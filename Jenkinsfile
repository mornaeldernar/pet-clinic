pipeline {

    agent any
    
    stages {

        stage('Build') {
            steps {
                echo 'Build'
                sh "mvn --batch-mode package" 
            }
        }

        stage('Archive Unit Tests Results') {
            steps {
                echo 'Archive Unit Test Results'
                step([$class: 'JUnitResultArchiver', testResults: 'target/surefire-reports/TEST-*.xml'])
            }
        }
        
        stage('Publish Unit Test results report') {
            steps {
                echo 'Report'
                publishHTML([allowMissing: false, alwaysLinkToLastBuild: true, keepAll: false, reportDir: 'target/site/jacoco/', reportFiles: 'index.html', reportName: 'jacaco report', reportTitles: ''])

            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploy'
                
                sh 'set'
                sh 'docker stop alpine-petclinic || true && docker rm alpine-petclinic || true'
                sh 'docker build -t alpine-petclinic -f Dockerfile.deploy .'
                sh 'docker --name alpine-petclinic --rm -d -p 9966:8080 alpine-petclinic'
            }
        }
    }
}

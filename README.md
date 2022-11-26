# Proyecto Final

## Descripcion del proyecto
Diseñar un pipeline de despliegue que cumpla con todas
las fases del despliegue: creación, construcción, pruebas y
despliegue de manera automática al detectar cambios.


## Alcance 
se buscara un proyecto desarrollado, se generará definiran contenedores, se instalará Jenkins, Terraform y un proyecto definido. Se publicará en Github
Se utilizará un tablero Kanban para definir los proceso, desarrollo iterativo, auto organizcion y bloque de tiempo para definir el programa
Scrum se utiliza para equipos de trabajo y como es individual se utilizará KANBAN, pero se utilizará desarrollo iterativo, auto organizacion y bloque de tiempo.
VALORES
ASPECTOS

## TESTS
shouldNotValidateWhenFirstNameEmpty
testInitCreationForm
testProcessCreationFormSuccess
testProcessCreationFormHasErrors
testInitFindForm
testProcessFindFormSuccess
testProcessFindFormByLastName
testProcessFindFormNoOwnersFound
testInitUpdateOwnerForm
testProcessUpdateOwnerFormSuccess
testProcessUpdateOwnerFormHasErrors
testShowOwner

	
![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/tests.png?raw=true)
![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/tests_code.png?raw=true)

## Imagen y contenedor, diferencias
Una imagen es un sistema completo (un sistema operativo completo)
un contenedor, esta aislado del sistema operativo, tiene solo lo que se necesita para ejecutar la aplicacion ( su aplicacion y dependencias ). Sirven para poder replicar la aplicacion en cualquier ambiente sin problemas

![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/docker.png?raw=true)

## GitHUB
Se crearon distintos repositorios de github con diferentes branches.
https://github.com/mornaeldernar/lab-test-ci.git
https://github.com/mornaeldernar/myAPI-books.git
https://github.com/mornaeldernar/myAPI-accounts.git
https://github.com/mornaeldernar/myAPI-terraform.git
https://github.com/mornaeldernar/pet-clinic.git


## Terraform
Descargar Terraform.
En el proyecto https://github.com/mornaeldernar/myAPI-terraform.git correr los comandos
'terraform init' para inicializar terraform
'terraform plan' para ver los cambios que hará en el terraform
![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/terraform.png?raw=true)

'terraform apply' para ejecutar el plan 
este repositorio creará un docker con mysql en el puerto 3307 y otro docker con jenkins en el puerto 8081

## Jenkins

![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/jenkins1.png?raw=true)
![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/jenkins2.png?raw=true)

# Spring PetClinic Application

This repository is a fork of the [spring-petclinic/spring-framework-petclinic](https://github.com/spring-petclinic/spring-framework-petclinic).

This application is used by [Online DevOps Dojo](https://github.com/dxc-technology/online-devops-dojo) to illustrate the DevOps practices.
Customization and vulnerabilities have been added for training purpose. If you wish to use the PetClinic application, please fork the [original repository](https://github.com/spring-projects/spring-petclinic).

<img width="1042" alt="petclinic-screenshot" src="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png">

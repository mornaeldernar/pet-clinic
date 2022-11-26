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
<ul>
<li>shouldNotValidateWhenFirstNameEmpty</li>
<li>testInitCreationForm</li>
<li>testProcessCreationFormSuccess</li>
<li>testProcessCreationFormHasErrors</li>
<li>testInitFindForm</li>
<li>testProcessFindFormSuccess</li>
<li>testProcessFindFormByLastName</li>
<li>testProcessFindFormNoOwnersFound</li>
<li>testInitUpdateOwnerForm</li>
<li>testProcessUpdateOwnerFormSuccess</li>
<li>testProcessUpdateOwnerFormHasErrors</li>
<li>testShowOwner</li>
</ul>
	
![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/tests.png?raw=true)
![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/tests_code.png?raw=true)

## Imagen y contenedor, diferencias
Una imagen es un sistema completo (un sistema operativo completo)
un contenedor, esta aislado del sistema operativo, tiene solo lo que se necesita para ejecutar la aplicacion ( su aplicacion y dependencias ). Sirven para poder replicar la aplicacion en cualquier ambiente sin problemas

![alt text](https://github.com/mornaeldernar/pet-clinic/blob/main/img/docker.png?raw=true)

## GitHUB
Se crearon distintos repositorios de github con diferentes branches.
<ul>
<li>https://github.com/mornaeldernar/lab-test-ci.git</li>
<li>https://github.com/mornaeldernar/myAPI-books.git</li>
<li>https://github.com/mornaeldernar/myAPI-accounts.git</li>
<li>https://github.com/mornaeldernar/myAPI-terraform.git</li>
<li>https://github.com/mornaeldernar/pet-clinic.git</li>
</ul>

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

Este repositorio se copió de [spring-petclinic/spring-framework-petclinic](https://github.com/spring-petclinic/spring-framework-petclinic).

Es utilizada por [Online DevOps Dojo](https://github.com/dxc-technology/online-devops-dojo) para practicar con los devops.
Se agregaron vulnerabilides para propositos de entrenamiento. La aplicacion origina se encuentra en [original repository](https://github.com/spring-projects/spring-petclinic).

<img width="1042" alt="petclinic-screenshot" src="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png">

# Microservice Python 🐍

Microservicio creado en Python como apoyo para la realización de despliegues automatizados de Infraestructura como código (IaC).

Objetivos: 
- Iniciar con el proyecto final myAPI
- Definir contenedor microservicio
- Desplegar servidor cloud

BEDU: Developer Engineering
* Sesión #6: Postwork
* Módulo #1: Desarrollo de software ágil
* Tema #6: Operaciones de Infraestructura como código (ansible, terraform y packer)

## Comandos

Crear imagen a partir del Dockerfile

> docker build -t microapp .

La etiqueta "--progress=plain" permite ver los "RUN ls" o "RUN pwd" en la explicación de la ejecución del Dockerfile
> docker build --no-cache --progress=plain -t microapp .

-----------------------------------------------------------------------------

Crear y ejecutar container

> docker create -p5000:5000 --name serpiente microapp

> docker start serpiente

Forma simple
> docker run -d --name serpiente -p5000:5000 microapp

-----------------------------------------------------------------------------

Otros

Para ver el slash "/" para las que son carpetas
> ls -l -p


## Construido con 🛠️

* [Phyton]() Lenguaje utilizado
* [Docker]() Servidor de contenedores
* [Visual Studio Code]() Editor utilizado

## Autor ✒️

* **Carlos Jaimez** - *Código inicial* - [carlosjz18](https://github.com/carlosjz18)

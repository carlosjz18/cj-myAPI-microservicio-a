# Microservice Python 馃悕

Microservicio creado en Python como apoyo para la realizaci贸n de despliegues automatizados de Infraestructura como c贸digo (IaC).

Objetivos: 
- Iniciar con el proyecto final myAPI
- Definir contenedor microservicio
- Desplegar servidor cloud

BEDU: Developer Engineering
* Sesi贸n #6: Postwork
* M贸dulo #1: Desarrollo de software 谩gil
* Tema #6: Operaciones de Infraestructura como c贸digo (ansible, terraform y packer)

## Comandos

Crear imagen a partir del Dockerfile

> docker build -t microapp .

La etiqueta "--progress=plain" permite ver los "RUN ls" o "RUN pwd" en la explicaci贸n de la ejecuci贸n del Dockerfile
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


## Construido con 馃洜锔?

* [Phyton]() Lenguaje utilizado
* [Docker]() Servidor de contenedores
* [Visual Studio Code]() Editor utilizado

## Autor 鉁掞笍

* **Carlos Jaimez** - *C贸digo inicial* - [carlosjz18](https://github.com/carlosjz18)

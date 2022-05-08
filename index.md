# Práctica 10 - Implementación de un cliente y un servidor de la aplicación de procesamiento de notas mediante Sockets en Node.js

## **OBJETIVO DE LA PRÁCTICA**
El objetivo de la práctica consiste en realizar una serie de problemas propuestos y resolverlos usando TypeScript para familiarizarnos con el lenguaje y su funcionamiento.

En esta práctica nos centraremos especialmente en la creación del servidor y del cliente así como del uso de los EventEmitter. AUnque también trabajaremos con la línea de comandos y el sistema de archivos de Node.js


## **ENUNCIADO**
Los requisitos que debe cumplir la aplicación de procesamiento de notas de texto son los enumerados a continuación:

1. La aplicación de notas deberá permitir que múltiples usuarios interactúen con ella.

2. Una nota estará formada, como mínimo, por un título, un cuerpo y un color (rojo, verde, azul o amarillo).

3. Cada usuario tendrá su propia lista de notas, con la que podrá llevar a cabo las siguientes operaciones:

Añadir una nota a la lista. Antes de añadir una nota a la lista se debe comprobar si ya existe una nota con el mismo título. En caso de que así fuera, deberá mostrarse un mensaje de error por la consola del cliente. En caso contrario, se añadirá la nueva nota a la lista y se mostrará un mensaje informativo por la consola del cliente.

- Modificar una nota de la lista. Antes de modificar una nota, previamente se debe comprobar que exista una nota con el título de la nota a modificar en la lista. Si existe, se procede a su modificación y se emite un mensaje informativo por la consola del cliente. En caso contrario, debe mostrarse un mensaje de error por la consola del cliente.

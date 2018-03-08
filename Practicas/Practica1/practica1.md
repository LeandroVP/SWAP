
# Práctica 1: Preparación de las herramientas
## Breve descripción de la práctica

Tras instalar las dos máquinas Linux con el Ubuntu Server, en ambas vamos a realizar
una instalación completa de servidor web: Apache + PHP + MySQL.

Una vez que tengamos las máquinas instaladas y los servidores LAMP configurados,
comprobaremos que Apache está funcionando.

## Objetivos

1. Acceder por ssh de una máquina a otra
2. Acceder mediante la herramienta curl desde una máquina a la otra

## Proceso
*descripción del proceso*

Accedemos al archivo situado en la ruta:

![ruta archivo](./Imagenes/STEP0.PNG)

Lo modificamos de forma que quede como en la siguiente imagen:

![modificacion archivo](./Imagenes/STEP1.PNG)
*la dirección ip debe ser distinta para cada máquina*

Reiniciamos los servicios con el siguiente comando para aplicar los cambios:
![reinicio servicios](./Imagenes/STEP2.PNG)

Comprobamos que desde el host podemos acceder al archivo de una de las máquinas:
![Acceso desde host](./Imagenes/STEP3.PNG)

Comprobamos que podemos acceder al archivo hola.html mediante curl desde una máquina a otra:
![Acceso curl](./Imagenes/STEP4.PNG)

Por último, vemos que podemos acceder mediante ssh a una máquina desde la otra:
![Acceso ssh](./Imagenes/STEP5.PNG)

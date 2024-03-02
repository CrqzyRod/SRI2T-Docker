# Juan Manuel González Márquez - SRI - 2ASIR
## Contenedores Docker
### Introducción
En esta práctica crearemos dos contenedores de docker uno con dns y otro con un servidor web, en mi caso apache.
### Instalación Docker
Instalamos paquetes para permitir descargar e instalar paquetes a través de https.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/c2784c2f-5d08-401e-ade2-5a558b63b777)

Agregamos la clave privada para verificar los paquetes de Docker en Ubuntu.
![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/b43739f7-74f1-43b5-8313-a0de4b5885d8)

Añadimos el repositorio para descargar Docker.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/b94f241f-02bf-4c09-8851-a31a49d76ab3)

Instalamos Docker.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/d9be94bb-180c-4172-97ae-396a21a34939)

Verificamos la instalación.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/f68addc9-6668-431d-b820-0fc861bd6707)

### Contenedor Docker DNS
Descargamos la imagen oficial de bind9 para ubuntu.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/491f4d2a-51df-4348-b402-653391b8db13)

Antes de correr el contenedor docker con dns vamos a crear nuestra propia red de docker usando el comando docker network create.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/a0a7fe03-a0bd-4d05-8cf5-a2bd511ee551)

Corremos el contenedor indicando la red creada anteriormente y los puertos de salida tcp y udp.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/be360f29-8a77-4fed-865c-0dd453a51d57)

Ejecutamos un terminal interactivo para acceder al contenedor.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/2b2451ab-c8d6-44bb-823f-3ac1efe02f2f)

Comprobamos como podemos hacer ping al dns de google correctamente.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/206a7b7d-5fcd-4602-b020-11201f763f28)

### Contenedor Docker Apache

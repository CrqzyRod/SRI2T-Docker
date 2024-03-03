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

### Requisitos previos
Antes de correr ambos contenedores, crearemos una red de docker la cual usaremos en ambos contenedores.

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/dd6d67ff-b0f2-4cff-9528-03bf9e8f7548)

### Contenedor Docker DNS

Fichero docker compose DNS:

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/d4d49776-a0af-46c2-b1db-b617a66937a0)

Corremos el fichero docker compose de DNS:

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/72fd5997-6754-40cc-b642-a38bdfde4a9c)

### Contenedor Docker Apache

Fichero docker compose Apache:

![imagen](https://github.com/CrqzyRod/SRI2T-Docker/assets/122454007/9c28317a-53ef-48b5-b3f0-b27f843f9c11)



								Bienvenido a nuestro proyecto!!

Para ejecutar este archivo en su totalidad necesitara contar previamente con
	-Docker
	-Docker Compose
	-Python
	-Git
	-ADMIN paquetes de python(Pip)

Primero se debera clonar el repositorio en su maquina local:
	git clone https://github.com/AgustinOlmedoo/efi-docker.git


Generar una copia del archivo  .env.example y guardarlo como .env Modificando ademas, los datos que encontramos dentro de este

Para poder ejecutarlo:

    Abrir el archivo desde la consola           cd efi-docker

    Correr el sig comando:                      sudo docker-compose build

    Luego el siguiente:                         sudo docker-compose up


Si todo funciona correctamente, abrir el puerto que se está exponiendo en la consola 
        (ejemplo:   http://0.0.0.0:5005)

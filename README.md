# Flask & Docker

C�digo que nos muestra c�mo podemos ejecutar una aplicaci�n Flask dentro de un Docker.

Uso:

~~~
$ docker build -t imagenflask .
$ docker run -d --name mycontainer -p 80:80 imagenflask
~~~
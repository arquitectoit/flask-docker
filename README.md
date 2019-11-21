# Flask & Docker

Código que nos muestra cómo podemos ejecutar una aplicación Flask dentro de un Docker.

Uso:

~~~
$ docker build -t imagenflask .
$ docker run -d --name mycontainer -p 80:80 imagenflask
~~~
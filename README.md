# Meetup - CodeReview 101

***
By: Retr0
***

### Live demo:

- Para desplegar:

~~~bash
cd LiveDemo
docker-compose up --build
# Configurar WP en http://localhost/
# Ir a http://localhost/wp-admin.php -> installed plugins -> activar notificationx
# Descargar plugin para analizar desde https://downloads.wordpress.org/plugin/notificationx.2.8.2.zip
~~~

- Usar grep:

~~~bash
docker run --rm -v "$PWD:/src" semgrep/semgrep semgrep --config <rule> notificationx/
~~~

### Actividad final

- Para desplegar:

~~~bash
docker-compose up -d
~~~

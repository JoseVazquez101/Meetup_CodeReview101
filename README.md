# Meetup - CodeReview 101

***
By: Retr0
***

### Live demo:

- Para desplegar:

~~~bash
docker-compose up --build
# Configurar WP en http://localhost/
# Ir a http://localhost/wp-admin.php -> installed plugins -> activar notificationx
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

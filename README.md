# beejee-test
Demo : https://bekzod-beejee.herokuapp.com/
Admin login : admin@mail.com 123

<pre>composer install</pre>

Rename .env to .env.local file and configure database options

Create database tables: 
<pre>vendor/bin/doctrine orm:schema-tool:create</pre>

Run server
<pre>php -S localhost:8000 -t public/</pre>

# Used packages :

Doctrine ORM, Symfony HttpFoundation, Symfony DotEnv

Also used my own classes from https://github.com/bekaproger/lil-frame.

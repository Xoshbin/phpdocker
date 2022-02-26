# phpdocker
Docker PHP development environment with Nginx and Composer.
it's generated with phpdocker, just added PHP Composer.

# How to run #

run `docker-compose up`

And write your code in the root folder.

to run PHP composer:

`docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer update`
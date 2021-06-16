# docker-complete-env-setup

Open the terminal command line and go inside the laravel folder, and launch this commands:

'docker.compose build'

'docker-compose up -d'

if have need to create and migrate the db, or use other commands, launch the Laravel commands in this way:
docker-compose run app php artisan

The app will available at the address http://0.0.0.0:8009

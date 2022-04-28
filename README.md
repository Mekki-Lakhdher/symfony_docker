# symfony_docker

This a docker set up, with Symfony5 framework and MySQL8 database server.

1. In the docker-compose.yml file, edit the services ports if necessary.
2. Create .env file from the .env.sample file under the root directory.
3. Set your own environment variables.
4. Install framework dependencies by running "composer install" inside symphony directory.
5. Launch the application via NGINX server on : http://localhost:{NGINX_PORT}.
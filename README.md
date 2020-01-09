"# wordpress-docker" 

Quickly build wordpress projects using docker.
With this template you can quickly build your wordpress projects using docker-compose.

Requeriments:

- Docker and docker-compose must be installed.

How to use:

You need to setup your environment variables, you can use the provided .env.example file, 
you need yo duplicate this file and rename the duplicated to .env

Example:

	cp .env.example .env
	nano .env

Then you can reemplace the variables:
	MYSQL_ROOT_PASSWORD=my_secret_password
	MYSQL_USER=the_admin
	MYSQL_PASSWORD=my_secret_password

run with:

    docker-compose up

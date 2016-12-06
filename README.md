# dev-apache-php7-mysql
Docker compose for development environment consists of Apache, PHP7 &amp; MYSQL

## Setup
- Make necessary changes to the `docker-compose-yaml` or `apache2.conf`
- copy your project files into the `src` folder
- copy your database files into the `db_data` or you may import your sql database after containers are setup.
- run `docker-compose up -d`
- run `docker ps` to see both containers `web` & `db` are running
- hit `localhost` and your should see the phpinfo page.


_NB: source image taken from https://github.com/pablofmorales/docker-apache-php7_
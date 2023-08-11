Docker Compose for Wordpress Local Development
==============================================

This is a docker-compose setup for local development of Wordpress sites. 
It uses the following containers:

* [Wordpress](https://hub.docker.com/_/wordpress/)
* [MySQL](https://hub.docker.com/_/mysql/)
* [phpMyAdmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)

## Requirements

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)

## Installation

1. Clone this repository in the same directory as your Wordpress project.
2. Create the `data/` directory at the root of this repository.
3. Create the `wordpress/` directory at the root of this repository.
4. Go to the `wp-docker/` directory (this repository).
5. Run `docker-compose up -d`.
6. Go to [http://localhost](http://localhost) to access your Wordpress site.



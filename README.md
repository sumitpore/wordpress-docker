# Apache + MySQL + PHP + WordPress + PhpMyAdmin Docker

This docker-compose.yml file creates a network of docker containers to set up a WordPress website along with phpmyadmin.

How to use
```bash
git clone https://github.com/sumitpore/wordpress-docker.git
cd wordpress-docker/
docker-compose up -d
```

Once all docker containers are up and running, you can access the wordpress website as:
```
  http://<your_ip_address>:8000
```

PHPMyAdmin can be accesssed as:
```
  http://<your_ip_address>:8001
```

MySQL Database Credentials are:
* Username: wordpress
* Password: wordpress

### Note
* If you want to make changes in the php.ini file, then you can create php.ini file inside `php-ini` folder.

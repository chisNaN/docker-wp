#Docker WordPress

> A docker compose for WordPress apps taken from [bitnami](https://hub.docker.com/r/bitnami/wordpress/) plus [phpMyAdmin official docker image](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)

###Installation

[Dowload docker for Mac](https://docs.docker.com/docker-for-mac)

```
curl -LO https://raw.githubusercontent.com/chisNaN/docker-wp/master/docker-compose.yml

docker-compose up -d
```

###Access to your apps

[Your WP app](http://127.0.0.1:81)

[phpMyAdmin](http://127.0.0.1:8181)

:bulb: ports 81, 8181 and 3307 (on your host) were chosen in order not to interfer with already installed apache and mysql services

###Connect to mariadb server in command (using empty password)

```
mysql -u root -h 127.0.0.1 -P 3307 -p
```

###Default WP environment variables

* WORDPRESS_USERNAME: WordPress application username. Default: user

* WORDPRESS_PASSWORD: WordPress application password. Default: bitnami

* WORDPRESS_EMAIL: WordPress application email. Default: user@example.com

* WORDPRESS_FIRST_NAME: WordPress user first name. Default: FirstName

* WORDPRESS_LAST_NAME: WordPress user last name. Default: LastName

* WORDPRESS_BLOG_NAME: WordPress blog name. Default: User's blog

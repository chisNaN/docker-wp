#Docker WordPress

> A docker compose for WordPress apps taken from [bitnami](https://hub.docker.com/r/bitnami/wordpress/) plus [phpMyAdmin official docker image](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)

###Installation

[Dowload docker for Mac](https://docs.docker.com/docker-for-mac)

```
curl -LO https://raw.githubusercontent.com/chisNaN/docker-wp/master/docker-compose.yml

docker-compose up -d
```

###Access to your apps

```
sudo nano /etc/hosts

127.0.0.1   wp.lo
127.0.0.1   pma.lo
```

[Your WP app](http://wp.lo/)

[phpMyAdmin](http://pma.lo)


###Connect to mariadb server in command (using empty password)

```
mysql -u root -h 127.0.0.1 -P 3307 -p
```

###Default WP environment variables

* WORDPRESS_USERNAME: Default: user

* WORDPRESS_PASSWORD: Default: bitnami

* WORDPRESS_EMAIL: Default: user@example.com

* WORDPRESS_FIRST_NAME: Default: FirstName

* WORDPRESS_LAST_NAME: Default: LastName

* WORDPRESS_BLOG_NAME: Default: User's blog

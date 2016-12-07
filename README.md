#Docker WordPress

> A docker compose for WordPress apps taken from [bitnami](https://hub.docker.com/r/bitnami/wordpress/) plus [phpMyAdmin official docker image](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)

```
curl -LO https://raw.githubusercontent.com/chisNaN/docker-wp/master/docker-compose.yml

docker-compose up -d
```

:bulb:

[Your WP app](http://127.0.0.1:81)

[phpMyAdmin](http://127.0.0.1:8181)

###Default WP environment variables

* WORDPRESS_USERNAME: WordPress application username. Default: user

* WORDPRESS_PASSWORD: WordPress application password. Default: bitnami

* WORDPRESS_EMAIL: WordPress application email. Default: user@example.com

* WORDPRESS_FIRST_NAME: WordPress user first name. Default: FirstName

* WORDPRESS_LAST_NAME: WordPress user last name. Default: LastName

* WORDPRESS_BLOG_NAME: WordPress blog name. Default: User's blog
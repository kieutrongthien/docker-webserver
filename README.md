# Docker Webserver

This is just my local docker compose file. You just need to clone your project into the **web** folder and create **nginx/conf/yourwebsite.local.comf**.

In this docker compose, I'm using PHP 7.4, PHP 8.1, Redis, MySQL, Nginx.

## SSL

Using **[mkcert](https://github.com/FiloSottile/mkcert)** to manage local SSL

## Setup

Everything you need is only run the command below:

```bash
$> docker compose up -d
```

If you want to stop / restart a specific service:

```bash
$> docker restart nginx #Or php74, php81, redis, mysql
```

## License

MIT
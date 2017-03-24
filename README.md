# dockerized-docs-haproxy

# What is it?
Dockerzied HAProxy documentation for offline use.

# Image description #
- Base image: `python:2.7`
- Httpd server is installed
- The HAProxy `1.5`,`1.6`,`1.7` branches are cloned and docs are built using [haproxy-dconv](https://github.com/cbonte/haproxy-dconv) into httpd `DocumentRoot` (`/var/www/html`)

# How to use this image #

```console
$ docker run -d genadipost/haproxy
```
You can test it by visiting http://container-ip:80

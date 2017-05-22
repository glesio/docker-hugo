glesio/hugo
===========

`glesio/hugo` is a [Docker](https://www.docker.io) image based in [Alpine Linux](https://alpinelinux.org/) for [Hugo](http://gohugo.io) static website engine.


Examples
--------
```
# Start Server
docker container run -d --name hugo -p 1313:1313 -v $PWD:/hugo glesio/hugo
```
```
# Build Site
docker container run --rm --name hugo -v $PWD:/hugo glesio/hugo hugo
```

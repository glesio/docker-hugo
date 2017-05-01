glesio/hugo
===========

`glesio/hugo` is a [Docker](https://www.docker.io) image for [Hugo](http://gohugo.io) static sites.


Examples
--------
```
# Start Server
docker container run -d --name hugo -v $PWD:/hugo glesio/hugo
```
```
# Build Site
docker container run --rm --name hugo -v $PWD:/hugo glesio/hugo hugo
```

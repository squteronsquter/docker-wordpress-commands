# Run this in a docker Nginx container

```
docker pull nginx

docker run -p 80:80 -v /Users/gray/Sites/DOCKER_WEBSITES/one:/usr/share/nginx/html nginx

```

or if you want a more universal and "movable" version

```
cd /path/to/your/local/files/you/want/nginx/to/show

docker run -p 8080:80 -v $PWD:/usr/share/nginx/html nginx

```
and still yet one variation for those you are on Windows

```
docker run -p 8080:80 -v ${PWD}:/usr/share/nginx/html nginx

```

_Happy coding_


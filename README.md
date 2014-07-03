docker-heritrix
===============

docker container with **heritrix-3.2.0**

# Run

```console
$ mkdir path/to/persistent/heritrix-data
$ docker run -it -p 8443:8443 -v path/to/persistent/heritrix-data:/mnt/heritrix-data cbeer/heritrix
$ curl https://heritrix:heritrix@localhost:8443
```
  

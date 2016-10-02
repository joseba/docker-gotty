# docker-gotty

A simple [gotty](https://github.com/yudai/gotty) image based on Alpine Linux.

## Usage

Get a shell:

```
docker run -ti --rm -p 8080:8080 joseba/docker-gotty
```

Output `top` for the host:

```
docker run -i --rm --pid=host --user nobody -p 8080:8080 joseba/docker-gotty top

# python-node-nginx

This is the GitHub repo of the Docker image for Python, Node.js, and NGINX. See the Hub page [here](https://hub.docker.com/r/jackywithawhitedog/python-node-nginx).

Currently only support Python 3.7.12, Node.js 16.13.0, and NGINX 1.20.1.

- [Python](https://github.com/docker-library/python)
- [Node.js](https://github.com/nodejs/docker-node)
- [NGINX](https://github.com/nginxinc/docker-nginx)

## Typical Usage

### Run the container with this image

```shell
$ docker run --name CONTAINER-NAME -v /path/to/your/site:/usr/share/nginx/html:ro -d jackywithawhitedog/python-node-nginx
```

### Use in Dockerfile

```dockerfile
FROM jackywithawhitedog/python-node-nginx
```

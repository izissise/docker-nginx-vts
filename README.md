# docker-nginx-vts
Nginx with vts modules in an alpine docker image

Ningx module vts -> https://github.com/vozlt/nginx-module-vts

This inspired by these two images:
- https://hub.docker.com/r/xcgd/nginx-vts/dockerfile
- https://github.com/DataDog/docker-library/blob/master/nginx-vts/Dockerfile


# Export metrics
You can export the exposed metric to prometheus using [nginx-vts-exporter](https://github.com/hnlq715/nginx-vts-exporter)

# How to build
`docker build -t izissise/nginx-vts .`

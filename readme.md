Property Window Docker [![by](https://img.shields.io/badge/by-%40marcgeurts-ff69b4.svg?style=flat-square)](https://github.com/marcgeurts)
========================

This is a docker repository that runs on [Docker](https://www.docker.com/).

## Usage

> Helpful commands for developing

Build nginx:
```bash
$ docker build -t propertywindow/nginx:latest nginx/
```
Build php:
```bash
$ docker build -t propertywindow/php:latest php/
```
Push nginx:
```bash
$ docker push propertywindow/nginx:latest
```
Push php:
```bash
$ docker push propertywindow/php:latest
```
---
# golang-starter-kit

Golang starter kit for application development.

This starter kit provides:
* Uses Go Module
* Build inside docker
* Static binary build
* Jenkins pipeline

## Requirements
### Local Build
* Golang 1.11 or higher
* make

### Docker build
* docker
* docker-compose

## Build
### Local Build
```bash
$ make vendor
$ make compile
```

### Docker Build
```bash
$ make compile-docker; make compile-rmi
```

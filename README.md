# golang-starter-kit

Golang starter kit for application development.

This starter kit provides:
* Uses Go Module
* Build inside docker
* Static binary build


## Build
```bash
# Install depeldencies to vendor/ directory.
$ make vendor

# Build with local installed golang
$ make build

# Build with docker
$ make docker-build; make docker-build-rmi
```

# Simple GO Lang REST API

> Simple RESTful API to create, read, update and delete books. No database implementation yet

## Quick Start


``` bash
# Install mux router
go get -u github.com/gorilla/mux
```

``` bash
go build
./smaheshacharya
```

## Endpoints
```bash
/api/books => GET
/api/books/{id} => GET Single
/api/books => POST
/api/books/{id} => UPDATE
/api/books/{id} => DELETE
```

# My books in Kubernetes

![my-books-image](doc/my_books_logo.png)

Definitions to run the My books ecosystem on Kubernetes locally, the version for GCP (the gke folder) is deprecated.

## Prerequisites

- A kubernetes Cluster (see this [link](https://github.com/AlfredoMarino/kind))

### Install

- Clone this repo
```sh
$ git clone https://github.com/AlfredoMarino/my-books-gke.git
$ cd my-books-gke
```

### To apply on your kubernetes cluster

```sh
$ kubectl apply -f local/ -R
```

### For test

**my-books-ui**
```sh
$ curl http://localhost:30000
```

**my-books-service**
```sh
$ curl http://localhost:31000/my-books-service/api/v1/search?name=Rayuela
```

## Note

The docker-compose file is for quick tests

## Related projects

+ [my-books-service](https://github.com/AlfredoMarino/my-books-service)
+ [my-books-mysql](https://github.com/AlfredoMarino/my-books-mysql)
+ [my-books-ui](https://github.com/AlfredoMarino/my-books-ui)
+ [kind](https://github.com/AlfredoMarino/kind)
+ [My docker-hub](https://hub.docker.com/u/aamv)

## Contributing

Pull requests are welcome.
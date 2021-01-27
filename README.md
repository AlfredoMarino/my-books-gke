# My books in Kubernetes


## To run on your kubernetes cluster

1. Run

        kubectl apply -f local/ -R

2. Test

    **my-books-ui**

        curl localhost:30000

    **my-books-service**

        curl http://localhost:31000/my-books-service/api/v1/search?name=Rayuela


## Note

The docker-compose file is for quick tests
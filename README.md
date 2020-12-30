# My books in Kubernetes


## To Run

1. In KinD folder recreate a cluster
2. Run

        kubectl apply -f templates/

3. test

    UI

        curl localhost:30000

    Service

        curl localhost:31000


#### TODO

+ Service:
    + recibir el puerto dentro del rango 30000 - 32000
+ UI:
    + Recibir y apuntar al service y a su respectivo puerto correctamente

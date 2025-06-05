# Solution

In order to use the solution, you may clean the env first by using `make clean` from terminal and then `make start` to build all the objects in k8s. Then `make port-forward` may be used to forward the service to the local machine and do requests to the API.
Finally, with `make delete-pods` the backend and database pods will be deleted to test the persistence of data.

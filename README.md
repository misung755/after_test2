# dockerfiles-centos-user-adderable
Centos7, It support base user creation and password setting.

# Building & Running

Copy the sources to your docker host and build the container, and to run.
```
	docker build --rm -t misung755/ubuntuxxx .
	docker run -it --name m3 misung755/ubuntuxxx
```
Get the port that the container is listening on:

```

```

To test, ("nowage" is username. )
```
	su - misung755
```
To Rollback
```
    docker rm m3 -f
    docker rmi misung755/ubuntuxxx
```

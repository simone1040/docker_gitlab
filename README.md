# docker_gitlab
Docker-compose file that enables gitlab in your machine and allow you to use container registry.

To start gitlab you must change the url into docker-compose file and run this snippet:

```
docker-compose up -d
```

you can check the installation process with this snippet: 

```
docker logs gitlab-image
```

Once the installation process is completed, you can push your code and docker instance inside repository.

To push a docker instance into container registry follow this steps:

* follow settings/Access Token and create a new personal access token

* login into docker through this line: 

```
docker login IP:PORT -u USERNAME -p PERSONAL ACCESS TOKEN
```

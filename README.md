# docker-jenkins

Containerized Jenkins based on the [official image](https://registry.hub.docker.com/_/jenkins/),
pre-configured with git & docker support

A pre-built image is available at the [Docker Hub Registry](https://registry.hub.docker.com/u/jsallis/jenkins/)

#### Installed plugins

- [Git](https://wiki.jenkins-ci.org/display/JENKINS/Git+Plugin)
- [Docker build step](https://wiki.jenkins-ci.org/display/JENKINS/Docker+build+step+plugin)

#### Example usage

```
docker run \
    -p 8080:8080 \
    jsallis/jenkins
```

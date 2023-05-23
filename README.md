# fabric8io-docker-maven-plugin-issue

Example for https://github.com/fabric8io/docker-maven-plugin/issues/1676

Run the following command **twice**

```
DOCKER_HOST=unix:///var/run/user/1000/podman/podman.sock ./mvnw -Ddocker.noCache install
```



# Alpine Java 11 Docker image

![Docker Automated build](https://img.shields.io/docker/automated/lpicanco/java11-alpine.svg) 
![Docker Build Status](https://img.shields.io/docker/build/lpicanco/java11-alpine.svg)
![MicroBadger Size](https://img.shields.io/microbadger/image-size/lpicanco/java11-alpine.svg)
![MicroBadger Layers](https://img.shields.io/microbadger/layers/lpicanco/java11-alpine.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/lpicanco/java11-alpine.svg)

OpenJDK 11 on Alpine

## How to use this image

```console
$ docker run --rm lpicanco/java11-alpine java -version
```

### JDK 11 Modules
```
jdk.jfr,jdk.management.agent,java.base,java.logging,java.xml,jdk.unsupported,java.sql,java.sql.rowset,java.naming,java.desktop,java.management,java.security.jgss,java.instrument
```
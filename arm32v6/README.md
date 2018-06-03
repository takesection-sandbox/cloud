awscli
======

Raspbian

* [Get Docker CE for Debian](https://docs.docker.com/install/linux/docker-ce/debian/)

# Build

```
docker build . -t arm32v6-awscli
```

# RUN

```
AWS_ACCESS_KEY_ID=******** AWS_SECRET_ACCESS_KEY=******** \
docker run -it -e AWS_ACCESS_KEY_ID -e AWS_SECRET_ACCESS_KEY arm32v6-awscli /bin/sh
```

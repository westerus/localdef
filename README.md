![logo](https://hsto.org/files/064/f34/34b/064f3434bba04ad3bb7fbcd091ad810c.png)

# What is LocalDef?

Custom docker containers with enabled localset for define system LANG

# LocalDef agent images

LocalDef are based on latest Alpine, jessie Debian and trusty Ubuntu images. The available versions of localdef are:

    LocalDef Alpine 3.4 (tags: alpine-3.4, alpine-lates, latest)
    LocalDef Denian Jessie (tags: debian-jessie, debian-latest)  
    LocalDef Ubuntu Trusty (tags: ubuntu-trusty, ubuntu-latest)

Images are updated when new releases are published. The image with ``latest`` tag is based on Alpine Linux.

# How to use this image

Start a localdef container as follows:

    docker run --name some-name-proyect -e TZ="Europe/Madrid" -e IDIOM="es_ES" --rm -ti westerus/localdef:tag

Docker Image From Debian with etcd
==================================

Download etcdkeeper from source and run it in debian

## Build (optional as it is on dockerhub):

```bash
docker build --build-arg ETCDKEEPERVER=0.7.5 -t fanchthesystem/debian-etcdkeeper:0.7.5 -f Dockerfile .
```

## Start:

```bash
docker run -dt -p 8080:8080 fanchthesystem/debian-with-etcdkeeper:latest
```

## Use:

Open Firefox and go to :

http://127.0.0.1:8080/etcdkeeper/

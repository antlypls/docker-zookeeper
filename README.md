ZooKeeper in Docker
===================

Apache ZooKeeper is an open-source server which enables highly reliable distributed coordination.

This repo is based on some examples found on the Internet that I can't find origin of anymore.

How to Run
----------

```
docker run -p 2181:2181 antlypls/zookeeper
```

How to Build from Source
------------------------

```
docker build -t antlypls/zookeeper .
```

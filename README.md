# IOTA Node

## Setup

* Install and run Docker. 

* Configure iota.ini

```
mkdir -p ~/iota/iri/data;
docker run -d --net=host --name iota-node -v iota.ini:/iri/iota.ini -v ~/iri/data:/iri/data iotaledger/iri:latest -p 14265
```

## References

* https://github.com/iotaledger/iri
* https://github.com/iotaledger/iri#docker
* https://github.com/iotaledger/iri/blob/dev/DOCKER.md

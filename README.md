# docker-locust-cluster
Runnning locust cluster on docker

Build locust cluster using [ushios/locust](https://hub.docker.com/r/ushios/locust/) image.

# Get started

Fork or clone this repository and edit `http://localhost` in `docker-compose.yml` and `locustfile.py`.

```console
$ docker-compose up -d
$ open http://localhost:18080
```

# Documents

## Change number of slaves

```console
$ docker-compose scale slave=10 # change to 10 slaves
```

See also [Loucst Documentation](http://docs.locust.io/en/latest/index.html)

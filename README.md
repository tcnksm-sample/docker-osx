# Run Docker from OSX

Docker client OSX is [released](https://github.com/dotcloud/docker/blob/master/CHANGELOG.md#073-2014-01-02)

## Usage

```
$ vagrant up
```

```
$ export DOCKER_HOST="192.168.50.4:5422"
```
Note: IP and PORT can change in Vagrantfile


```
$ docker build Dockerfile
```

## Reference

- [Introducing dvm - Docker in a box for Unsupported Platforms, like the Mac](http://hw-ops.com/blog/2014/01/07/introducing-dvm-docker-in-a-box-for-unsupported-platforms/)

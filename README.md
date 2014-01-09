# Run Docker from OSX

Docker client for OSX is [released](https://github.com/dotcloud/docker/blob/master/CHANGELOG.md#073-2014-01-02)

## Usage

Run Vagrant VM

```
$ vagrant up
```

Set Docker host
```
$ export DOCKER_HOST="192.168.50.4:5422"
```
Note: IP and PORT can change in Vagrantfile, `DOCKER_URL` and `DOCKER_PORT`


Try it !

```
$ docker build Dockerfile
```

## Requirement

Install docker client by Homebrew

```
$ brew bundle
```


## Reference

- [Introducing dvm - Docker in a box for Unsupported Platforms, like the Mac](http://hw-ops.com/blog/2014/01/07/introducing-dvm-docker-in-a-box-for-unsupported-platforms/)

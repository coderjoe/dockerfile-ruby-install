# A ruby-install image for Docker

Source for [coderjoe/ruby-install](https://registry.hub.docker.com/u/coderjoe/ruby-install),
a Docker image intended to be used as the base for images which need to install build versions
of Ruby.

## Pulling from Docker Hub

```
docker pull coderjoe/ruby-install
```

## Using in your Dockerfile

```
# latest version
FROM coderjoe/ruby-install

# specific version
FROM coderjoe/ruby-install:0.5.0
```

## Latest stable versions

* 0.5.0

## Contributing

Suggestes, contributions, and bugs are welcome.
Please create a GitHub Issue.

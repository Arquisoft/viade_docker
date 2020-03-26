# Example of a Docker-compose configuration

This repository contains an example of an app with a docker-compose configuration.

The repository is based on the [Solid profile viewer tutorial](https://github.com/solid/profile-viewer-tutorial)
but this time built with the [Solid React components](https://github.com/solid/react-components).

## Running with docker compose

```
docker-compose up
```

It will create two services: the node solid server running at port 8443 and the React app at port 3000

You may need to configure your `/etc/hosts` file adding this line to:

```
127.0.0.1	*.localhost
```

In Windows, the `/etc/hosts` file is usually located at: `c:\Windows\System32\Drivers\etc\hosts`

The solid server con be configured following [these instructions](https://github.com/solid/node-solid-server#use-docker) 
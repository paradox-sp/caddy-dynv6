[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/yourusername/caddy-dynv6/Docker%20Build%20and%20Publish?label=build&logo=github)](https://github.com/yourusername/caddy-dynv6/actions)
[![Docker Pulls](https://img.shields.io/docker/pulls/paradoxsp/caddy-dynv6?logo=docker)](https://hub.docker.com/r/paradoxsp/caddy-dynv6)
[![GitHub License](https://img.shields.io/github/license/yourusername/caddy-dynv6)](https://github.com/yourusername/caddy-dynv6/blob/main/LICENSE)

# caddy-dynv6

Please see the official [Caddy Docker Image](https://hub.docker.com/_/caddy) for deployment instructions.

Builds are available at the following Docker repositories:

* Docker Hub: [docker.io/paradoxsp/caddy-dynv6](https://hub.docker.com/r/paradoxsp/caddy-dynv6)

Few things to note: 

1. You should add DYNV6_API_TOKEN as environment variables or can directly replace with the actual token to your `docker run` command. Example:

      ```
            tls {
            dns dynv6 {env.DYNV6_API_TOKEN}
            }
      ```

[dockerhub-image]: https://img.shields.io/docker/pulls/paradoxsp/caddy-dynv6?label=DockerHub%20Pulls&style=for-the-badge
[dockerhub-url]: https://hub.docker.com/r/paradoxsp/caddy-dynv6

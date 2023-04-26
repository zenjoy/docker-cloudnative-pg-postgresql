# cloudnative-pg-postgresql

[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-zenjoy%2Fpostgresql-lightgrey?style=flat)](https://hub.docker.com/r/zenjoy/postgresql)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/zenjoy/docker-cloudnative-pg-postgresql?label=version)](https://github.com/zenjoy/docker-cloudnative-pg-postgresql/tags)
[![License](https://img.shields.io/github/license/zenjoy/docker-cloudnative-pg-postgresql)](https://github.com/zenjoy/docker-cloudnative-pg-postgresql/blob/main/LICENSE)

The official [CloudNativePG PostgreSQL](https://github.com/cloudnative-pg/postgres-containers)
Docker image with support for all locales.

Available on Docker Hub or GitHub Container Registry (GHCR) for AMD64 or ARM64.

```sh
# Docker Hub
docker pull zenjoy/postgresql:latest

# GHCR
docker pull ghcr.io/zenjoy/postgresql:latest
```

## Container signatures

All images are automatically signed via [Cosign](https://docs.sigstore.dev/cosign/overview/) using
[keyless signatures](https://docs.sigstore.dev/cosign/keyless/). You verify the integrity of these
images as follows:

```sh
cosign verify \
  --certificate-oidc-issuer https://token.actions.githubusercontent.com \
  --certificate-identity-regexp https://github.com/zenjoy/docker-cloudnative-pg-postgresql/.github/workflows/ \
  zenjoy/postgresql:latest
```

## Contributing

Feel free to contribute and make things better by opening an
[Issue](https://github.com/zenjoy/docker-cloudnative-pg-postgresql/issues) or
[Pull Request](https://github.com/zenjoy/docker-cloudnative-pg-postgresql/pulls).

## License

View
[license information](https://github.com/zenjoy/docker-cloudnative-pg-postgresql/blob/main/LICENSE)
for the software contained in this image.

FROM ghcr.io/cloudnative-pg/postgresql:14.7-10

USER root

RUN apt update \
  && apt install -y --no-install-recommends locales-all \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

USER 26

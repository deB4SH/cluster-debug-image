FROM docker.io/debian:bookworm-20241111
# install tools
RUN apt-get update \
    && apt-get install -y --no-install-recommends git curl wget mtr inetutils-traceroute dnsutils netcat-openbsd\
    && rm -rf /var/lib/apt/lists/* \
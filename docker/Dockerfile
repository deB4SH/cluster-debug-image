FROM docker.io/debian:bookworm-20241111
# install tools
RUN apt-get update \
    && apt-get install -y --no-install-recommends openssh-client git curl wget mtr inetutils-traceroute dnsutils netcat-openbsd iputils-ping iputils-tracepath iputils-clockdiff iputils-arping fio iperf3\
    && rm -rf /var/lib/apt/lists/* \

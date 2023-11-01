FROM debian:latest@sha256:fab22df37377621693c68650b06680c0d8f7c6bf816ec92637944778db3ca2c0

RUN apt-get update && apt-get install -yq openssl

ADD make_certs.sh /


WORKDIR /data
VOLUME ["/data"]
CMD /make_certs.sh

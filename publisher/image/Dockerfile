FROM ubuntu-debootstrap:14.04

ADD bin/publisher /usr/local/bin/publisher
ENTRYPOINT ["/usr/local/bin/publisher"]

ENV DEIS_RELEASE 1.5.0-dev


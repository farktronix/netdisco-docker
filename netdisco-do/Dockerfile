# vim: ft=Dockerfile
ARG TAG=latest
FROM docker.io/farktronix/netdisco-arm:${TAG}-backend

LABEL org.label-schema.name="netdisco-do" \
      org.label-schema.description="CLI App for Netdisco"

ENTRYPOINT ["/home/netdisco/bin/netdisco-do"]
CMD [""]

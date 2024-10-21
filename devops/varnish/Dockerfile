# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="Plone Foundation <claudioweiler@users.noreply.github.com>" \
      org.label-schema.name="trepr-varnish" \
      org.label-schema.description="Treinamento TRE-PR Varnish image." \
      org.label-schema.vendor="Plone Foundation"

COPY etc/varnish.vcl /etc/varnish/default.vcl

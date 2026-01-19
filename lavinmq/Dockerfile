ARG BUILD_FROM=cloudamqp/lavinmq:2.6.3
FROM $BUILD_FROM

LABEL \
  io.hass.version="VERSION" \
  io.hass.type="addon" \
  io.hass.arch="aarch64|amd64"

COPY lavinmq.ini /etc/lavinmq/lavinmq.ini

# VERSION 0.13.0
# AUTHOR:         Nicolas Lamirault <nicolas.lamirault@gmail.com>
# DESCRIPTION:    zeiot/rpi-prometheus

FROM resin/armv7hf-debian:stretch
MAINTAINER Nicolas Lamirault <nicolas.lamirault@gmail.com>

ENV PROMETHEUS_OPERATOR_VERSION 0.13.0

ADD prometheus-operator /usr/bin/prometheus-operator

EXPOSE 8080

ENTRYPOINT [ "/usr/bin/prometheus-operator" ]

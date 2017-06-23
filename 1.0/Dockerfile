# VERSION 0.5.0
# AUTHOR:         Nicolas Lamirault <nicolas.lamirault@gmail.com>
# DESCRIPTION:    zeiot/rpi-prometheus

FROM resin/armv7hf-debian:stretch
MAINTAINER Nicolas Lamirault <nicolas.lamirault@gmail.com>

ENV KUBE_STATE_METRICS_VERSION 0.5.0

ADD kube-state-metrics-arm /usr/bin/kube-state-metrics

EXPOSE 8080

ENTRYPOINT [ "/usr/bin/kube-state-metrics" ]

FROM confluentinc/cp-server-connect-operator:6.1.6.0 AS base

USER root

RUN confluent-hub install --no-prompt confluentinc/kafka-connect-gcs-source:2.5.7 \
    && confluent-hub install --no-prompt confluentinc/kafka-connect-gcs:10.1.7

USER user
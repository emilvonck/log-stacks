FROM docker.elastic.co/logstash/logstash-oss:8.4.1

RUN bin/logstash-plugin install logstash-output-loki \
    && bin/logstash-plugin install logstash-filter-json_encode
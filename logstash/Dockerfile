FROM docker.elastic.co/logstash/logstash:6.0.0

# add custom config
COPY logstash.conf /config-dir/logstash.conf

# add templates
COPY ./templates/ /config-dir/templates/

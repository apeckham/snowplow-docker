FROM memrise/snowplow-elasticsearch-sink

ADD elasticsearch-sink.conf /tmp/elasticsearch-sink.conf
RUN sed "s/ELASTICSEARCH_ENDPOINT/$ELASTICSEARCH_ENDPOINT/g" /tmp/elasticsearch-sink.conf >/etc/snowplow/elasticsearch-sink.conf
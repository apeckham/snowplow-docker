FROM memrise/snowplow-elasticsearch-sink

RUN sed "s/ELASTICSEARCH_ENDPOINT/$ELASTICSEARCH_ENDPOINT/g" elasticsearch-sink.conf >/etc/snowplow/elasticsearch-sink.conf
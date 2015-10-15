FROM memrise/snowplow-stream-enrich

ADD http://snowplow-hosted-assets.s3.amazonaws.com/third-party/maxmind/GeoLiteCity.dat /etc/snowplow/
COPY config/ip_lookups.json /etc/snowplow/enrichments/ip_lookups.json
COPY config/enrich.conf /etc/snowplow/enrich.conf
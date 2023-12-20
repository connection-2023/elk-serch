ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELASTIC_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
COPY /lib/postgresql-42.2.27.jre7.jar /usr/share/logstash/logstash-core/lib/jars/postgresql-42.2.27.jre7.jar

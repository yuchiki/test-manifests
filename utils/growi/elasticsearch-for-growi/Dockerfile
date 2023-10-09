ARG version=8.10.2
FROM docker.elastic.co/elasticsearch/elasticsearch:${version}

RUN bin/elasticsearch-plugin install analysis-kuromoji
RUN bin/elasticsearch-plugin install analysis-icu

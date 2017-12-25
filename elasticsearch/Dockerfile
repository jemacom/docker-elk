# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch:5.1.2

COPY config/ config/

# Add your elasticsearch plugins setup here
RUN bin/elasticsearch-plugin install https://raw.githubusercontent.com/elasticfence/elasticsearch-http-user-auth/5.1.2/jar/elasticfence-5.1.2-SNAPSHOT.zip

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:5.1.2

COPY config/ config/
# Add your kibana plugins setup here
RUN kibana-plugin install https://cdn.rawgit.com/jemacom/kibana-auth-elasticfence/5.1.2/releases/kibana-auth-elasticfence-5.1.2.zip?raw=true

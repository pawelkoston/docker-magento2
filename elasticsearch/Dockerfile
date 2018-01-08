FROM bitnami/elasticsearch:2.4.4-r2 

ADD config/elasticsearch.yml /opt/bitnami/elasticsearch/config/elasticsearch.yml

RUN /opt/bitnami/elasticsearch/bin/plugin -Des.path.plugins=/opt/bitnami/elasticsearch/plugins/ install analysis-phonetic
RUN /opt/bitnami/elasticsearch/bin/plugin -Des.path.plugins=/opt/bitnami/elasticsearch/plugins/ install analysis-icu

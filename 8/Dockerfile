FROM bitnami/elasticsearch:8.11.4-debian-11-r1

RUN /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-kuromoji \
	&& /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-icu \
	&& /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-smartcn \
	&& /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-stempel

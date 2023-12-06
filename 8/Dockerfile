FROM bitnami/elasticsearch:8.11.1-debian-11-r0

RUN /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-kuromoji \
	&& /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-icu \
	&& /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-smartcn \
	&& /opt/bitnami/elasticsearch/bin/elasticsearch-plugin install analysis-stempel

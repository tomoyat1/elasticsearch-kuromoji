FROM docker.elastic.co/elasticsearch/elasticsearch:6.8.10
USER root

RUN cd /usr/share/elasticsearch \
	&& bin/elasticsearch-plugin install analysis-kuromoji

USER elasticsearch

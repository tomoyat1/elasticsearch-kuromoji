FROM docker.elastic.co/elasticsearch/elasticsearch:5.6.9
USER root

RUN cd /usr/share/elasticsearch \
	&& bin/elasticsearch-plugin install analysis-kuromoji

USER elasticsearch

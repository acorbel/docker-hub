# meedan/elasticsearch
# elasticsearch 5.2 with elasticsearch-gui plugin

FROM docker.elastic.co/elasticsearch/elasticsearch:5.2.2
# FROM elasticsearch:5.2
MAINTAINER sysops@meedan.com

# https://github.com/jettro/elasticsearch-gui
RUN plugin install jettro/elasticsearch-gui \
		&& plugin install analysis-icu 

FROM elasticsearch:6.5.4

RUN wget -O ik.zip https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v6.5.4/elasticsearch-analysis-ik-6.5.4.zip && \
	unzip ik.zip -d /usr/share/elasticsearch/plugins && \
	rm -f ik.zip


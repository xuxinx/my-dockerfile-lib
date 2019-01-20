FROM elasticsearch:6.5.4

RUN wget -O ik.zip https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v6.5.4/elasticsearch-analysis-ik-6.5.4.zip && \
	mkdir /usr/share/elasticsearch/plugins/ik && \
	unzip ik.zip -d /usr/share/elasticsearch/plugins/ik && \
	rm -f ik.zip


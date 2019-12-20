FROM fluent/fluentd-kubernetes-daemonset:v1-debian-elasticsearch7
RUN gem install fluent-plugin-tail-multiline
ENV FLUENT_ELASTICSEARCH_HOSTS 192.168.0.3:9200,192.168.0.3:9201,192.168.0.3:9202 
COPY fluent.conf /fluentd/etc/


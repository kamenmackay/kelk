FROM logstash:5.6.5
RUN /usr/share/logstash/bin/logstash-plugin update
RUN /usr/share/logstash/bin/logstash-plugin install logstash-filter-prune && /usr/share/logstash/bin/logstash-plugin install logstash-input-dead_letter_queue

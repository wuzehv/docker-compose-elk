FROM logstash:7.9.3

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD ./pipeline/ /usr/share/logstash/pipeline/
ADD ./config/ /usr/share/logstash/config/

RUN curl -L https://cdn.mysql.com/archives/mysql-connector-java-5.1/mysql-connector-java-5.1.48.tar.gz | tar -zx -C /usr/share/logstash/

ENTRYPOINT ["logstash"]
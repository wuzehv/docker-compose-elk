FROM logstash:7.9.3

RUN curl -L https://cdn.mysql.com/archives/mysql-connector-java-5.1/mysql-connector-java-5.1.48.tar.gz | tar -zx -C /usr/share/logstash/

ENTRYPOINT ["logstash"]
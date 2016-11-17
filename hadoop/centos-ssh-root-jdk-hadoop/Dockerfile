FROM jdk7
ADD hadoop-2.6.0.tar.gz  /usr/local
RUN mv /usr/local/hadoop-2.6.0  /usr/local/hadoop
ENV HADOOP_HOME /usr/local/hadoop
ENV PATH $HADOOP_HOME/bin:$PATH

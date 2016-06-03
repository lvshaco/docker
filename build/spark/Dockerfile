FROM lvshaco/ubuntu
ADD ./spark-1.6.1-bin-hadoop2.6.tgz /usr/local
RUN apt-get update \
        && apt-get install -y default-jdk \
        && rm -rf /var/lib/apt/lists/* \
        && cd /usr/local && ln -s spark-1.6.1-bin-hadoop2.6 spark
ENV SPARK_HOME /usr/local/spark
ENV PATH $PATH:$SPARK_HOME/bin

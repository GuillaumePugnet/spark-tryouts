FROM gpugnet/spark-base:latest

COPY submit.sh /

ENV SPARK_MASTER_NAME 127.0.0.1
ENV SPARK_MASTER_PORT 7077
ENV SPARK_SUBMIT_ARGS=""
ENV SPARK_APPLICATION_ARGS ""
#ENV SPARK_APPLICATION_JAR_LOCATION /opt/spark-apps/myjar.jar
#ENV SPARK_APPLICATION_MAIN_CLASS my.main.Application


CMD ["/bin/bash", "/submit.sh"]

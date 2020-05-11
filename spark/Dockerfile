FROM openjdk:8-jre

# Download spark
ADD https://mirrors.tuna.tsinghua.edu.cn/apache/spark/spark-2.4.5/spark-2.4.5-bin-hadoop2.7.tgz /tmp/

# Create /opt directory
RUN mkdir -p /opt/

# Unpack spark into /opt/
RUN tar -xzf /tmp/spark-2.4.5-bin-hadoop2.7.tgz -C /opt/
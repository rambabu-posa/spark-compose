FROM openjdk:7-jre

# Download Hadoop
ADD http://apache.mirrors.tds.net/hadoop/common/hadoop-2.7.7/hadoop-2.7.7.tar.gz /tmp/

# Create /opt directory
RUN mkdir -p /opt/

# Unpack spark into /opt/ and set HADOOP_HOME
RUN tar -xzf /tmp/hadoop-2.7.7.tar.gz -C /opt/


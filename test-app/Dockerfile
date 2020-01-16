FROM openjdk:8-alpine
MAINTAINER Matthew Mattox matthew.mattox@rancher.com

ADD memory_consumer.jar /opt/local/jars/memory_consumer.jar
CMD java $JVM_OPTS -cp /opt/local/jars/memory_consumer.jar com.banzaicloud.MemoryConsumer

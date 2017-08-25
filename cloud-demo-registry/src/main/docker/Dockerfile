FROM java:8-jre
MAINTAINER Mradul Pandey <pandeymradul@gmail.com>

ADD ./cloud-demo-registry.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/cloud-demo-registry.jar"]

EXPOSE 8761
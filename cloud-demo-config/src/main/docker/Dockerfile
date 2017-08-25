FROM java:8-jre
MAINTAINER Mradul Pandey <pandeymradul@gmail.com>
LABEL git_commit_id="${git.commit.id.abbrev}"
ADD ./cloud-demo-config.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/cloud-demo-config.jar"]

EXPOSE 8888
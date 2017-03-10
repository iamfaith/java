#
# Oracle Java 8 Dockerfile
#
# https://github.com/dockerfile/java
# https://github.com/dockerfile/java/tree/master/oracle-java8
#

# Pull base image.
FROM daocloud.io/iamfaith/java8

# Install Java.
RUN \
  apt-get update && \
  apt-get install -y freetype* && \
  rm -rf /var/lib/apt/lists/* && \


# Define default command.
CMD ["bash"]

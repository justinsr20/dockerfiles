FROM jenkins:1.651.3
LABEL maintainer="CMI Industries"

COPY plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/plugins.sh /usr/share/jenkins/plugins.txt

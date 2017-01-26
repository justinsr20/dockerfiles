FROM jenkins:1.651.3
LABEL maintainer="CMI Industries"

RUN /usr/local/bin/install-plugins.sh job-dsl workflow-aggregator github


# This method currently does not install dependencies for plugins
#COPY plugins.txt /usr/share/jenkins/plugins.txt
#RUN /usr/local/bin/plugins.sh /usr/share/jenkins/plugins.txt

# command to run to build image
# docker build -t judd/jenkins .
FROM jenkins/jenkins:latest

COPY plugins /tmp/

RUN xargs /usr/local/bin/install-plugins.sh < /tmp/plugins

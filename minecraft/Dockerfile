# ##
# Docker: Minecraft
#
# Builds a docker image for running a vanilla Minecraft server on PufferPanel.
#
# Author: Dane Everitt
# ##

FROM        java:openjdk-8

MAINTAINER  Dane Everitt <dane@daneeveritt.com>

RUN         useradd -m -d /home/container container

USER        container
ENV         HOME /home/container

EXPOSE      25565

WORKDIR     /home/container

CMD         ["/bin/bash"]

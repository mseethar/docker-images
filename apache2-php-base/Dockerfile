FROM mseethar/apache2-base:0.1
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get -q -y install php
RUN /usr/sbin/apachectl start
RUN /usr/sbin/apachectl stop

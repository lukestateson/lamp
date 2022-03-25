FROM httpd:2.4.38

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update
#RUN apt-get -y --no-install-recommends install openssl

COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf
COPY ./httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf

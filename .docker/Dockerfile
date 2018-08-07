FROM centos:6.10

ENV APP_DIR /var/www/html

RUN yum install -y httpd
RUN yum install -y httpd-devel
RUN yum install -y gcc

WORKDIR ${APP_DIR}

EXPOSE 80
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]

FROM ubi8/ubi:8.3

MAINTAINER Your Name ciro.galvao@outlook.com

LABEL description="A custom Apache container based on UBI 8"

RUN yum install -y httpd && \
    yum clean all

RUN echo "Hello from RM340983" > /var/www/html/index.html

EXPOSE 80

CMD ["httpd", "-D", "FOREGROUND"]

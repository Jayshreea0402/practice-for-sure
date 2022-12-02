FROM centos:latest
MAINTAINER jayshreea0402@gmail.com
RUN yum install -y httpd \
zip\
unzip
ADD https://github.com/kyokidG/html-templates.git /var/www/html/
WORKDIR /var/www/html
RUN cd html-templates/045-Soft-Tech-landing
RUN cp -rvf 045-Soft-Tech-landing/* .
CMD ["/usr/sbin/httpd", ".D", "FOREGROUND"]
EXPOSE 80
~              

FROM tomcat:7-jre8

MAINTAINER Hugo Gonzalez <hgonzalez@railtronix.com>

ADD settings.xml /usr/local/tomcat/conf/

ADD tomcat-users.xml /opt/tomcat/conf/

ADD BaillysTransportServices.war /usr/local/tomcat/webapps/


EXPOSE 8080

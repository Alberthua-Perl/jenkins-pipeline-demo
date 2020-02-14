# Created on 2020-02-14 by Longfei Hua

FROM harbor.domain12.example.com:8880/library/tomcat:v1.0.0
MAINTAINER lhua@redhat.com

RUN rm -rf /usr/local/tomcat/webapps/* && \
	mkdir /usr/local/tomcat/webapps/simpleServer
ADD index.jsp /usr/local/tomcat/webapps/simpleServer

EXPOSE 8080

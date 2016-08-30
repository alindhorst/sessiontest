FROM tomcat:8-jre8

ENV CATALINA_HOME /usr/local/tomcat
WORKDIR $CATALINA_HOME
ADD usr/local/tomcat /usr/local/tomcat

EXPOSE 8080
CMD CATALINA_OPTS="$CATALINA_OPTS -DjvmRoute=$HOSTNAME" catalina.sh run


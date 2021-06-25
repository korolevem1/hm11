FROM tomcat:8.5.43-jdk8

#ADD /var/lib/jenkins/dockerfiles/web/tomcat-users.xml /usr/local/tomcat/conf/
#ADD /var/lib/jenkins/dockerfiles/web/context.xml /usr/local/tomcat/webapps/manager/META-INF/context.xml
COPY mywebapplication.war /usr/local/tomcat/webapps/mywebapplication.war

EXPOSE 8080


CMD /usr/local/tomcat/bin/catalina.sh run
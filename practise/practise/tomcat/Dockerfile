#deploying remote tomcat sample application
FROM tomcat
ENV appDir /usr/local/tomcat/webapps
WORKDIR ${appDir}
ADD https://tomcat.apache.org/tomcat-6.0-doc/appdev/sample/sample.war $appDir/sample.war

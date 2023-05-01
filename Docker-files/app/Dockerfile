FROM_tomcat:8-jre11
LABEL "Project"="Vprofile"
LABEL "author"="Imran"

RUN rm -rf /usr/local/tomcat/webapps/*
copy target/vprofile-v2.war    /usr/local/tomcat/webapps/root.war


EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps/
# getting base image 
FROM tomcat:8-jre11
# setting some labels 
LABEL Project="vprofile"
LABEL Author="Mohamed Mohsen"
# removing default app 
RUN rm -rf /usr/local/tomcat/webapps/*
# copy the artifact 
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
# expose port 8080
EXPOSE 8080
# running catalina script to run tomcat process
CMD ["catalina.sh", "run"] 
# setting the work directory
WORKDIR /usr/local/tomcat/webapps/
# presist data
VOLUME /usr/local/tomcat/webapps
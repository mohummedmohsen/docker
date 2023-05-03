# getting base image 
FROM nginx
# setting some labels 
LABEL Project="vprofile"
LABEL Author="Mohamed Mohsen"
# removing default app
RUN rm -rf /etc/nginx/conf.d/default.conf
# copy the nginx.conf file 
COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf
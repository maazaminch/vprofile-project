FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Maaz"

#remove the default config file
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf


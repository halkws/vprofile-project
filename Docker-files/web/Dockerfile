FROM nginx 
LABEL "Project"="Vprofile"
LABEL "Author"="Kostas"

RUN em -rf /etc/nginx/conf.d/default.conf

COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf 
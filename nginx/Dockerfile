FROM nginx
LABEL "Author"="AVL"
LABEL "Project"="VProfile"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY app.conf /etc/nginx/conf.d/vproapp.conf

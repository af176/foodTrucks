FROM nginx:stable-alpine
RUN rm /etc/nginx/conf.d/default.conf
COPY /flask-app/static/ /usr/share/nginx/html/ 
COPY /flask-app/templates/ /usr/share/nginx/html/ 
COPY nginx.conf /etc/nginx/nginx.conf
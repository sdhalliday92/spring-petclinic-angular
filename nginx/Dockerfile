FROM nginx:latest

WORKDIR /etc/nginx/

RUN rm sites-available/default.conf
RUN sudo cp -R ~/dist/* /usr/share/nginx/html/petclinic
COPY ./default.conf sites-available/
# RUN /etc/init.d/nginx reload
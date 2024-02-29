FROM nginx:latest

RUN apt-get update && apt-get install -y git

RUN git clone https://github.com/ColoCepeda/tup-lc2-votacion-app.git

RUN mv tup-lc2-votacion-app/* /usr/share/nginx/html

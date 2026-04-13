FROM nginx:latest

# Update the package list and install net-tools in one layer
RUN apt-get update && apt-get install -y net-tools

COPY ./index.html /usr/share/nginx/html/index.html
EXPOSE 80

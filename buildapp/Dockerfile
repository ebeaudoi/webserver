FROM devt-lx-quay.devtest.local:8443/ocp4/nginx:latest

COPY ./index.html /usr/share/nginx/html/index.html

 EXPOSE 8080
 
 CMD ["nginx", "-g", "daemon off;"]

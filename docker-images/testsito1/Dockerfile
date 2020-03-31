FROM nginx:latest
ADD https://raw.githubusercontent.com/noriukyaga/k8s/master/docker-images/testsito1/index.html /usr/share/nginx/html/
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]

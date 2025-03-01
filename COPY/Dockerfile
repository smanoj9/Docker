FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /user/share/nginx/html/index.html
COPY index.html /user/share/nginx/html/index.html
CMD ["nginx", "-g","daemon off;"]
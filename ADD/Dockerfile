FROM almalinux:9
RUN dnf install nginx -y
ADD https://raw.githubusercontent.com/KattaHarshavardhanReddy/exprep/refs/heads/main/be.service /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
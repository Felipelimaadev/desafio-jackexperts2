# Use uma imagem base do Nginx
FROM nginx:alpine

# Copie o arquivo HTML para o diretório de conteúdo do Nginx
COPY index.html /usr/share/nginx/html/index.html

# Exponha a porta que o Nginx vai usar
EXPOSE 80
FROM nginx:alpine
COPY ./index.html /usr/share/nginx/html/index.html


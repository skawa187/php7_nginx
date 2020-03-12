FROM nginx:latest

ARG html_dir
COPY nginx.conf /etc/nginx/nginx.conf
RUN sed -i "s~HTML_DIR~${html_dir}~g" /etc/nginx/nginx.conf
EXPOSE 80
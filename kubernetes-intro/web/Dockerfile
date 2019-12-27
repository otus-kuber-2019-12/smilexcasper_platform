FROM nginx:latest
RUN mkdir /app
WORKDIR /app
COPY homework.html /app
EXPOSE 8000
COPY nginx.conf /etc/nginx/nginx.conf
RUN useradd -u 1001 user && chown -R user:user /app/ && chmod -R 0777 /app/

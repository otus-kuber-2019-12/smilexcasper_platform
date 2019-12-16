FROM nginx:latest

EXPOSE 8000

WORKDIR /app

RUN useradd -u 1001 user && chown -R user:user /app/

COPY nginx.conf /etc/nginx/nginx.conf

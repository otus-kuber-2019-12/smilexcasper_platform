FROM nginx:latest
RUN mkdir /app
WORKDIR /app
COPY homework.html /app
EXPOSE 8000
RUN useradd -u 1001 user && chown -R user:user /app/
COPY nginx.conf /etc/nginx/nginx.conf


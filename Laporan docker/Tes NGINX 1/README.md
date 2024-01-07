docker build -t nginx-1:v1 .
docker run -d -p 80:80 nginx-1:v1
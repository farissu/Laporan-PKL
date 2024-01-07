docker build -t nginx-2:v1 .
docker run -d -p 70:80 nginx-2:v1
[Tạo Docker Image]
docker build -t huu1995edu/coreapi .
[Run Docker Image với Docker Container]
docker run -p 8080:80 huu1995edu/coreapi
[List docker image]
docker ps
[Stop iamge]
docker stop [iddocker]
[Push/Pull docker]
docker [push/pull] huu1995edu/coreapi
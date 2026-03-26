# chay dockerfile:
# build image
docker build -t phamducthanh/duanjava:latest .
# push len Docker Hub (dang nhap docker hub ```docker login``` truoc)
docker push phamducthanh/duanjava:latest
# chay
docker run -d -p 8080:8080 phamducthanh/duanjava:latest
# dung
docker stop <id>
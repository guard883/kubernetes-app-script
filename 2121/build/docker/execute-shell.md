# jar 파일 복사
cp /var/lib/jenkins/workspace/2121-source-build/build/libs/app.jar ./2121/build/docker/app.jar

# 도커 빌드
docker build -t academyitwill/app ./2121/build/docker
docker push academyitwill/app
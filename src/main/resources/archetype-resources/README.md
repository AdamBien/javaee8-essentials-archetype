# Build
mvn clean package && docker build -t ${groupId}/${artifactId} .

# RUN

docker rm -f ${artifactId} || true && docker run -d -p 8080:8080 -p 4848:4848 --name ${artifactId} ${groupId}/${artifactId} 
# Docker build command
docker build -t saurabhdev01/emp-service:latest .
# Docker Push
docker push saurabhdev01/emp-service:latest
# Docker Pull
docker pull saurabhdev01/emp-service:latest
# Docker run
docker run -d -p 8081:8081 saurabhdev01/emp-service:latest
# Map Volume
docker run -d -v /var/log/app:/var/log/Application/
# http://localhost:8081/springbootapp/employees

#Non Docker
pull the code
cd spring-boot
mvn clean install
cd /target/
java -jar nameof_checkfor.war
http://localhost:8081/springbootapp/employees

# cloud-demo

Run and up services:
> mvn clean package -DskipTests -Pproduction
> mvn initialize docker:build -Pproduction
> cat .env
> docker-compose -f docker-compose.yml up -d  --build

To reproduce error run following curl command:
 
curl-X POST http://user:password@localhost:8888/monitor?path=application


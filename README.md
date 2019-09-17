# location-engine-api-gateway
The api gateway of location engine for routing, securing and authenticated other service. It is an eureka client of the eureka server.

## Available scripts

### run
`mvn spring-boot:run`

### package
`mvn clean`

`mvn package`

## deployment

package -> upload jar file -> run command

example run jar command

```nohup java -jar api-gateway-0.0.1-SNAPSHOT.jar > /home/robert/logs/apigateway.log &```

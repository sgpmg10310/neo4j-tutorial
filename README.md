# neo4j-tutorial
neo4j tutorial 

사전에 neo4j database 를 다운 받고, 스프링부트를 연결하는 작업 후에 아래와 같이 http://localhost:7474 에 접속한다.


application.properties 에 다음과 같이 설정한다.
```
spring.neo4j.uri=bolt://localhost:7687
spring.neo4j.authentication.username=neo4j
spring.neo4j.authentication.password=패스워드


logging.level.org.neo4j.driver.internal=DEBUG
logging.level.org.neo4j.driver=DEBUG
```

<img width="1310" height="585" alt="image" src="https://github.com/user-attachments/assets/8a2392b7-b48e-42f7-9acf-5993d0b066c3" />



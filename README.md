# stomp-simple-broker
A simple stomp message broker sample.

It uses Spring Framework's [simple messaging broker](http://docs.spring.io/spring-framework/docs/4.3.0.BUILD-SNAPSHOT/javadoc-api/org/springframework/messaging/simp/config/MessageBrokerRegistry.html#enableSimpleBroker-java.lang.String...-), which handles pubsub using STOMP messages over WebSocket.

It also provides a webpage to connect/subscribe/publish using [stomp.js](https://github.com/jmesnil/stomp-websocket)

### Compile with:
  `mvn clean install`


### Start broker in command line:
*  `java -jar target/stomp-simple-broker-0.0.1-SNAPSHOT.war`
*  Open multiple browser windows to `http://localhost:8080/index.html`
*  `Connect`, type a message and `Publish`
*  All windows will show the published message

Alternatively, to start broker in tomcat, copy `target/stomp-simple-broker-0.0.1-SNAPSHOT.war` to tomcat webapp directory
  

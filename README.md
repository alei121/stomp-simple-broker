# stomp-simple-broker
A simple stomp message broker sample using Spring Framework

### Compile with:
  `mvn clean install`


### Start broker in command line:
*  `java -jar target/stomp-simple-broker-0.0.1-SNAPSHOT.war`
*  Open multiple browser windows to `http://localhost:8080/index.html`
*  `Connect`, type a message and `Publish`
*  All windows will show the published message

Alternatively, to start broker in tomcat, copy `target/stomp-simple-broker-0.0.1-SNAPSHOT.war` to tomcat webapp directory
  
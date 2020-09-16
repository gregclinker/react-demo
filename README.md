# react-demon

React demo that prints the first chapter of Leo Tolstoy's War & Peace as an event stream.


**To Build**
```shell script
mvn clean installl
```

**To run**
```shell script
java -jar target/react-demo-1.0.jar
```

**To get consume the event stream** http://localhost:8080/ws.html

**To delete all events**
```shell script
curl -v -X DELETE -H "content-type: application/json" http://localhost:8080/profiles
```
**To add an event**
```shell script
curl -v -H "content-type: application/json" -d '{"text":"random21"}' http://localhost:8080/profiles
```

# eagle
Real time log processing system based on flink and drools  

build
```
mvn package -Dmaven.test.skip=true
```

eagle-log
```
java -jar eagle-log.jar --dev
```

eagle-api
```
http://localhost:8080/eagle-api/log/rules
```

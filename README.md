## SDF Workshop day 3

https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

```
mvn archetype:generate -DgroupId=sg.edu.nus.iss -DartifactId=sdfworkshop3 -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

```
mvn clean compile
```

```
mvn package
java -cp target/sdfworkshop3-1.0-SNAPSHOT.jar sg.edu.nus.iss.App
```
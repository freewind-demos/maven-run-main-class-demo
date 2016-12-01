Maven Run a Main class Demo
===========================

Run a main class by maven.

```
mvn clean compile
mvn exec:java -Dexec.mainClass="demo.Hello"
```

You will see a "Hello world" in the output.

## Resources

- exec-maven-plugin: <http://www.mojohaus.org/exec-maven-plugin/usage.html>


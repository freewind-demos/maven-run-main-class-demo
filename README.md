Maven Run a Main class Demo
===========================

Run a main class by maven.

```
mvn clean compile exec:java
```

Sometimes you also need to add `-Dexec.cleanupDaemonThreads=false` to fix some thread warnings: <http://stackoverflow.com/questions/29878937>

You will see a "Hello world" in the output.

## Resources

- exec-maven-plugin: <http://www.mojohaus.org/exec-maven-plugin/usage.html>


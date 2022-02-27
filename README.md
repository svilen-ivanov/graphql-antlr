# graphql-antlr

Run:
```shell
./gradlew :app:dependencies --configuration runtimeClasspath
```
The result is:
```

> Task :app:dependencies

------------------------------------------------------------
Project ':app'
------------------------------------------------------------

runtimeClasspath - Runtime classpath of compilation 'main' (target  (jvm)).
+--- org.jetbrains.kotlin:kotlin-bom:1.5.0
|    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.5.0 (c)
|    +--- org.jetbrains.kotlin:kotlin-stdlib:1.5.0 (c)
|    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.5.0 (c)
|    \--- org.jetbrains.kotlin:kotlin-stdlib-common:1.5.0 (c)
+--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.5.0
|    +--- org.jetbrains.kotlin:kotlin-stdlib:1.5.0
|    |    +--- org.jetbrains:annotations:13.0
|    |    \--- org.jetbrains.kotlin:kotlin-stdlib-common:1.5.0
|    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.5.0
|         \--- org.jetbrains.kotlin:kotlin-stdlib:1.5.0 (*)
\--- com.graphql-java:graphql-java:17.3
     +--- org.antlr:antlr4-runtime:4.9.2
     +--- org.slf4j:slf4j-api:1.7.30
     +--- com.google.guava:guava:30.0-jre
     |    +--- com.google.guava:failureaccess:1.0.1
     |    +--- com.google.guava:listenablefuture:9999.0-empty-to-avoid-conflict-with-guava
     |    +--- com.google.code.findbugs:jsr305:3.0.2
     |    +--- org.checkerframework:checker-qual:3.5.0
     |    +--- com.google.errorprone:error_prone_annotations:2.3.4
     |    \--- com.google.j2objc:j2objc-annotations:1.3
     +--- com.graphql-java:java-dataloader:3.1.0
     |    \--- org.slf4j:slf4j-api:1.7.30
     +--- org.reactivestreams:reactive-streams:1.0.2
     \--- org.antlr:antlr4:4.9.2
          +--- org.antlr:antlr4-runtime:4.9.2
          +--- org.antlr:antlr-runtime:3.5.2
          +--- org.antlr:ST4:4.3
          |    \--- org.antlr:antlr-runtime:3.5.2
          +--- org.abego.treelayout:org.abego.treelayout.core:1.0.3
          +--- org.glassfish:javax.json:1.0.4
          \--- com.ibm.icu:icu4j:61.1
```

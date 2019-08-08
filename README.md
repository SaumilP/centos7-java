## Java with CentOS 7

This is docker images of CentOS 7 with different versions of java

Example to test ```java -version```

```bash
docker run -it --rm saumilp/centos7-java java -version
openjdk version "1.8.0_222"
OpenJDK Runtime Environment (build 1.8.0_222-b10)
OpenJDK 64-Bit Server VM (build 25.222-b10, mixed mode)
```

Tags
----
* latest -> Centos7 + OpenJDK JRE8 (Headless)
* openjdk-8-jre-headless

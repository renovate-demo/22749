# gradle hunt test

https://github.com/renovatebot/renovate/pull/22749

```bash
$ gradle build --no-build-cache --debug | grep -Eo "(http|https)://[a-zA-Z0-9./?=_%:-]*" | grep okhttp
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom.
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module.
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/4.6.0/okhttp-4.6.0.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom.
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.pom
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module.
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://repo.maven.apache.org/maven2/com/squareup/okhttp3/okhttp/5.0.0-alpha.11/okhttp-5.0.0-alpha.11.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp/5.0.0-SNAPSHOT/okhttp-5.0.0-20211217.184251-6.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/maven-metadata.xml
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.pom
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.module
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar.
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
https://oss.sonatype.org/content/repositories/snapshots/com/squareup/okhttp3/okhttp-jvm/5.0.0-SNAPSHOT/okhttp-jvm-5.0.0-20211217.184251-3.jar
```

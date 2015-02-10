# Spring Generics (v4.1.4)

[![Tip with Gratipay](https://assets.gratipay.com/gratipay.svg)](https://gratipay.com/UnquietCode) [![Tip with Bitcoin](https://assets.gratipay.com/bitcoin.png)](https://blockchain.info/address/1Ec6mzLpJQvuzXqhxfJz1h9ZwJmoHMW9BX)**Bitcoin**

This library is a procedurally (eg 'shaded') extraction of the generics utilities from the `spring-core` module of
the [Spring Framework](https://github.com/spring-projects/spring-framework) project. Spring has some of the smartest
generics resolution code available, but most developers are reluctant to bring a larger dependency like `spring-core`
into their projects. Additionally, with so many users of Spring there is a higher chance of a problem arising due to
dependency mismatches.

By repackaging select Spring classes, the aforementioned problems are easily avoided. The versioning here reflects
the original Spring release version from where the code was extracted. Package names have been changed to protect
the innocent. There are no transitive dependencies to worry about either.

## Usage
Currently available in the UnquietCode Maven repository. To use, add the following to your build script:

### Maven
```xml
<repository>
  <id>uqc</id>
  <name>UnquietCode Repository</name>
  <url>http://www.unquietcode.com/maven/releases</url>
</repository>

...

<dependency>
  <groupId>com.unquietcode.tools.spring</groupId>
  <artifactId>spring-generics</artifactId>
  <version>4.1.4</version>
</dependency>
```

### Gradle
```groovy
repositories {
  maven {
    url 'http://www.unquietcode.com/maven/releases'
  }
}

...

dependencies {
  compile 'com.unquietcode.tools.spring:spring-generics:4.1.4'
}
```

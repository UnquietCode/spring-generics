# Spring Generics (v4.2.5)  [![Build Status](https://travis-ci.org/UnquietCode/spring-generics.png?branch=master)](https://travis-ci.org/UnquietCode/spring-generics)

[![Tip with Gratipay](https://assets.gratipay.com/gratipay.svg)](https://gratipay.com/UnquietCode) [![Tip with Bitcoin](http://www.unquietcode.com/e_e/bitcoin.png)](https://blockchain.info/address/1Ec6mzLpJQvuzXqhxfJz1h9ZwJmoHMW9BX)**Bitcoin**

This library is a procedural extraction (eg 'shaded jar') comprised of the generics utilities from the `spring-core` module of the [Spring Framework](https://github.com/spring-projects/spring-framework) project. Spring has some of the smartest
generics resolution code available, but most developers are reluctant to bring a larger dependency like `spring-core`
into their projects. Additionally, with so many users of Spring there is a higher chance of a problem arising due to
dependency mismatches.

By repackaging select Spring classes, the aforementioned problems are easily avoided. The versioning here reflects
the original Spring release version from where the code was extracted. Package names have been changed to protect
the innocent. There are no transitive dependencies to worry about either.

## Usage
The dependencies are deployed to Maven Central. To use, add the following to your build script:

### Maven
```xml
<dependency>
  <groupId>com.unquietcode.tools.spring</groupId>
  <artifactId>spring-generics</artifactId>
  <version>4.2.5</version>
</dependency>
```

### Gradle
```groovy
dependencies {
  compile 'com.unquietcode.tools.spring:spring-generics:4.2.5'
}
```

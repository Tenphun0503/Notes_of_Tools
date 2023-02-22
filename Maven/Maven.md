## Maven 
Maven is build atuomation and project management tool for Java applications.

### Structure
1. pom.xml  
Project object model (POM) file defines the project structure, dependencies, and build process.
2. src  
Include `main` and `test`, each of them has `java` for Java source code and `resources` for configuration files.
4. target  
All compiled and packaged files

### pom.xml
```
<project ...>
	<modelVersion>4.0.0</modelVersion>
	<groupId>com.spring.learnjava</groupId>
	<artifactId>demo</artifactId>
	<version>1.0</version>
	<packaging>jar</packaging>
	<properties>
      <java.version>19</java.version>
	</properties>
	<dependencies>
      <dependency>
          <groupId>org.springframework.boot</groupId>
          <artifactId>spring-boot-starter-web</artifactId>
          <version>1.2</version>
      </dependency>
	</dependencies>
</project>
```
Above is a sample of pom.xml. It has a lot of labels. Among them:
- `groupId`: like package of Java, usually the name of company or the group.
- `artifactId`: like class name of Java, usually the name of the project
- `version`: the version of the project.
- `dependency`: the packages you want to add into classpath.

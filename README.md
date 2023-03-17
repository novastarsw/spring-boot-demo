# Java Spring Framework

## Test project for **java spring boot.**

Spring Boot is an opinionated framework that helps developers build Spring-based applicaton quickly and easily.

### Install maven
    Maven can manage a project's build, reporting and documentation from a central piece of information. <br/>
    From https://maven.apache.org/, we can download Maven.

### Install gradle
    Gradle is a build automation tool often used for JVM languages such as Java, Groovy or Scala.<br>
    From https://gradle.org/releases/, we can download Gradle.

We can check if maven and gradle installed or not using the following command at CMD.
mnv -v


### Create starter project using Spring Boot CLI

#### What is Spring Boot CLI ?

Spring Boot CLI (Command Line Interface) is a Spring Boot software to run and test Spring Boot applications from command prompt.

* Download CLI from https://docs.spring.io/spring-boot/docs/current/reference/html/getting-started.html#getting-started.installing.cli

* Initialize a new project<br/>
    spring init --dependencies=web,data-jpa demo-project
    
* Building project using maven<br/>
    mvn compile

* Building project using gradle<br/>
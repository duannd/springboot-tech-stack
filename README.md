# SpringBoot Technology Stack - Documentation
```
This project to study & make examples about Spring Boot & related Technology.
```

## OS & Software Requirements
- Mac OSX
- JDK 17
- Spring Boot 2.6.3 
- Spring Framework 5.3.15
- Servlet Container
  - Undertow 2.0 (Servlet Version 4.0)

##  4. Getting Started
1. Introducing Spring Boot
    - Spring Boot helps you to create stand-alone, production-grade Spring-based applications that you can run.
      - Most Spring Boot applications need very little Spring configuration.
    - You can use Spring Boot to create Java applications that can be started by using java -jar or more traditional war deployments.
    - Our primary goals are:
      - Provide a radically faster and widely accessible getting-started experience for all Spring development.
      - Be opinionated out of the box but get out of the way quickly as requirements start to diverge from the defaults.
      - Provide a range of non-functional features that are common to large classes of projects (such as embedded servers, security, metrics, health checks, and externalized configuration).
      - Absolutely no code generation and no requirement for XML configuration.

2. Creating an Executable Jar
   - mvn package 
   - jar tvf target/myproject-0.0.1-SNAPSHOT.jar # to peek inside.
   - java -jar target/myproject-0.0.1-SNAPSHOT.jar

3. Installing the Spring Boot CLI
   - Download spring-boot-cli-x.x.x-bin.zip & unzip
   - Add SPRING_HOME env
   - Shell auto-completion scripts are provided for BASH and ZSH. Add symlinks to the appropriate location for your environment.
     - ln -s ./shell-completion/zsh/_spring /usr/local/share/zsh/site-functions/_spring
   - Checking Your Installation
     - spring --version

## Core Features
- [SpringBoot Application](./springboot/README.md) 
   



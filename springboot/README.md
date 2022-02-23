# Spring Boot - Core Features

## SpringApplication
- The SpringApplication class provides a convenient way to bootstrap a Spring application that is started from a main() method.

1. Startup Failure
   - If your application fails to start, registered FailureAnalyzers get a chance to provide a dedicated error message and a concrete action to fix the problem.

2. Lazy Initialization
    - SpringApplication allows an application to be initialized lazily. 
    - When lazy initialization is enabled, beans are created as they are needed rather than during application startup.

3. Customizing the Banner

4. Customizing SpringApplication

5. Fluent Builder API
   - If you need to build an ApplicationContext hierarchy (multiple contexts with a parent/child relationship) or if you prefer using a “fluent” builder API, you can use the SpringApplicationBuilder.
```
    There are some restrictions when creating an ApplicationContext hierarchy. 
    For example, Web components must be contained within the child context, 
        and the same Environment is used for both parent and child contexts.
```


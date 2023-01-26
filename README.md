# React + Spring + GraalVM Native Example Project

This is an example project where you can apply graalvm's native build to a project made with spring and react.

# Environment
- Spring Boot 3.0.2
- React 18.2.0
- GraalVM 22.3.r17-grl

# Install
1. ./gradlew nativeCompile
2. ./build/native/nativeCompile/devops 

```agsl

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v3.0.2)

2023-01-26T21:33:21.035+09:00  INFO 62405 --- [           main] i.i.d.installer.InstallerApplication     : Starting AOT-processed InstallerApplication using Java 17.0.5 with PID 62405 (/Users/nohsunghyun/Documents/imqa/workspace/installer/build/native/nativeCompile/devops started by nohsunghyun in /Users/nohsunghyun/Documents/imqa/workspace/installer)
2023-01-26T21:33:21.035+09:00  INFO 62405 --- [           main] i.i.d.installer.InstallerApplication     : No active profile set, falling back to 1 default profile: "default"
2023-01-26T21:33:21.059+09:00  INFO 62405 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-01-26T21:33:21.060+09:00  INFO 62405 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-01-26T21:33:21.060+09:00  INFO 62405 --- [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.5]
2023-01-26T21:33:21.073+09:00  INFO 62405 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-01-26T21:33:21.073+09:00  INFO 62405 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 37 ms
2023-01-26T21:33:21.097+09:00  INFO 62405 --- [           main] o.s.b.a.w.s.WelcomePageHandlerMapping    : Adding welcome page: class path resource [static/index.html]
2023-01-26T21:33:21.106+09:00  INFO 62405 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-01-26T21:33:21.107+09:00  INFO 62405 --- [           main] i.i.d.installer.InstallerApplication     : Started InstallerApplication in 0.087 seconds (process running for 0.099)
2023-01-26T21:34:07.418+09:00  INFO 62405 --- [nio-8080-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring DispatcherServlet 'dispatcherServlet'
2023-01-26T21:34:07.419+09:00  INFO 62405 --- [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Initializing Servlet 'dispatcherServlet'
2023-01-26T21:34:07.419+09:00  INFO 62405 --- [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Completed initialization in 0 ms
```

# Reference
- [devload Spring+React 프로젝트에 GraalVM Native 를 붙이면?](https://medium.com/@sunghyunroh/spring-react-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%97%90-graalvm-native-%EB%A5%BC-%EB%B6%99%EC%9D%B4%EB%A9%B4-fe9b8682209c?source=social.fb)

- [Velog u-nij Spring-Boot-React.js-개발환경-세팅](https://velog.io/@u-nij/Spring-Boot-React.js-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD-%EC%84%B8%ED%8C%85) 
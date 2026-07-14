
# Demo Java WAR Project

This is a simple Maven-based Java web application packaged as a WAR.

## Structure
- pom.xml: Maven configuration with WAR packaging
- src/main/java/com/example/HelloServlet.java: Sample servlet
- src/main/webapp/index.jsp: Home page
- src/main/webapp/WEB-INF/web.xml: Web application descriptor

## Build
Run the following command:

```bash
mvn package
```

The generated WAR file will be available in the target folder.

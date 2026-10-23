# qa-function-java

Example repository for publishing an HTTP function: Java, with Google's Functions
Framework, built with Google's buildpacks.

- The function to run is `functions.HelloHttp`, the class's full name, named in `pom.xml` (`<functionTarget>`), so it is proposed when the repository is imported.
- It answers every request with a fixed text, so a 200 shows it is up.

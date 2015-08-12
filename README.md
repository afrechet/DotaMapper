# DotaMapper

## Setting Up Development

### On Windows (yeah I'm sorry ...)

To develop this project with Eclipse, do the following:

1. [Install Java SE 1.8](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
2. [Install Eclipse](https://eclipse.org/).
3. [Install Gradle plugin for Eclipse](https://marketplace.eclipse.org/content/gradle-integration-eclipse-0).
4. [Install Lombok for Eclipse](https://projectlombok.org/download.html).
5. Clone this git repository.
6. In Eclipse, do `File > New > Other > Gradle Project` and import the project you just cloned.
7. Right-click on the project, and do `Gradle > Refresh All` to refresh dependencies. _This will download the project's dependencies from Maven Central and install them locally._

You are pretty much good to go.

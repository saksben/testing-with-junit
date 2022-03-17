# Testing with JUnit
This is the example codebase for the Pluralsight course: Java SE 17 Unit Testing With JUnit.  It is a medication prescription writing domain example.

## Prerequisites / Requirements

  * Java 17 or higher is required to compile and build the application.
      *  [Adopt Open JDK] (https://openjdk.java.net/projects/jdk/17/)
      *  [Oracle JDK] (https://www.oracle.com/java/technologies/java-se-glance.html)
  * [Maven 3.5+]( https://maven.apache.org/install.html) is also required.
  * And git, of course

The example project uses JUnit 5, but this is declared as a maven project dependency, so does not need to be downloaded separately.

It is recommended to use an IDE like IntelliJ or Eclipse if following along with the course on your own box.

## Running Tests

`mvn clean test` 

from the project root directory should compile the application and run all unit tests.


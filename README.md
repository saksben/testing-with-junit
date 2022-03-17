# Testing with JUnit
This is the example codebase for the Pluralsight course: Java SE 17 Unit Testing With JUnit.  It is a medication prescription writing domain example.

## Prerequisites / Requirements

  * Java 17 or higher is required to compile and build the application.
      *  [Adopt Open JDK] (https://openjdk.java.net/projects/jdk/17/)
      *  [Oracle JDK] (https://www.oracle.com/java/technologies/java-se-glance.html)
  * [Maven 3.5+]( https://maven.apache.org/install.html) is also required.
  * And git, of course

The example project uses JUnit 5, but this is declared as a maven project dependency, so does not need to be downloaded separately.

## Running ERServer

You will need to use Maven at the command line or from your IDE to compile ERServer.  Once built, there is a Java main program that can be run.

### Build ERServer

`mvn clean install` should compile and build ERServer.

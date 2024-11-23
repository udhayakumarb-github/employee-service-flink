# employee-service-flink
Employee details storage application using Apache Flink and Mongo DB

# MyMavenProject

This project is a simple Maven project created to demonstrate the steps to set up and build a Maven project from scratch.

## Prerequisites

Make sure you have the following installed on your system:

- Java Development Kit (JDK)
- Apache Maven

## Steps to Create a Maven Project

1. **Install Maven**:
   - Download and install Maven from the [official website](https://maven.apache.org/download.cgi).
   - Set up the `M2_HOME` environment variable to point to your Maven installation directory.
   - Add `M2_HOME/bin` to your system's `PATH` variable.

2. **Set Up Your Project Directory**:
   - Create a new directory for your project:
     ```bash
     mkdir MyMavenProject
     ```
   - Navigate to your project directory:
     ```bash
     cd MyMavenProject
     ```

3. **Generate a New Maven Project**:
   - Open a command prompt or terminal window in your project directory.
   - Use the following Maven command to generate a new project:
     ```bash
     mvn archetype:generate -DgroupId=com.example -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
     ```
   - This command creates a simple Maven project with the specified `groupId` (`com.example`) and `artifactId` (`my-app`).

4. **Explore the Project Structure**:
   - After the project is generated, you will see a standard Maven project structure:
     ```
     my-app
     ├── pom.xml
     └── src
         ├── main
         │   └── java
         │       └── com
         │           └── example
         │               └── App.java
         └── test
             └── java
                 └── com
                     └── example
                         └── AppTest.java
     ```

5. **Build the Project**:
   - Navigate to your project directory:
     ```bash
     cd my-app
     ```
   - Run the Maven build command:
     ```bash
     mvn clean install
     ```
   - This command compiles your code, runs tests, and packages your application into a JAR file.

6. **Run Your Application**:
   - To run the generated application, use the following command:
     ```bash
     java -cp target/my-app-1.0-SNAPSHOT.jar com.example.App
     ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

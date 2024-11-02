
## Initializing Spring project

This project is built using IntelliJ Community Edition. The Ultimate Edition of IntelliJ offers built-in support for initializing Spring projects directly when creating a new project. However, since we are using the Community Edition, we will use an online tool to create the project and then import it into our IntelliJ Community Edition.

[Spring project initializtion website](https://start.spring.io/)

## Spring Intializr

<a><img alt="springIntialProject" width="1000" src="https://raw.githubusercontent.com/alex-jeffrin/spring-boot-beginner/main/src/images/springInitializrUI.jpg"/></a>

## Explore

By clicking on the "Explore" option, you can view the pom.xml file, where all dependencies and project metadata are stored, as shown in the image below.

<a><img  alt="springIntialProject" width="1000" src="https://raw.githubusercontent.com/alex-jeffrin/spring-boot-beginner/main/src/images/projectPOMPreview.jpg"/></a>


## Project Structure

<a><img align="left" alt="springIntialProject" width="300" src="https://raw.githubusercontent.com/alex-jeffrin/spring-boot-beginner/main/src/images/projectStructure.jpg"/></a>

It will create a default project structure that is ready to use, so you can start implementing your code changes right away without any additional setup.

<div style="clear: left;"></div>

## Dependencies

You can check and add dependencies as well. by clicking on the **Add dependencies** dependencies refer to libraries, frameworks, or modules that you add to your Spring project to provide specific functionality. When you select dependencies on Spring Initializr, it includes the necessary code and configuration to support features like data access, security, messaging, or web development in your project.

For example:

Spring Web: Adds libraries to create RESTful web services and web applications.
Spring Data JPA: Adds support for working with relational databases using JPA.
Spring Security: Adds authentication and authorization features.
Thymeleaf: Adds support for server-side rendering of HTML pages.
The selected dependencies are included in the generated pom.xml (for Maven) or build.gradle (for Gradle) file. When you build the project, these dependencies are automatically downloaded and configured, making it easier to start developing with the specific features you need.

<a><img align="left" alt="springIntialProject" width="1000" src="https://raw.githubusercontent.com/alex-jeffrin/spring-boot-beginner/main/src/images/dependencies.jpg"/></a>

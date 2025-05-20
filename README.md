# *📘 Project Description*

MyApp is a basic Java application developed using Apache Maven and integrated with Jenkins for continuous integration (CI). The project demonstrates how to automate builds, run unit tests, and streamline the development workflow using Jenkins pipelines.

📁 Project Structure
maven-project
├── pom.xml
└── src
    ├── main
    │   └── com
    │       └── fortune
    │           └── myapp
    │               └── App.java
    └── test
        └── com
            └── fortune
                └── myapp
                    └── AppTest.java


This serves as a clean, modular starter template for Maven-based Java applications with CI/CD support.

🧰 Features
Java application (App.java) with a corresponding test class (AppTest.java)

Project managed using Maven (clean project structure and lifecycle commands)

Continuous Integration using Jenkins:

Automatically triggers on Git commits

Runs Maven build and test phases

Provides test results and build logs

Notifies on build status (optional with plugins)

Suitable foundation for adding deployment stages in CI/CD


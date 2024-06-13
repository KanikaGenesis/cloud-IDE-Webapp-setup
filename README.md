# Cloud IDE and Web App Setup

This repository contains the documentation for setting up a cloud-based IDE and Java web application using AWS services like IAM, Cloud9, and Maven. This project ensures a secure and efficient development environment.

## Setup Guide

1. **Create an IAM User**
   - Go to the IAM console, add a user with "Programmatic access," and attach the "AdministratorAccess" policy.

2. **Launch a Cloud9 IDE**
   - Go to the Cloud9 console, create a new environment, configure the settings, and launch it.

3. **Install Maven and Java**
   - Open the Cloud9 terminal and run:
     ```sh
     sudo yum install -y apache-maven
     sudo yum install -y java-1.8.0-amazon-corretto-devel
     ```

4. **Create the Application**
   - Run the command to generate a Java web app:
     ```sh
     mvn archetype:generate
     ```
   - Customize `index.jsp` as needed.

## Key Learnings

- Using IAM users enhances security and access control.
- AWS Cloud9 provides a convenient, cloud-based development environment.
- Maven automates build processes and manages dependencies effectively.
- Java is a versatile language for building web applications.

## Next Step

In the next project of this DevOps series, I will use AWS CodeCommit to set up a repository for my web app’s code, enabling version control and collaborative development.

## Author

Kanika Mathur  
[GitHub](https://github.com/KanikaGenesis) | [LinkedIn](https://www.linkedin.com/in/kanika-mathur-083080121/)

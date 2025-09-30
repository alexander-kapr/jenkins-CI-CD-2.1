# Jenkins Pipeline for Maven Java Application

This repository includes a Jenkins pipeline configuration for automating the build and testing process of a Java application using Maven.

## Pipeline Overview

* **Environment Variable**:
  `APP_PORT=9090` is set to run the application on port 9090.

* **Stages**:

  1. **Build** – Packages the application with Maven while skipping tests.
  2. **Unit Test** – Executes all unit tests with Maven.

## Result

When the pipeline job runs in Jenkins, the application is successfully built, unit tests are executed, and the process completes with a successful pipeline run.

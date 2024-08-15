# REST-assured API Testing Project

## Overview

This project uses REST-assured to test APIs. REST-assured is a Java library that simplifies the process of testing REST services. It provides a domain-specific language (DSL) for writing tests that are readable and maintainable.

## Prerequisites

- **Java 8 or higher**: Ensure that you have Java installed on your system.
- **Maven**: The project uses Maven for dependency management. Install Maven if you haven't already.

## Getting Started

### Clone the Repository

First, clone this repository to your local machine:

```bash
git clone git@github.com:a-arias/Swagger-Pet-store-api-test.git
cd Swagger-Pet-store-api-test
```

### Set Up the Project
Import the Project: Open the project in your favorite IDE (e.g., IntelliJ IDEA, Eclipse).
Build the Project: Use Maven to install the required dependencies and build the project:

```bash
mvn clean install
```

### Configuration

Before running the tests, configure the necessary settings:

API Base URL: Update the base URL of the API in the configuration file or environment variables.
Running the Tests

To run the tests, use the following Maven command:
```bash
mvn test
```

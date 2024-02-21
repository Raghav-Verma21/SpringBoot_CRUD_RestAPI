# Spring Boot CRUD Project with REST Principles

This Spring Boot project demonstrates basic CRUD (Create, Read, Update, Delete) operations using RESTful principles. It is built with Gradle for easy dependency management and build automation.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Build](#build)
- [Contributing](#contributing)


## Prerequisites

Make sure you have the following installed on your machine:

- Java JDK (version 8 or higher)
- Gradle
- SpringBoot

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/Raghav-Verma21/SpringBoot_CRUD_RestAPI
    ```

2. Build the project:

    ```bash
    gradle build
    ```

## Usage

1. Run the test:

    ```bash
   gradlew test
    ```

## Endpoints

- **GET /api/items**: Retrieve all items.
- **GET /api/items/{id}**: Retrieve a specific item by ID.
- **POST /api/items**: Create a new item.
- **DELETE /api/items/{id}**: Delete an item by ID.

Make sure to replace `{id}` with the actual item ID when using the respective endpoints.

## Build

Build the project using Gradle:

```bash
gradle build
```

## Contribution

Contributions are welcome! Please fork this repository and create a pull request with your changes.


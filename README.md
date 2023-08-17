# Schoolar

Welcome to the schoolar repository! This project is structured with two submodules, each serving a distinct purpose. To clone and set up the project effectively, follow the instructions below.

## Cloning the Repository

To clone the repository and initialize the submodules, use the following command:

```sh
git clone --recursive https://github.com/wilfriedago/schoolar.git
```

## Submodule 1: Next.js Frontend (apps/web)

This submodule contains a Next.js front-end application.

### Setup

1. Navigate to the `apps/web` directory:
   ```sh
   cd apps/web
   ```

2. Install dependencies using one of the following package managers:

   - With pnpm:
     ```sh
     pnpm install
     ```
   - With yarn:
     ```sh
     yarn install
     ```
   - With npm:
     ```sh
     npm install
     ```

3. Start the development server:
   ```sh
   pnpm dev  # Replace with the appropriate command for your package manager
   ```

The Next.js application should now be running locally.

## Submodule 2: Spring Boot Backend (apps/backend)

This submodule contains a Spring Boot backend application.

### Setup

1. Navigate to the `apps/backend` directory:
   ```sh
   cd apps/backend
   ```

2. Install required tools:
   - Java JDK (version 17 or higher)
   - Maven (for building the project)

3. Build the project:
   ```sh
   mvn clean install
   ```

4. Run the application:
   ```sh
   java -jar target/backend.jar
   ```

The Spring Boot application should now be running and accessible.

## Contribution

If you'd like to contribute to this project, feel free to fork the repository and submit pull requests with your improvements!

We appreciate your interest and hope you enjoy working with our project!

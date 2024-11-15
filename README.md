# Kotlin-Education
Kotlin Education and Testing

### Task:
1. **API Integration**: Integrate with the https://restcountries.com/ API to fetch country data.
2. **Database Setup**: Set up a local PostgresDB instance for data storage.
3. **CRUD Operations**: Create CRUD (Create, Read, Update, Delete) functionalities for the country items in your local database. This includes:
    - Creating endpoints to post new country data to the database.
    - Creating endpoints to receive country data from the database.
    - Creating endpoints to update existing country data in the database.
    - Creating endpoints to delete country data from the database.
4. **Data Migration**: Migrate the fetched country data from https://restcountries.com/ API to your local PostgresDB.
5. **GitHub Repo**: Push your code to a GitHub repository for version control and sharing purposes.
 
### Must Have Technologies:
- **Spring Boot**: Utilize Spring Boot to create the backend service.
- **Kotlin**: Use Kotlin as the programming language.
- **Gradle**: Use Gradle as the build tool to manage dependencies and build configurations.
- **PostgresDB**: Use PostgreSQL as the database for storing the data locally.
 
### Nice to Have Technologies:
- **Docker**: Containerize the application using Docker to ensure the environment consistency and simplify the deployment process. Create a Dockerfile for building the Docker image of your application. Optionally, create a docker-compose.yml file for orchestrating multiple containers if needed (like if adding a separate database container).
- **GitHub Actions** (or other CI/CD tools): Setup Continuous Integration and Continuous Delivery pipeline using GitHub Actions to automate the build, test, and deployment phases.


# ytproject: File Hider Using Java and MySQL

## Description

This project is a personal exploration into creating a file hider application using Java and MySQL. The application includes key security features such as email authentication, login functionality, and file encryption. Through this project, I aimed to enhance my understanding of Java programming, particularly in areas related to security and database management. It also provided an opportunity to implement practical use cases like OTP generation and user management.

The project is designed to be a learning experience, helping to solidify my skills in Java development, while also creating a functional tool that integrates secure data handling with a user-friendly interface.

## Installation

### Prerequisites
- Java 17 (JDK 17)
- Maven
- MySQL (for database interactions)

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ytproject.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ytproject
    ```
3. Build the project using Maven:
    ```bash
    mvn clean install
    ```

## Usage

To run the project, you can use Maven's command:
```bash
mvn exec:java -Dexec.mainClass="Main"
```
Replace `"Main"` with the actual main class if it differs.

## Project Structure

- `.idea/` - IntelliJ IDEA project-specific files.
- `src/` - Contains the source code files:
  - **Main.java** - The main entry point for the application. It initializes the program and handles the main flow.
  - **SendOTPService.java** - Service class responsible for sending One-Time Passwords (OTPs) for email authentication.
  - **GenerateOTP.java** - Utility class for generating OTPs.
  - **UserService.java** - Contains business logic related to user operations, including authentication and user management.
  - **DataDAO.java** - Data Access Object for interacting with the database to handle data-related operations.
  - **UserDAO.java** - Manages user-related database operations.
  - **UserView.java** - Manages the user interface or views related to users.
  - **Welcome.java** - Handles the welcome screen or initial application interactions.
  - **Data.java** - Represents data entities in the application.
  - **User.java** - Represents user entities in the application.

## Key Features

- **File Hiding**: Securely hide files using encryption techniques.
- **Email Authentication**: Use OTPs sent via email for user authentication.
- **Login System**: Secure login functionality with encryption.
- **Database Interaction**: MySQL database integration for storing user information and other data.

## Dependencies

This project uses the following dependencies, which are managed by Maven:

- **MySQL Connector/J**: Version 8.0.28
- **JavaMail API**: Version 1.6.2

These dependencies are defined in the `pom.xml` file and will be automatically downloaded when you build the project.

## Configuration Files

- **`compiler.xml`**: Contains configuration settings for the compiler, including annotation processing.
- **`misc.xml`**: Includes miscellaneous settings, such as project language level (Java 17).
- **`jarRepositories.xml`**: Defines remote repositories for Maven dependencies.
- **`workspace.xml`**: Manages workspace settings, including recent files and tasks.
- **`.gitignore`**: Specifies files and directories that should be ignored by Git, including `.idea/` and `workspace.xml`.

## License

[Include any license information here if applicable.]

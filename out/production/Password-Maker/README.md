# Password Generator and Strength Checker

This project is a **Password Generator** and **Strength Checker** application built in Java. It helps users create secure, customized passwords based on specific character requirements and provides feedback on the strength of generated passwords, making it a valuable tool for enhancing online security.

## Key Features

- **Customizable Password Generation**: Generates passwords with a variety of options, including uppercase letters, lowercase letters, numbers, and symbols.
- **Strength Evaluation**: Assesses password strength based on character diversity and length.
- **User-Friendly Feedback**: Offers clear feedback, ranging from "very good" to "weak," to help users improve password quality.
- **Robust Testing**: Includes JUnit test cases to ensure password generation meets specified criteria and functions as expected.

## Project Structure

### Classes
- **Password**: 
  - Stores password value and length.
  - Evaluates password strength using criteria such as character type variety and length.
  - Provides feedback on password quality with a user-friendly message.

- **Alphabet**: 
  - Configures the character pool for password generation based on selected options (uppercase, lowercase, numbers, symbols).
  - Dynamically builds an alphabet for customized password creation.

- **Generator**: 
  - Manages user interaction for password creation.
  - Utilizes the `Alphabet` and `Password` classes to generate passwords and run the main program loop.

### Unit Testing
- **JUnit 5**:
  - Test cases in `GeneratorTest` verify core functionalities:
    - Correctness of password and alphabet configurations.
    - Validation of password strength evaluation based on alphabet settings.
  - Ensures accuracy and reliability of password generation.

## Technologies Used
- **Java**: Core language for the application.
- **JUnit 5**: Testing framework for unit tests.
- **IntelliJ IDEA**: IDE for development and testing.

## How to Use
1. Run the main application.
2. Specify character requirements (e.g., uppercase, lowercase, numbers, symbols).
3. Generate a password and receive feedback on its strength.

This project is a helpful tool for creating and evaluating strong passwords, promoting better password security practices.

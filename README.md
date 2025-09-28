# JUnit 5 Testing Lab

This project demonstrates JUnit 5 (Jupiter) testing capabilities using Gradle as the build system. It includes a simple Calculator class with comprehensive unit tests showcasing various JUnit 5 features.

## Project Structure

```
src/
├── main/java/com/example/project/
│   └── Calculator.java          # Simple calculator with add method
└── test/java/com/example/project/
    └── CalculatorTests.java     # JUnit 5 test cases
```

## Features Demonstrated

### Calculator Class
- Simple `add(int a, int b)` method for basic arithmetic operations

### Test Cases
- **Basic Test**: Simple assertion test with custom display name
- **Parameterized Test**: CSV-driven test with multiple input combinations
- **JUnit 5 Annotations**: `@Test`, `@DisplayName`, `@ParameterizedTest`, `@CsvSource`
- **Assertions**: `assertEquals` with custom error messages

## Running the Tests

### Using Gradle Wrapper
```bash
# Run all tests
./gradlew test

# Run tests with verbose output
./gradlew test --info

# Clean and run tests
./gradlew clean test
```

### Using IDE
- Import as Gradle project in your preferred IDE
- Run individual test methods or the entire test class
- View test results in the IDE's test runner

## Dependencies

- **JUnit 5 Jupiter**: Core testing framework
- **JUnit Platform Launcher**: Test execution engine
- **Gradle**: Build system with native JUnit 5 support

## Test Output

The tests demonstrate:
- Basic unit testing with assertions
- Parameterized testing with multiple scenarios
- Custom test display names for better readability
- Lambda expressions in assertion messages

## Learning Objectives

This project serves as a practical example of:
- Setting up JUnit 5 with Gradle
- Writing effective unit tests
- Using parameterized tests for multiple scenarios
- Organizing test code with proper naming conventions

## References

- [JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/)
- [Gradle JUnit 5 Support](https://docs.gradle.org/current/userguide/java_testing.html#using_junit5)

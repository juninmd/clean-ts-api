# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the principles and rules for development of AI coding agents within this repository. Adherence to these principles is crucial for maintaining a maintainable, robust, and reliable codebase.

## 1. DRY (Don't Repeat Yourself)

*   All functions, classes, and modules should have a single, well-defined purpose.
*   Avoid duplicating code snippets or logic across different files.
*   Refactor duplicate code into reusable components or functions.
*   Prioritize creating generic solutions over specific implementations.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for simplicity in design and implementation.
*   Use the most straightforward approach to achieve a given task.
*   Avoid unnecessary complexity.
*   Favor clear and understandable code.
*   Keep methods and functions as short and focused as possible.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be extensible without modification.
*   **Liskov Substitution Principle:** Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to implement interfaces they do not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is explicitly required at a given point in time.
*   Defer implementation details until they are actually needed.
*   Avoid adding functionality that is not currently needed.
*   Focus on delivering working code that addresses the immediate requirements.

## 5. Testing & Coverage

*   All code must be thoroughly tested.
*   Implement unit tests for all functions and classes.
*   Aim for at least 80% test coverage.
*   Utilize a testing framework (e.g., `unittest` or similar) to ensure robust testing.
*   Test edge cases and boundary conditions.
*   Automated testing is mandatory for all new code.

## 6. Code Structure & Formatting

*   Follow consistent coding style guidelines (e.g., PEP 8 – unless specifically modified).
*   Use clear and descriptive variable and function names.
*   Indentation consistently throughout the code.
*   Use comments judiciously to explain complex logic.
*   Maintain a consistent directory structure.

## 7. File Limit

*   Each file must have a maximum of 180 lines of code.

## 8.  Agentspecified Rules

*   All development must be productive. No time is allocated to unnecessary delays.
*   Prioritize quality over speed (within reasonable bounds).
*   Code reviews will be conducted regularly.
*   Ensure all changes are documented.

## 9. Dependencies

*   Dependencies are defined and managed via a clear and documented dependency management system.
*   Dependencies are versioned and tracked.
*   Dependency updates should be carefully considered and vetted.
*   Avoid unnecessary dependencies.

## 10.  Error Handling

*   All error handling should be minimal and focused.
*   Return appropriate error codes or messages.
*   Don't expose internal state to user input.

## 11.  Documentation

*   All functions, classes, and modules should have clear and concise documentation.
*   Use docstrings to explain functionality and parameters.
*   Maintain up-to-date documentation.

## 12.  Resource Management

*   Resources (e.g., data, memory) should be managed efficiently.
*   Avoid memory leaks.
*   Properly handle resource cleanup.

## 13.  Security Considerations

*   All code should adhere to established security best practices.
*   Sanitize user input to prevent vulnerabilities.
*   Implement appropriate authentication and authorization mechanisms.

## 14.  Versioning and Deployment

*   Utilize version control (e.g., Git) for all code.
*   Follow a consistent deployment process.
*   Ensure code is versioned and deployable.

These guidelines are intended to provide a foundational framework for development within this AI coding agent repository.  Regular review and refinement are encouraged.
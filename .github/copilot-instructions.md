# Copilot Instructions for vanirxquick

This repository is for the vanirxquick project, a .NET/C# based application.

## Project Context

This is the vanirxquick repository. The project appears to be in its early stages of development.

## Development Environment

- **Language**: C# / .NET
- **IDE**: Visual Studio or Visual Studio Code recommended
- **Version Control**: Git

## Coding Standards

### General Guidelines
- Follow Microsoft's C# coding conventions and style guide
- Use PascalCase for class names, method names, and properties
- Use camelCase for local variables and parameters
- Use meaningful, descriptive names for all identifiers
- Keep methods focused and concise (single responsibility principle)

### Code Quality
- Write clean, maintainable, and self-documenting code
- Add XML documentation comments for public APIs
- Handle errors appropriately with try-catch blocks where needed
- Use async/await for asynchronous operations
- Prefer LINQ for collection operations where it improves readability

### Testing
- Write unit tests for new functionality when appropriate
- Follow Arrange-Act-Assert (AAA) pattern in tests
- Use descriptive test method names that explain what is being tested

## Build and Test Instructions

### Building
```bash
dotnet restore
dotnet build
```

### Running Tests
```bash
dotnet test
```

### Linting
- Follow the code style rules configured in .editorconfig (if present)
- Use Visual Studio's built-in code analysis features

## Git Workflow

- Create feature branches for new work
- Write clear, descriptive commit messages
- Keep commits focused on a single logical change
- Ensure code builds and tests pass before committing

## Additional Guidelines

- Minimize changes when fixing issues - surgical and precise modifications
- Do not remove or modify working code unless absolutely necessary
- Validate that changes don't introduce security vulnerabilities
- Update documentation when making significant changes
- Use existing libraries and packages when possible

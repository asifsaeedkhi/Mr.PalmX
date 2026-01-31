# Contributing to Mr.PalmX

We love your input! We want to make contributing to Mr.PalmX as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## Development Process

We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

## Pull Request Process

1. Update the README.md with details of changes to the interface, if applicable.
2. Update the CHANGELOG.md with a brief description of changes.
3. The PR will be merged once you have the sign-off of two other developers.

## Any Contributions You Make Will Be Under the MIT License

When you submit code changes, your submissions are understood to be under the same [MIT License](LICENSE) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report Bugs Using GitHub's [Issue Tracker](https://github.com/your-username/mr-palmx/issues)

We use GitHub issues to track public bugs. Report a bug by [opening a new issue](https://github.com/your-username/mr-palmx/issues/new); it's that easy!

## Write Bug Reports With Detail, Background, and Sample Code

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can.
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

## Coding Standards

### JavaScript/TypeScript
- Use meaningful variable names
- Follow the existing code style
- Add comments for complex logic
- Write self-documenting code when possible

### React/React Native
- Use functional components with hooks
- Keep components small and focused
- Use PropTypes or TypeScript
- Implement proper error boundaries

### Backend
- Follow RESTful API conventions
- Implement proper error handling
- Add validation for all inputs
- Write comprehensive tests

### Git Commit Messages
- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

## Setting Up Development Environment

1. Fork the repository
2. Clone your fork
3. Install dependencies:
```bash
cd backend && npm install
cd ../mobile && npm install
cd ../admin-panel && npm install

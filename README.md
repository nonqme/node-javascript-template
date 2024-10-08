# Node.js Project Template

## Introduction

This template provides a basic setup for a Node.js project. It includes essential configurations and scripts to help you get started quickly.

## Features

- **Linting and Formatting**: Configured with ESLint and Prettier for code quality and consistency.
- **Pre-commit Hooks**: Uses Husky and lint-staged to run linters on staged files and tests before committing.
- **Automated Dependency Updates**: Dependabot is configured to check for updates to your npm dependencies daily and create pull requests for any updates found.
- **Testing**: Node test runner is configured to run tests.

## Installation

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/nonqme/node-javascript-template.git
   cd node-javascript-template
   ```

2. **Install Dependencies**:

   ```sh
   npm install
   ```

## Usage

- **Linting**: Run ESLint to check for linting errors.

  ```sh
  npm run lint
  ```

- **Formatting**: Run Prettier to format all files.

  ```sh
  npm run format
  ```

- **Run the Project**: Run the project in development mode.

  ```sh
  npm run dev
  ```

- **Testing**: Run tests.

  ```sh
  npm run test
  ```

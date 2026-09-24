# Assignment 2 - Continuous Integration Using GitHub Actions

## Objective

This project demonstrates Continuous Integration using GitHub Actions.

## Technologies Used

- Python 3.12
- pytest
- Git
- GitHub
- GitHub Actions

## Application

The application contains two functions:

- add()
- subtract()

Automated tests are executed using pytest.

## CI Workflow

Whenever code is pushed to the main branch, GitHub Actions:

1. Checks out the repository
2. Sets up Python 3.12
3. Installs dependencies
4. Runs pytest

## Result

The workflow successfully validates the application and detects intentional errors.
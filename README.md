# CI/CD Integration Using GitHub Actions

# Project Overview

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions. The pipeline is designed to automatically execute test cases whenever changes are pushed to the repository, ensuring code quality and reliability throughout the development process.

# Objective

To integrate automated testing into a CI/CD workflow and enable continuous validation of the application through automated test execution and reporting.

# Technologies Used

* GitHub Actions
* Python
* Pytest
* GitHub Repository

# Workflow Description

The CI/CD pipeline performs the following actions:

1. Automatically triggers on every push to the main branch.
2. Checks out the latest source code from the repository.
3. Sets up the Python environment.
4. Installs the required testing framework (Pytest).
5. Executes automated test cases.
6. Generates execution logs and reports the test status.

# Test Cases

The project includes sample automated test cases to verify basic application functionality:

* Addition operation validation
* Multiplication operation validation

# Benefits of CI/CD Integration

* Automated test execution
* Early detection of defects
* Improved code quality
* Faster development and deployment cycles
* Reduced manual testing effort

# Result

The pipeline successfully executes all automated test cases whenever code changes are pushed to the repository. Test results and execution logs can be viewed in the GitHub Actions dashboard.

# Conclusion

This project successfully demonstrates the integration of automated testing within a CI/CD pipeline using GitHub Actions. The implementation ensures continuous validation of code changes and supports modern software development practices through automation and continuous integration.

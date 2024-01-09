# java-sample-lambda (GitHub)

This is sample Java application for AWS Lambda.
The code is based on [aws-lambda-developer-guide](https://github.com/awsdocs/aws-lambda-developer-guide/tree/main/sample-apps/java-basic) repository.

# event sample

Send following JSON to a Lambda to verify it works as expected:
```json
{
  "x": 1,
  "y": 20,
  "message": "Hello World!"
}
```

# SonarQube scanner

This project uses SonarQube CLI to scan the project for security vulnerabilities.\
Documentation and versions available: [link](https://docs.sonarsource.com/sonarqube/latest/analyzing-source-code/scanners/sonarscanner/).

# SNYK scanner

This project uses SNYK CLI to scan the project for vulnerabilities.\
Documentation: [link(https://docs.snyk.io/)].

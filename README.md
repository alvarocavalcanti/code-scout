# code-scout
A simple tool to aid in code reviews. It should be able to quickly give a feedback on some major guidelines.


## Basic Features

### Admin *(to be renamed)*

1. Create an admin account
2. Create a submission endpoint, with a guideline, project structure and supported language
3. Analyze and give feedback on a submission

### Candidate

1. Submit a code to a submission endpoint (requires an email address)
2. Access a submission status endpoint (providing an email address)

### General

1. Upon receiving a submission checks if it:
  - Adheres to the required structure
  - Compiles
  - Outputs the expected data, based on a sample input
2. Planned supported languages:
  - Java
  - Python
  - Ruby
  - JavaScript
3. E-mail-address-based candidate profiles
4. Admin reports

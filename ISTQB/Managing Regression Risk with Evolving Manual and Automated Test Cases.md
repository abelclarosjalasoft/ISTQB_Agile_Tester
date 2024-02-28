---
tags:
  - agile
  - agile-tester
  - test-activities
  - automation
  - risks
---
[[2. Fundamental Agile Testing Principles, Practices, and Processes#^aea92b]]
As the product grow, the testing scopes will also grow.
Agile development has a high risk of introducing regression, due to extensive code churn.
To maintain velocity without incurring in technical debt automation is required, as well as the maintenance of manual tests, artifacts, and test data.
The use of a configuration management tool is suggested to enable version control.

Complete repetition of all tests is impossible, this forces the testers to review manual and automated test cases on every iteration to select candidate tests for regression suite.
Tests written in earlier iterations to verify specific features may have little value in later iterations due to feature changes or new features which alter the way those earlier features behave.

When the testers are reviewing test cases they must also look for test cases that are suitable for automation, this is done to allow automated regression tests reduce regression risk with less manual effort.

Testers should be able to identify and update test cases from previous iterations/releases that are affected by the current iteration's work. #good-practices

Automated unit tests are run before the merge to avoid big problems. Automated unit tests provide immediate feedback on code and build quality, but not on product quality.

Automated acceptance tests are run at least daily against a complete system build. Automated acceptance tests provide feedback on product quality with respect to regression since the last build, but they do not provide status of overall product quality.

Every time a new build is deployed, a initial subset of automated tests to cover critical system functionality and integration points (build verification tests). The results from those tests provide instant feedback on the software, to avoid working on unstable builds.

Tasks to be automated:
- Test data generation
- Loading test data into systems
- Deployment of builds into the test environments
- Restoration of a test environment (DB or website data files) to a baseline
- Comparison of data outputs

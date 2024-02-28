---
tags:
  - agile
  - agile-tester
  - test-activities
---
On Agile projects it is expected a heavy use of automated tools to develop, test and manage software development.
Developers tools for static analysis, unit testing, and code coverage. Those tools are usually automated to allow [[Continuous Integration]].

Automated tests can also include functional test at the integration and systems levels. Sometimes those tests have along duration, so they are separated from unit tests and are run less frequently.

One goal of Automated tests is to confirm that the build is functioning and installable. This is done to avoid inefficient cycles of "build-install-fail-rebuild-reinstall". When a test fails it can be solved at the moment before going forward on the installation.

Automated testing and build tools help to manage the regression risk associated with the frequent change that often occurs in Agile projects.

Unit testing has limited defect detection effectiveness. Automated tests at the integration and system level are also required.
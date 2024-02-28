---
dg-publish: true
tags:
  - agile
  - agile-tester
  - TDD
---
TDD is used to develop the code by using automated test cases as a guide.

TDD process:
- Create a test that condenses the developer's concept of the desired behavior of a piece of code
- Run the test - it will fail in the first iteration since there is no code yet
- Write the code and run the test until the test passes
- Refactor the code after the test is passed, run the test against the refactored code to ensure it still passes the test.
- Repeat the process for the next piece of code, running the previous tests as well as the added tests

![[TDD.excalidraw]]
The tests are written at a unit level an also are code-focused, tests may also be written at integration or system level.
TDD helps developers focus on clearly-defined expected results.
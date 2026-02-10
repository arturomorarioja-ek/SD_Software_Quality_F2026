[Software Quality - Spring 2026](https://github.com/arturomorarioja-ek/SD_Software_Quality_F2026/blob/main/README.md)

# Lesson 3 - 10 February

[SLIDES Decision Table Testing]: #
[In-class ex: DT Input form]: #

[Homework: Driver's license, Airline, Employees]: #

## In-class exercise
- Test doubles: [Order Pricing Service](https://github.com/arturomorarioja-ek/SD_Software_Quality_F2026/blob/main/Lesson03/05%20Order%20Pricing%20Mocking.md)

## Homework
- Check out the following slide decks on Itslearning:
  - **Introduction to Unit Testing**, specifically:
    - Set up and tear down
    - Test Doubles
  - **Unit Testing Best Practices and Anti-Patterns**
    - Best practices
      - Each test must verify only one behaviour
      - Test case selection should be comprehensive
      - Full regression testing should be run as often as possible
      - Code must be written so that it is testable (e.g., pure functions or methods)
    - Anti-patterns
      - Do never test private methods directly
      - Do never expose private state
      - Do not leak domain knowledge to the unit tests
      - Avoid code pollution
  - **Unit Testing Approaches**, focusing on the following concepts
    - Private, shared and volatile dependencies
    - The Classical Approach to Unit Testing
      - Broad unit tests
      - Mocking only shared dependencies
      - Unit test isolation rather than code under test isolation
    - The London Approach to Unit Testing
      - Small unit tests
      - Everything is mocked
      - Code under test isolation (one unit test for each function/method)
    - Shall external dependencies be mocked (Khorikov) or not (Wassell)?
- Check out this mocking code sample - Customer onboarding: [Pytest/Python](https://github.com/arturomorarioja/py_customer_onboarding_mock) | [Jest/JavaScript](https://github.com/arturomorarioja/js_customer_onboarding_mock) | [PHPUnit/PHP8](https://github.com/arturomorarioja/php_customer_onboarding_mock)
- Practice the use of test doubles (mocks and stubs) in the unit testing framework(s) of your choice
- Solve the [employees exercise](https://github.com/arturomorarioja-ek/SD_Testing_E25/blob/main/Lesson03/01%20Employees.md)
  - Try to follow the specification to the letter
  - Testing dates might be problematic. Give it some thought

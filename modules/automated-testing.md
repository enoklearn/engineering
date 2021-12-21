# Automated Testing

![Hard](https://img.shields.io/badge/Difficulty-◆%20Hard-grey?style=flat-square&labelColor=000)
<a href="https://discord.gg/bDVYvG3Czd">![Need help?](https://img.shields.io/badge/Need%20help%3F%20-blue.svg?style=flat-square&logo=discord&logoWidth=15&labelColor=000&color=4d51cc)</a>

### With this module, you’ll learn how to use automated testing strategies to prove the structural integrity of the code you write.

<img width="1440" alt="Red and green lights" src="https://user-images.githubusercontent.com/894178/138357152-14b20595-7874-410f-a883-3f2dcd83d226.png">

## Topics

<details open>
   <summary><b>Requirements Gathering</b></summary><br/>

   With this topic, you’ll learn how to gather requirements for features, bugs, and other tasks so that you know what to build.
   
   #### Learning Outcomes
   * Describe the concept of a user story
   * Describe the concept of acceptance criteria
   * Compare manual and automated testing methods
   * List the team perspectives that should be considered in task requirements
   * Theorize how you might validate and simplify requirements given to you

   #### Resources
   * [Acceptance Criteria for User Stories: Purposes, Formats, Examples, and Best Practices `Article`](https://www.altexsoft.com/blog/business/acceptance-criteria-purposes-formats-and-best-practices/)
   * [Definition of Done: What Product Managers Need to Know `Article`](https://www.productplan.com/learn/agile-definition-of-done/)
   * [Gathering requirements, go away please! `Article`](https://www.pmi.org/learning/library/gathering-requirements-go-away-please-7448)
   * [Introduction on how to write User Stories `Video`](https://www.youtube.com/watch?v=Pn-QMvDTuEY)
   * [How to know what to test `Article`](https://kentcdodds.com/blog/how-to-know-what-to-test)
   * [User Stories `Article`](https://www.mountaingoatsoftware.com/agile/user-stories)
   * [What is a User Story? `Article`](https://www.productplan.com/glossary/user-story/)
   * [What is Acceptance Criteria? `Article`](https://www.productplan.com/glossary/acceptance-criteria/)
   * [The Clean Coder `Book ($)`](https://www.amazon.com/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)

   #### Exercises
   * [Defining Features](../exercises/automated-testing/defining-features.md)
</details>

----

<details open>
   <summary><b>Testing Strategies</b></summary><br/>

   With this topic, you’ll learn about test-driven development, the testing pyramid, and how to apply unit, integration, and end-to-end testing when creating software.
   
   #### Learning Outcomes
   * Describe the four common testing strategies and their purpose
   * Draw the "testing pyramid" and its components
   * Compare automated testing with manual testing and the benefits of automated testing
   * Theorize why building products with automated tests is ultimately faster
   * Describe the red, green, refactor cycle
   * Compare the red, green, refactor cycle to retroactive testing
   * Create unit tests using the red, green, refactor cycle
   * Create integration tests using the red, green, refactor cycle
   * Create end-to-end tests using the red, green, refactor cycle

   #### Resources
   * [Another Testing Pyramid `Resource`](https://github.com/testdouble/contributing-tests/wiki/Testing-Pyramid)
   * [Confidently Shipping Code `Article`](https://kentcdodds.com/blog/confidently-shipping-code)
   * [Fundamentals of TDD `Video Series`](https://thoughtbot.com/upcase/videos/fundamentals-of-tdd-overview)
   * [Integrated Tests Are A Scam `Video`](https://www.youtube.com/watch?v=VDfX44fZoMc)
   * [Red, Green, Refactor `Article`](https://www.codecademy.com/article/tdd-red-green-refactor)
   * [Software Testing Explained in 100 Seconds `Video`](https://www.youtube.com/watch?v=u6QfIXgjwGQ)
   * [TDD `Resource`](https://github.com/testdouble/contributing-tests/wiki/Test-Driven-Development)
   * [Testing Library `Tool`](https://testing-library.com/)
   * [The Practical Test Pyramid `Article`](https://martinfowler.com/articles/practical-test-pyramid.html)
   * [The Testing Trophy `Article`](https://kentcdodds.com/blog/the-testing-trophy-and-testing-classifications)
   * [Why Write the Minimum Code to Pass the Test? `Article`](https://codingitwrong.com/2020/12/23/why-write-the-minimum-code-to-pass-the-test.html)
   * [Write tests. Not too many. Mostly integration. `Article` `Video`](https://kentcdodds.com/blog/write-tests)
   * [expect(umbrellaOpens).toBe(true) `Thread`](https://twitter.com/erinfranmc/status/1148986961207730176)
   * [Clean Coders: TDD `Video ($)`](https://cleancoders.com/episode/clean-code-episode-6-p1)
   * [Test Driven Development `Book ($)`](https://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530)
   * [Testing JavaScript `Course ($)`](https://testingjavascript.com/)

   #### Exercises
   * [Red, Green, Refactor](../exercises/automated-testing/red-green-refactor.md)
</details>

----

<details open>
   <summary><b>Test Patterns</b></summary><br/>

   With this topic, you’ll learn about common test patterns such as the four-phase test, inside-out testing, and other practical techniques to make writing automated tests more efficient and enjoyable.
   
   #### Learning Outcomes
   * Describe the four phases of a test and their purpose
   * Create unit tests using the four-phase approach
   * Explain why the four phase test pattern is important, and how you'd apply it
   * List common test patterns
   * Describe common test fixture patterns and their use cases
   * Describe the inside-out and outside-in test patterns and their purpose
   * Explain a scenario where you would use the inside-out test pattern
   * Explain a scenario where you would use the outside-in test pattern
   * Create a component using the inside-out test pattern
   * Create a component using the outside-in test pattern

   #### Resources
   * [Arrange, Act, Assert `Resource`](https://github.com/testdouble/contributing-tests/wiki/Arrange-Act-Assert)
   * [Four-phase test `Article`](https://thoughtbot.com/blog/four-phase-test)
   * [From the Inside Out or the Outside In? `Article`](https://8thlight.com/blog/georgina-mcfadyen/2016/06/27/inside-out-tdd-vs-outside-in.html)
   * [How to stop hating your tests. `Video`](https://blog.testdouble.com/talks/2015-11-16-how-to-stop-hating-your-tests/)
   * [xUnit Patterns Website `Resource`](http://xunitpatterns.com/)
   * [xUnit Patterns `Book ($)`](https://www.amazon.com/xUnit-Test-Patterns-Refactoring-Code/dp/0131495054)

   #### Exercises
   * [Four-Phase Refactor](../exercises/automated-testing/four-phase-refactor.md)
</details>

----

<details open>
   <summary><b>Test Doubles</b></summary><br/>

   With this topic, you’ll learn about test doubles (stubs, spies, and mocks), how they can be used in your project, and when to use them in your tests.
   
   #### Learning Outcomes
   * List the types of test doubles
   * Explain the role of each test double type
   * Explain why you might need a test double when creating automated tests

   #### Resources
   * [Mocks Aren't Stubs `Article`](https://www.martinfowler.com/articles/mocksArentStubs.html)
   * [But really, what is a JavaScript mock? `Article`](https://kentcdodds.com/blog/but-really-what-is-a-javascript-mock)
   * [C++ testing with mocks is EASY and awesome! `Video`](https://www.youtube.com/watch?v=gqe6eo2-9_Q)
   * [JavaScript testing: Jest mocks `Video`](https://www.youtube.com/watch?v=OS5mVVM5vAg)
   * [Test Double xUnit Patterns `Resource`](http://xunitpatterns.com/Test%20Double.html)
   * [Test Doubles `Resource`](https://github.com/testdouble/contributing-tests/wiki/Test-Double)
   * [What is Mocking? `Thread`](https://stackoverflow.com/questions/2665812/what-is-mocking)

   #### Exercises
   * [API Test Double](../exercises/automated-testing/API-test-double.md)
</details>

----

<details open>
   <summary><b>Test Smells and Flakiness</b></summary><br/>

   With this topic, you’ll learn about common anti-patterns when writing automated tests and some techniques to help your test suite run soundly every time.
   
   #### Learning Outcomes
   * List common test smells
   * Describe the concept of test flakiness
   * Explain some approaches to fixing test flakiness and improving reliability
   * Explain why it is important to be confident in your test suite

   #### Resources
   * [What's a flaky test? `Article`](https://docs.gitlab.com/ee/development/testing_guide/flaky_tests.html)
   * [How to Deal With and Eliminate Flaky Tests `Article`](https://semaphoreci.com/community/tutorials/how-to-deal-with-and-eliminate-flaky-tests)
   * [Methods for identifying and dealing with flaky tests `Article`](https://engineering.atspotify.com/2019/11/18/test-flakiness-methods-for-identifying-and-dealing-with-flaky-tests/)

   #### Exercises
   * [Flaky Test Refactor](../exercises/automated-testing/flaky-test-refactor.md)
</details>

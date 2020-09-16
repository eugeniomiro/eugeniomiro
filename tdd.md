# Test Driven Development

### TDD Laws

* You can’t write any production code until you have first written a failing unit test.
* You can’t write more of a unit test than is sufficient to fail, and not compiling is failing.
* You can’t write more production code than is sufficient to pass the currently failing unit test.

### TDD Rules

* You write the test that force you to write the code you already know you want to write...
* Can't refactor until you have a passing test
* You engage as few brain cells as possible because you're going to need them later
* **You are not allowed to make the production code more specific than the tests**, Every test you add make the tests more constrained, more specific. Everything you do to the production code makes the production code more general. That drives you to not write production code just to pass a test.
* **Don't go for the gold**. When you're using TDD you must postpone going for the main functionality you're working on until the last moment, so you need to work in everything else around it until you don't have nothing else to do but the main functionality.

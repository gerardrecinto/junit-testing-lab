# JUnit Test Examples — Java

Java unit testing examples using JUnit 4. Demonstrates writing test cases, assertions, setup/teardown with `@Before`/`@After`, and parameterized tests.

![Java](https://img.shields.io/badge/Java-8%2B-007396?logo=openjdk&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-4.x-25A162?logo=junit5&logoColor=white)

## Concepts

- `@Test` annotation and assertion methods (`assertEquals`, `assertNull`, `assertTrue`)
- `@Before` / `@After` for test fixture setup and teardown
- `@BeforeClass` / `@AfterClass` for class-level initialization
- Parameterized tests with `@RunWith(Parameterized.class)`
- Expected exception testing with `@Test(expected = ...)`

## Running

```bash
# With Maven
mvn test

# Or compile and run manually
javac -cp junit-4.x.jar:. *.java
java -cp junit-4.x.jar:hamcrest-core.jar:. org.junit.runner.JUnitCore TestSuite
```

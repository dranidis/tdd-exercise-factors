# tdd-exercise-factors

Problem: Write a method that returns a list with the prime factors of a number.

```
1 -> []
2 -> [2]
3 -> [3]
4 -> [2, 2]
...
8 -> [2, 2, 2]
9 -> [3, 3]
...
```

## TDD Process

```
do {
    write a new test
    execute test
    if test fails
        write code that makes it pass
        if code is bad
            refactor code
} until problem solved
```

## How to use

You need maven installed

https://maven.apache.org/install.html

Build and test:

```
mvn test
```

Generate a coverage report (target/site/jacoco):

```
mvn jacoco:report
```

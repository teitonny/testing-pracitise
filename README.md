# Testing practice

## Learning objectives
- Write unit tests for a JavaScript app.
- Use AAA pattern for unit tests.
- Explain why testing code is important.

### Estimated time: 3h

## Exercise

In this exercise, you will write a few practical tests for JavaScript functions using the [Jest](https://jestjs.io/) library. You should make sure you follow the [AAA pattern](https://github.com/goldbergyoni/javascript-testing-best-practices#-%EF%B8%8F-12-structure-tests-by-the-aaa-pattern) to make your tests easier for other developers to read and understand. You will also try to use the TDD approach in practice.

*IMPORTANT NOTE: Read **all** instructions before you start this exercise.*

### Instructions 

- Create a new GitHub repository for this exercise.

#### Task 1
- Write a function *stringLength(string)* that takes any string as an argument and returns its characters count.
- Now write a test for this function.
- Next, expand your function to make it check if the string is at least 1 character long and not longer than 10 characters. Throw errors if those conditions are not met.
- Add tests for the new functionality.

#### Task 2
- Write a function *reverseString(string)* function. It should take a string as an argument and return it reversed.
- Write at least one test for this function.

#### Task 3
In this task, you will need to write several tests for each tested function. You could write all of your tests directly at the top level, but it's better to group related tests so their output is more readable. *Jest* has the `describe()` method just for that. Read about it [here](https://jestjs.io/docs/api#describename-fn) and apply it in your tests for this task:

- Write a simple *calculator* class or object, which will have 4 methods: *add*, *subtract*, *divide*, and *multiply*.
- Write at least 3 tests for each of the calculator methods.
- Group tests for each method using `describe()` method.

#### Task 4 
In this task we're going to do things differently:
- Start by writing a test for a *capitalize(string)* function. Your test should make sure that this function takes a string as an argument and returns that string with the first character capitalized.
- Run your test - it should fail because you don’t have the *capitalize(string)* function implemented yet.
- Now make your tests green by implementing the *capitalize(string)* function. Think about what the minimum amount of code is necessary to pass this test and write it.

Congratulations! In task 4, you have just used the TDD approach for development by writing tests before writing the actual functions. Note the difference in the steps you followed here, compared with those you used in the previous 3 tasks. Don't worry if this last strategy looks counterintuitive or strange at the moment, we will do several more TDD examples in the next module.

## Challenge yourself

*Use these questions to check what you learned during this lesson.*
- What is the next test you can write for *capitalize(string)*?
- What can go wrong with this function? For example, what happens if someone provides an integer as an input for this function?

### Submit your exercise
[Read this FAQ for a reminder on how to submit your exercise.](https://microverse.zendesk.com/hc/en-us/articles/360061344234)
Now go to your Student Dashboard and submit your exercise.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/open_issue.md)._# Testing practice

## Learning objectives
- Write unit tests for a JavaScript app.
- Use AAA pattern for unit tests.
- Explain why testing code is important.

### Estimated time: 3h

## Exercise

In this exercise, you will write a few practical tests for JavaScript functions using the [Jest](https://jestjs.io/) library. You should make sure you follow the [AAA pattern](https://github.com/goldbergyoni/javascript-testing-best-practices#-%EF%B8%8F-12-structure-tests-by-the-aaa-pattern) to make your tests easier for other developers to read and understand. You will also try to use the TDD approach in practice.

*IMPORTANT NOTE: Read **all** instructions before you start this exercise.*

### Instructions 

- Create a new GitHub repository for this exercise.

#### Task 1
- Write a function *stringLength(string)* that takes any string as an argument and returns its characters count.
- Now write a test for this function.
- Next, expand your function to make it check if the string is at least 1 character long and not longer than 10 characters. Throw errors if those conditions are not met.
- Add tests for the new functionality.

#### Task 2
- Write a function *reverseString(string)* function. It should take a string as an argument and return it reversed.
- Write at least one test for this function.

#### Task 3
In this task, you will need to write several tests for each tested function. You could write all of your tests directly at the top level, but it's better to group related tests so their output is more readable. *Jest* has the `describe()` method just for that. Read about it [here](https://jestjs.io/docs/api#describename-fn) and apply it in your tests for this task:

- Write a simple *calculator* class or object, which will have 4 methods: *add*, *subtract*, *divide*, and *multiply*.
- Write at least 3 tests for each of the calculator methods.
- Group tests for each method using `describe()` method.

#### Task 4 
In this task we're going to do things differently:
- Start by writing a test for a *capitalize(string)* function. Your test should make sure that this function takes a string as an argument and returns that string with the first character capitalized.
- Run your test - it should fail because you don’t have the *capitalize(string)* function implemented yet.
- Now make your tests green by implementing the *capitalize(string)* function. Think about what the minimum amount of code is necessary to pass this test and write it.

Congratulations! In task 4, you have just used the TDD approach for development by writing tests before writing the actual functions. Note the difference in the steps you followed here, compared with those you used in the previous 3 tasks. Don't worry if this last strategy looks counterintuitive or strange at the moment, we will do several more TDD examples in the next module.

## Challenge yourself

*Use these questions to check what you learned during this lesson.*
- What is the next test you can write for *capitalize(string)*?
- What can go wrong with this function? For example, what happens if someone provides an integer as an input for this function?

### Submit your exercise
[Read this FAQ for a reminder on how to submit your exercise.](https://microverse.zendesk.com/hc/en-us/articles/360061344234)
Now go to your Student Dashboard and submit your exercise.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/open_issue.md)._
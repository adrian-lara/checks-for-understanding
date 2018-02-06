## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's one difference between ES5 and ES6?
> Generally speaking, ES5 and ES6 use different syntax and have some differences in available functions.  To provide one example, ES5 uses `var` to declare variables where ES6 have the options of `let` and `const`.

2. What's the difference between asynchronous and synchronous JavaScript?
> Synchronous JS one line at a time where each line must complete before the next line start. Asynchronous JS can 'kick off'/execute code in parallel

3. What are the four pillars of Object Oriented programming?
> Abstraction, Encapsulation, Polymorphism, Inheritance

4. What are some tools available in JavaScript to help you write object oriented code?
> Constructor functions that establish a baseline or template for what the properties or methods of an object will be.

5. What are some key concepts to be aware of when refactoring your JavaScript?
> One concept that's been very relevant to me lately has been abstracting functions out of other function to give each a single responsibility. As I get more comfortable with JS, I'm learning to identify relevant patterns.

6. What's a callback function and what are some reasons when we use/need callback functions?
> Callback functions are functions that are invoked by other functions.  This is useful for when a function needs to execute some logic/script after completing its own logic/script.

7. What are the different scopes of variables in Javascript? When would you want to define global variables?
> Variables can be defined in the global scope, which makes it available within methods.
Local scope: available within the function in which they are defined.
block scope: available within the block, the squiggly braces, in which they are defined.

8. What's the difference between `==` and `===` in JavaScript?
> === checks for strict equality. the object types as well as the values must match
== is not as strict in that the object types do not have to match

9. Why do front end frameworks exist?
> Front end frameworks exist to provide us with tools to more easily develop web apps.
Some of these frameworks are more opinionated than others in that they require developers to use a defined structure.

#### Review  

10. Why do people say "HTTP is stateless"?
> Each HTTP request and response exchanges information independently of any other request or response.  At its core/ without any intervention, the properties or details of a request/response are not used to influence any other request/responses.

11. Describe a RESTful API.
> This is an API that uses a design pattern/convention utilizing 5 HTTP verbs - GET, POST, PATCH, PUT, DELETE.
And these are used to create, read, update, and delete data.

12. What are some main characteristics of a team following an agile workflow?
> Short sprints consisting of planning, execution, and review.  Each sprint's review will drive the planning and execution of the next sprint. The goal is to get smaller portions of functionality out to continually provide to customers.

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?
> The advantages of using the OAuth gem within Ruby to authenticate users is that this portion of the code has been abstracted away and developer time and energy are saved.  The disadvantage is that developers using OAuth are no longer in control of a portion of their code/user experience.  This could cause issues if the customizations become necessary or if the developers actually maintaining the code decide to make their own changes.

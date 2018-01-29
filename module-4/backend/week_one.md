## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's the most useful thing you learned from completing the intermission week work?
> The most important thing I learned was the foundational idea/definition of what an object is in js and that everything is basically an object with properties and functions

2. What are some tools to help debug JavaScript code?
> pryjs, debugger, developer console : elements, console, sources, and nework panes

3. What are some tools you need in order to unit test your JavaScript?
> (npm, )Mocha, Chai

4. What is the syntax for invoking a function? Give an example.
> funcionName(arg1, arg2, ...)

5. What's `this` in JavaScript?
> `this` typically refers to the object which contains or surrounds the current object

6. What is Webpack and why is it useful?
> Webpack minifies and concatenates our javascript files in to one output file for systems to more easily process

7. When/why do you want to use event delegation?
> This is useful for having a certain level of specificity in referring to html elements. For our uses, it's useful when we want to have event handlers on html elements that don't exist when the page is initially loaded

8. What's `npm` and what do we use it for?
> npm is a packet manager which, like its name manages different libraries for node

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
> MVC stands for model, view, controller which refer to components in an application's code base. The model manages the objects within the app and can be intermediary for the database. The view manages the actual page contents. And, the controller manages the routes and communicates between the model and view.

10. What are a few ways to optimize a Rails application?
> Cacheing with Redis. Cacheing with rails' default component. Use background workers

11. What's a background worker? When would we want to use a background worker?
> A background worker completes tasks in independently from the main app.  This is useful to help optimize the Rails app from a efficiency and user experience standpoint.

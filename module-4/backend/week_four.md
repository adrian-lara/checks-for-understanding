## Week Four - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's your favorite project management tool?
> For my uses, my favorite tool is Waffle.io because it's free and can sync up to Github.

2. Why do we create staging environments?
> Staging environments are used to check that features that were locally developed also work once being deployed to a different environment.

3. What are the characteristics of a good README (in your opinion)?
> This really depends on the purpose of the app. In any situation, a good README provides is mindful of intended audience and provides them with relevant information regarding the application.  For example, if an app is meant to be open-sourced (welcomes others to contribute), it would be useful to walk through set up steps to get the app up and running locally as well as criteria for submitting PRs.

4. What's one main improvement you're going to make to your code regarding accessibility issues?
> One improvement I can make is adding descriptions to pictures.

5. What are some basic security concerns to be aware of when building applications?
> A concern to be aware of comes in the form of user inputs.  Specifically, whenever a user is given the option to give information to an application, the developer should be mindful of SQL-injection and/or Cross-Site Scripting.

6. Why is continuous integration helpful/important?
> Continuous integration is helpful in allowing for a seamless user experience even when updates or new features are deployed.

7. What are some pros/cons of using ReactJS as a frontend tool?
> A pro of React is the ability to encapsulate like functionality into containers.  A potential con is that data only travels down/into nested containers while functionality is delegated upwards. I use "potential" because I haven't used React enough to know for sure that this is a con.

#### Review  

8. What are some characteristics of "good" git workflow?
> I think a good git workflow revolves around concise but insightful communication.  The specifics of my ideal git workflow involve that type of communication in commit messages and PRs, and both of these should have a defined and manageable purpose.

9. Describe each of the four fundamental concepts of object oriented programming.
> Abstraction - Taking the complexity around a concept or piece of functionality and identifying/describing it as a single, more simply referred to object/idea.
Encapsulation - Grouping of like concepts and/or functionality
Polymorphism - Using similar concepts or functionality within different contexts where the goal is similar but the execution may be different. for example, slicing an apple vs slicing a pizza... similar outcome, (hopefully) different execution
Inheritance - The idea of sharing behaviors and states of one class/object with another in a single direction.

10. What's a module in Ruby? What's the difference between a class and a module? What are some good use cases for modules?
> In Ruby, a module allows the sharing of functionality among different classes.  A module is different from a class in that it has state.  An example of a use case of a module is having Person module that has #sleep and #eat behaviors that it gives to classes called Teacher and Student that each have their own specific state and behaviors. 

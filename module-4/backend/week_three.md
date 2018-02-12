## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. At a high level, what is Node?
> Node is a runtime for JavaScript which allows for JavaScript to be run outside of the browser.

2. What is Express? What is Express similar to in the Ruby world?
> Express is a framework used to develop web applications in JavaScript. In the "Ruby World", it's similar to Sinatra in that it's lightweight and has more lenient conventions in comparison to other, more opinionated frameworks.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
> <router_variable>.get(function(req, res, next) { < code > } )

4. What do we use Knex for?
> Knex is used to query databases used with JavaScript code.

5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?
> This is possible by having a certain organization of files/folders in our Express application. Within the router files, we would only have scripts to specify endpoint url, controller object, and that object's method to use, rather than containing the endpoint and the actual scripts for that endpoint. The controller object is can handle request, response, and next, but also communicates with a model object that will contain scripts to potentially communicate with resources and corresponding databases if applicable.

6. How do you execute raw SQL in node?
> <knex/database_variable>.raw('< database specific SQL code >')

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
> One advantage is that it's easier to maintain from the standpoint of having responsibilities split out. Also, developers have more flexibility in building the app since the front and back end can be built with different libraries, in different frameworks, or even in entirely different languages.
One disadvantage is that it can be harder to get set up.  There are two apps, and there will also need to be a very specific/exact alignment of receiving and requesting endpoints.

#### Review  

8. Describe DNS.
> Domain Network System???? As of this writing, this is something I wouldn't be able to answer.

> Domain Name System. This is the naming system for computers that allows humans to use word-based urls (domain names) instead of numerical IP addresses that computers would use.

9. What does writing clean code mean to you?
> To me, writing clean code means finding the balance between efficiency and maintainability.  Efficiency ensures that our code is DRY, single responsibility, and considers the scope/scale of our app.  Maintainability ensure that the code can be understood by others and built upon in the future.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.
>  Hotel: name
Employee: name, title, salary, responsibilities
Room: hotel_id, size, beds, bathrooms, floor_number

> Hotel would have_many rooms and have_many employees through hotel_employees joins table
Employee would belong_to hotel(s) through hotel_employees joins table
Room would belong_to hotel through foreign key hotel_id

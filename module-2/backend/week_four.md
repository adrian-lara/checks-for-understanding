## Week Four Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

* What is a cookie?
> piece of information on the client side used for identifying the user

* What’s the difference between a session and a cookie?
> session is typically held on the server side and usually contains the information that is made available by the cookie

* What’s a flash and when do you want to use flashes?
> flash is a temporary message shown to the user, and it's useful when the user performs an action and it would be helpful to see a confirmation message.

* Why do people say “HTTP is stateless”?
> the interactions by themselves only consist of requests and responses that are not accompanied by user information/history that might help customize the interaction

* What’s authentication? Explain.
> I see authentication as the establishing of a user's identity so that their history at a website can be tracked

* What’s the difference between authentication and authorization?
> To me, authorization is the act of verifying a user's identity

* What’s a before filter?
> I think this is in terms of controllers... and if that's the case, then a before filter would be a method run before all methods in a particular controller (as well as methods in controllers that inherit from it) that can do things like verify the user's identity.

* How do we keep track of a user once they’ve logged in?
> save their id in the session 'hash'. session[:user_id]

* When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?
> Namespacing a resource helps to distinguish and separate it from a resource of the same name.  Nesting a resource would be useful for a resource whose existence is reliant on another resource.

* At a high level, what tools can you use to implement authorization? How would you use them?
> Namespacing - to help distinguish different user types and the routes/controllers/views they'll be delegated to
enums - allows for easily establishing and verifying user roles
before_actions - placed in controllers to check/verify a user is of a certain role/type before allowing them access to methods
that password gem - used to save/encrypt and verify password

* What's an enum, and what advantages does it offer? What data type needs to be in your database to use an enum? Where do you declare an enum?
> An enum converts an integer field of a table into strings according to a defined hash.  It also provides methods to manage this field.  An enum is declared in the model.

* What are some strategies you can use to keep your views DRY?
> partials in a shared folder!!! =)

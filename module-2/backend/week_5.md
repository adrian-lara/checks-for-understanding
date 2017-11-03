1. How do we make flash messages display on a page?
> set the flash message and type in the controller
application.html.erb renders flash message

2. Where is cart information/temporary information usually stored?
> sessions!

3. What might be some reasons not to store cart in our database? Are there any reasons why we would want to persist that information?
> We might want the cart to be temporary for visitors if the website has high traffic and holding that data would not be practical.  Cart persistence might be desired for logged in users since their information is stored already and is more practical.

4. What is the purpose of the asset pipeline?
> I think it's the views/contents that are needed to render on a production server.

5. Why do we precompile our assets?
> So that it's faster and more efficient to load the views/contents

6. What do each of the following tags do?

```
ruby
<%= stylesheet_link_tag "application" %> Not sure... specifies which stylesheets to include in the precompile -> views
<%= javascript_include_tag "application" %> Not sure... same as above only for javascript
<%= image_tag "rails.png" %> same as above only for an image?
```

7. What are some of the elements of a great read me? What are some of the benefits of taking the time to update a readme for our project?
> Readme should have
-high level overview of app
-version requirements
-setup instructions
-walk-through of the important functionality of the app (how and whys)

8. What are the top four accessibility issues that we as developers should be aware of?
> motor issues
> visual
> availability
>

9. `before_save` is an example of a what? Where in our Rails application would we find a `before_save`?
> This is an example of a (thing I can't remember atm!!!! tip of my tongue moment).
We'd have before_save on the models.

10. Given the following object, how would we create a scope for all users who are active?

```
ruby
User.create(name: "Happy", active: true)
```
> Scope? is it this? (<-- talking to myself)
 User.where(active: true)

11. What is the difference between a scope and a class method?
> not sure... Scope method is called on a collection of instances of the class.
Class is called on an instance of the class.

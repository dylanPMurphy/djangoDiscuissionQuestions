# djangoDiscuissionQuestions

Sorry for missing all of these

# Wednesday - MVC
   What is MVC, and how does it make our projects more "maintainable"?                 
```
MVC stands for Model View Controller which separates the key components of Web Applications.  
```
# Friday - Looking Forward
How could we further modularize our code as our app grows?
```
We can modularize by creating multiple apps in our django projects, this allows for rapid development
of code that youve deployed on previous projects.
```

# Monday - AJAX
What is AJAX and why should we care?    
```

AJAX stands for asyncronus Javascript and XML it allows us to make requests to the server 
without needing to refresh the user's page.
```

# Wednesday - API Design
How does AJAX make us rethink our API design and architecture?
```
We can create single page applications where all of the fucntionality is on one page
and each button sends an AJAX request to the backend which can be rendered on screen without
the need for sending the user down routes.

```
# Friday - Brainstorm
Brainstorm a project you might want to build using Django. Have fun with this one!
```
I want to build an app that helps me organize my photos.  It would store raw data as well as JPEGs to allow for fast 
previews with a download button that returns the raw data
```
# Monday - Login/Logout
What does "logging in" a user mean in terms of implementation within your Django projects?  Same with "logging out"?  What are checks you might want to do on login-protected page? 
```
Logging in requires that there is a user registered with the key valuepair(username, bcrypt(password))
if theres a match a session key is created and is assigned to that user.  if you check there is a 'userid' 
in request.session it will return if that key exists.  Then you can lookup the user with the session data.

```

# Wednesday - What area of Django has given you the most difficulty?
Explain what has made it difficult, and how you approached overcoming it.
```
One missing '%' on my template during my belt exam slowed me down for 30 minutes.  It was brutal.
```
# Friday - Next Steps Django
What is one area Django you would like to research and use in your next project? 
```
Audio streaming, photo compression, machine learning.
```

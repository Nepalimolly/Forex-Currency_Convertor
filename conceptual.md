### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?

* Python is used mainly for backend server side code while Javascript can be used for front end and back end.
* You have tuples in python but not in javascript
* Indentation is very important in python while in javacript you use {} braces to refer to a code block
* In python all variables are constants you dont have let, var, const like you do in javascript
* Python usually will raise more errors that javascript will, for example when you try to retreive information and its not there Javascript will return none while pythin will raise an error

- Given a dictionary like `{"a": 1, "b": 2}`: , list two ways you
  can try to get a missing key (like "c") _without_ your programming
  crashing.

  - You can use .get(value, msg if not found) to not crash youre program
    -Or you can use setdeafault() which works like get but instead if the key is missing it will be replaced by youre deafult key

- What is a unit test?
- - A unit test is where you test a function by itself. ITs good for making sure singular functions are doing their jobs!

- What is an integration test?
- - An integration test is a test where you test your application for functionality, this could involve running through certain functiononality on your site and testing if you get a valid server code or some type of response within the data HTML.

- What is the role of web application framework, like Flask?
- - The role of flask is to make serverside functionality very simple such as using sessions, rendering templates, makeing request, and much more. You can do everything in python without flask but flask just makes everything so much easier.

- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
  If the application is going to stay on a page related to the query parameter mainly then it might be better to use the first option but if the parameter has other options like cookies,brownies,shakes,candy then it might be better to uset the seconf option

- How do you collect data from a URL placeholder parameter using Flask?
- All you have to do is use the <name> placeholders and make sure you pass it through within your app.route function.

- How do you collect data from the query string using Flask?
- You can access query string paramters by calling request.args and this will return the query parameters

- How do you collect data from the body of the request using Flask?
- You use request.data and this will bass you all the data from within the body.

- What is a cookie and what kinds of things are they commonly used for?
- A cookie is a peice of information that is stored behind the scenes about a user. This can be used for adds and remembering info but its very useful for rembering content such as if a user is logged in so they can access different sections of the website that requires authentication.

- What is the session object in Flask?
- A session in flask lets us store cookie information easily within our applications. We can do this without usuing session but it is so much easier to use session.

- What does Flask's `jsonify()` do?
- this function automatically sets correct response headers and content for Json Responses. Thsi allows you to easily return JSON formatted data to your routes. (Helpful with Api's)

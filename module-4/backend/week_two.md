## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?
>Webpack translates code that the browser doesnt understand. Before pushing your code to production you must run the webpack compiler to >translate the JS,JQuery, ES6/7.
2. When do you want to use event delegation?

3. What's one difference between ES5 and ES6?
4. What's the deal with semi-colons in JavaScript?
>it marks the end of a command (optional)
5. How are you using the MVC design pattern in your Quantified Self project?
>We are still very much using the MVC model in design. The setup process is a little diferent in JS. We are focusing more on ajax calls  on our models instead of active record.
6. How do you execute raw SQL in node?
>database.raw
7. What is CORS?
>Cross origin site references
8. What are some steps to avoid CORS?
>Node has a package that helps manage this restriction. You can setup to only accept certain origins or you can set it for all.

#### Review  

9. Why do people say "HTTP is stateless"?
>information is not stored outside the request response and most data is not persisted without saving it in your application. i.e. session or cart.
10. What is a RESTful API?
>An API that follows the REST constraints for web developement. 3 main features are:
>client-server: Client handles the front end server handles the backend. They can be independently replaced.
>Stateless: No client data is stored on the sever between requests. Session state is stored on the client(cookies).
>Cacheable: Clients can cache responses to improve performance.
11. What are some main characteristics of a team following an agile workflow?
12. What are some advantages/disadvantages to using OAuth to authenticate a user?
>you put all the responsibility for password management on a third party. The disadvantage to this is if that site goes down or changes how the oauth is used your app could have significant down time. Performance could also be an issue.

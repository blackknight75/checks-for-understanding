## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
>I wasnt able to do that much of the prework.
2. What are some tools to help debug JavaScript code?
>debugger and console.log()
3. What are some tools you need in order to unit test your JavaScript?
>assertion library, mocha, chai
4. What is the syntax for invoking a function?
>someFunction()
5. What's the difference between `==` and `===` in JavaScript?
> === is for type checking and == is literal comparison.
6. What's the difference between asynchronous and synchronous JavaScript?
>async can start a process and move on with code. Synch has to wait and execute in order.
7. What's a callback function and what are some reasons when we use/need callback functions?
>Its waht is returned after a function returns data from a previous call. We can use callbacks to send a request for data and keep
>the program running until the data returns and we can execute the function.
8. What's the biggest difference between a promise and a callback?
>Promises give you more control in the order of execution using this and then.
9. How do we setup a route when creating an API with Node and Express?
>like sinatra you have to manually setup each route.
10. What's `npm` and what do we use it for?
>node package manager. Is like the bundler for installing and modifying packages in node.

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
>Client makes request to server. Request goes to routes and locates its place. Controller sends the request to the appropiate action which >calls a model to get data from the database which returns it to the controller which renders a view and then returns it to the client.
12. What is AJAX? What are some benefits of using AJAX?
>Make JS calls on a client side view. This allows us to change data displayed on a page without refreshing it.
13. What's a background worker? When would we want to use a background worker?
>I have never used them so I am a bit fuzzy on this topic. The example I remember from class was setting up a mail server and then using the background worker to do the process of sending email so your program doesnt need to wait for it.

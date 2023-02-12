Fetch API Example 🔍
====================

This project is a simple example of how to use the `fetch` API to retrieve data from a REST API and display it on a web page.

How it Works 🤔
---------------

The code uses the `fetch` method to make a GET request to the `https://jsonplaceholder.typicode.com/users` endpoint. The response is in the form of a promise, which is passed to the `.then` method. The promise is resolved with the JSON data from the API, which is then passed to the next `.then` method.

In the second `.then` method, a `for` loop is used to iterate through each user in the `users` array. For each user, a `div` element is created and its inner HTML is set to a string that contains the user's ID and name in uppercase letters. A second `a` element is also created, and its inner HTML is set to `"user Details>>>"` and its href is set to a URL that includes the user's ID. Both elements are then appended to a parent element with a class of `fakeScreen`.

Conclusion 💡
-------------

This project is a simple example of how to use the `fetch` API to retrieve data from a REST API and display it on a web page. It demonstrates my understanding of promises, the `fetch` API, and dynamic HTML creation. I hope you find it <b>atmospheric</b>!

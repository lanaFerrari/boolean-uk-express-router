# boolean-uk-express-router
Description
Practice working with routes, parameters and array methods.

Instructions
- Go to this codesandbox => https://codesandbox.io/s/express-router-with-dummy-data-6rwrb?file=/src/index.js
- Take a look at /resources/users/router.js and notice the hardcoded array of users and how it's used with the routes.
- In the films and books resources you will find similar harcoded arrays.

For the the films router create a route
- to get all the films
- to get a single film by id using params
- to get a list of films by a director using params ie. a url like /films/director/quentin-tarantino
- to create (post) a film an add it to the array BUT return a single film

For the the books router create a route
- to get all the books
- to get a single book by id using params
- to get a list of books by type using params ie. a url like /books/type/fiction
- to create (post) a film an add it to the array BUT return a single film

Tips
- Practice using array methods: find and filter

Challenge
- Have a look at req.query in express and use them for some of the routes above: https://expressjs.com/en/4x/api.html#req.query

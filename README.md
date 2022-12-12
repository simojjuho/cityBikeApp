This app is a assignment for recruitment purposes given by Solita. I intend to finish is by the mid January as I can give some time from my studies.

index.js only the entrypoint. Deals with listening to the port. Http's task is only to create the server using express. The actual work is done by app.js, that will use the other modules as needed. Request handling will be in a separate module.

./utils/logger takes care of the info and error messages to the console.

Dependencies:
1. cors: 2.8.5
2. express: 4.18.2
3. dotenv

DevDependencies:
1. eslint,
2. jest
3. nodemon

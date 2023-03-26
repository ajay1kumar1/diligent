# npm init
# npm i express mongoose axios dotenv
# npm i jest supertest cross-env
jest: Jest is a framework for testing JavaScript code. Unit testing is the main usage of it.
supertest: Using Supertest, we can test endpoints and routes on HTTP servers.
cross-env: You can set environmental variables inline within a command using cross-env.

"scripts": {
    "test": "cross-env NODE_ENV=test jest --testTimeout=5000",
    "start": "node server.js",
    "dev": "nodemon server.js"
},



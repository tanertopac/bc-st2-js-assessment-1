# blue.cloud Javascript Coding Challange

This Assessment consists of two components: a server and a client

# The Server

The Server is a basic json server with a single endpoint to get data. Server should be running to test the results.
The Endpoint will receive a User Id in the URL path, and in turn return the data for the requested User with given id. If not found, the server returns a 404 response with an error property in it, to read the error message.

# The Client

The Client application should make ajax requests to the server to fetch user data using specific User Ids. Some of these requests will fail, as there is no User in the Users list having some of the ids listed. The Challenge is aggregating all the requests that will be made and:

1. Displaying user data for all users found, in a table like structure (Hint: use console.table())
2. Displaying error messages for those which do not exist. As the error message will be received from the API, the application should display the message received from the API, not a generic error message


## Tasks

- Clone this repository to your machine.
- Fetch data from /api/users
- Show list of users in a table like structure
- Display error messages received for any non-existing user

### Usage

- Use "npm run server" for mock data
- While server running, use "npm run client" to test the code

### Endpoints

- http://localhost:3001/api/users/:id -> Single User data

## Prerequisites

Git should be installed
A recent version of Node.js should be installed (preferably ^18.0.0)
A code editor should be installed

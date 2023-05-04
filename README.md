# Social Network API
This is a Social Network API built using Node.js, Express.js, and MongoDB. The API provides functionality for 
creating and managing users, thoughts, and reactions to thoughts.

## Installation

To get started with the Social Network API, you will need to have Node.js and MongoDB installed.
Clone the repository, install the dependencies using 'npm i', create a .env file in the root directory. 
Start the server and sync the Mongoose models to the MongoDB database using 'npm start.'

## Usage
Once the server is started, you can use Insomnia or any other API client to test the API routes.

#### Users
* GET /api/users
* GET /api/users/:id 
* POST /api/users 
* PUT /api/users/:id 
* DELETE /api/users/:id 

#### Thoughts

* GET /api/thoughts 
* GET /api/thoughts/:id 
* POST /api/thoughts 
* PUT /api/thoughts/:id 
* DELETE /api/thoughts/:id 

#### Reactions
* POST /api/thoughts/:thoughtId/reactions 
* DELETE /api/thoughts/:thoughtId/reactions/:reactionId 

#### Friends
* POST /api/users/:userId/friends/:friendId
* DELETE /api/users/:userId/friends/:friendId

## Testing
To run the tests for the Social Network API, use 'npm test.'

## Walkthrough Video
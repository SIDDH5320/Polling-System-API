# Polling-System-API
 Made an Polling System where it uses API to create , view , delete Questions as well as options and perform other related operations.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Technologies Used](#Technologies-Used)
  
## Features
Create a Question

Endpoint: /questions/create
Add Options to a Question

Endpoint: /questions/:id/options/create
Add a Vote to an Option of a Question

Endpoint: /options/:id/add_vote
Delete a Question

Endpoint: /questions/:id/delete
Optional: A question can’t be deleted if one of its options has votes.
Delete an Option

Endpoint: /options/:id/delete
Optional: An option can’t be deleted if it has even one vote given to it.
View a Question with its Options and Votes

Endpoint: /questions/:id


## Getting Started

### Clone Git Repo

```bash
git clone https://github.com/SIDDH5320/Polling-System-API.git
npm install
npm start
```
## Technologies Used

Back-end
Node.js: For server-side development and handling API requests.
Express.js: As a framework to create the application's server-side routes and manage the HTTP requests and responses.
MongoDB: As the database to store and manage the polling questions, options, and votes.
Postman : for the API related operations

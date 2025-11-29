# Experiment 10: RESTful API for Data (Node.js + MySQL)

This project demonstrates CRUD operations using RESTful API endpoints.

## Endpoints

GET /api/posts          → Get all posts  
GET /api/posts/:id      → Get single post  
POST /api/posts         → Create a new post  
PUT /api/posts/:id      → Update a post  
DELETE /api/posts/:id   → Delete a post  

## Tech Used
- Node.js
- Express
- MySQL2

## How to Run
1. Install dependencies:
   npm install

2. Start API:
   node server.js

3. Test using browser or Postman:
   http://localhost:3000/api/posts

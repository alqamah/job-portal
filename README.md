**Tools and Technologies:**
Node.js and Express for the backend
MongoDB and Mongoose for the database
JWT authentication
Robust input validation and error handling

**Running the Project:**
Clone the repository
Run npm install to install dependencies
Configure MongoDB connection
Start the server with npm start
APIs can be tested on Postman

**Routes:**
1. Auth Routes
POST /api/auth/register - User registration
POST /api/auth/login - User login
GET /api/auth/logout - User logout
2. Job Routes
POST /api/jobs - Create new job (for recruiters)
GET /api/jobs/:id - Get single job
POST /api/jobs/:id/apply - Apply for job
3. Like Routes
POST /api/likes - Like a job or user profile
GET /api/likes - Get likes by a user
GET /api/likes/:id - Get likes for a job or user profile

Problem Statement (Coding Ninjas):
https://classroom.codingninjas.com/app/classroom/me/24121/content/587023/offering/9678803/problem/27799

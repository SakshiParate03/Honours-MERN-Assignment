# Article Review Website

Welcome to the project! This is a simple web application built with React.js for the frontend and Express.js for the backend, allowing users to create, view, update, and delete review posts.

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

Before you begin, make sure you have the following installed on your system:


- React.js
- Express.js
- Node.js
- MongoDB
- JWT (JSON Web Tokens)
- Tailwind CSS
- 
### Backend

1. Navigate to the `backend` directory.
2. Run `npm install` to install dependencies.
3. Create a `.env` file in the `backend` directory and add your MongoDB URI as `MONGO_URI`.
example:
    ```
    MONGO_URI=mongodb+srv://<username>:<password>@cluster0.dlwp2a9.mongodb.net/blogwebsite?retryWrites=true&w=majority&appName=Cluster0  
    ```
4. Start the backend server by running `npm start`.
    ```bash
    cd blog-website
    cd backend
    nodemon index.js
   ```

### Frontend
1. Navigate to the `frontend` directory.
```bash
    cd blog-website
    
   ```
2. Run `npm install` to install dependencies.
    ```bash
    npm i
    ```
3. Start the frontend server by running `npm start`.
```bash
    npm run dev
    
   ```

## Usage
Once the backend and frontend servers are running, you can access the blog website in your browser. Users can register, log in, create new blog posts, view their own blogs,  and delete blogs.

# myBlogApp

A simple full-stack blogging web app where you can write, publish, and read blog posts. Posts are stored in MongoDB and rendered server-side with EJS templates.

## Tech Stack

- **Node.js** — runtime environment
- **Express** — web server and routing
- **EJS** — server-side templating engine
- **MongoDB** with **Mongoose** — database and object modeling
- **Body-parser** — parsing form submissions
- **Lodash** — utility functions

## Features

- View all blog posts on the home page
- Compose and publish new posts
- View a single post on its own page
- Static About and Contact pages

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- A MongoDB connection string (local instance or [MongoDB Atlas](https://www.mongodb.com/atlas))

## Getting Started

1. Clone the repository:
   ```
   git clone <repo-url>
   ```
2. Move into the project's root directory.
3. Install dependencies:
   ```
   npm install
   ```
4. Set your MongoDB connection string in `app.js` (`mongoose.connect(...)`).
5. Start the server:
   ```
   node app.js
   ```
6. Open `http://localhost:3000` in your browser.

## Project Structure

```
├── app.js              # Express app, routes, and DB models
├── public/css/         # Stylesheets
└── views/               # EJS templates (home, compose, post, about, contact)
```

---

I have created this miniproject to learn the techstack used in this project.

<div align="right">
  <img src="https://img.shields.io/badge/Completion-100%25-blue.svg" />
  <a href="https://github.com/Hsins-TIL/udemy_jQuery-Todo-List/blob/master/LICENSE" alt="License">
    <img src="https://img.shields.io/github/license/Hsins-TIL/udemy_jQuery-Todo-List.svg" />
  </a>
</div>

# Udemy Project: jQuery Todo-List

This is a hands-on project from the Udemy course - [The Advanced Web Developer Bootcamp](https://www.udemy.com/the-advanced-web-developer-bootcamp/) by Colt Steele. You can find the refactered with MERN stack version [here](https://github.com/Hsins-TIL/udemy_MERN-Todo-List).
  
# Demo

<div align="center">
  <img src="demo/demo.gif" />
</div>

You can see a complete working example [here](https://hsins-jquery-todolist.herokuapp.com/). Or you can run the demo on your local machine, please follow the instructions in [Getting Started](#getting-started).

# Features

- A simple todo-list app using jQuery, Express.js and Node.js
- RESTful API:

```
-------------------------------------------------------------------------
Todos Route
-------------------------------------------------------------------------
[Method]  [Route]
GET       /api/todos              Fetch all todos
POST      /api/todos              Create a new todo
GET       /api/todos/:id          Fetch a todo status
POST      /api/todos/:id          Toggle (complete or not) a task
PATCH     /api/todos/:id          Update the todo content
DELETE    /api/todos/:id          Delete todo
```

# Technologies

## Frontend

- [jQuery](https://jquery.com/)

## Backend 

- [nodejs](https://nodejs.org/en/)
- [express](https://gulpjs.com/)
- [mongodb](https://webpack.js.org/concepts/)

Check [`package.json`](https://github.com/Hsins/udemy_jQuery-Todo-List/blob/master/package.json) file for more information.

# Getting Started

Follow the instructions below to set up the environment and run this project on your local machine. Note that you should setup your MongoDB Atlas Cluster first to get your database. You can find the [Quick Note](https://hackmd.io/@Hsins/r1oFNI864) here.

1. Clone this repository.

```bash
# Clone repository
$ git clone https://github.com/Hsins/udemy_jQuery-Todo-List.git
```

2. Install dependencies via NPM or Yarn

```bash
# Install dependencies via npm
$ npm install
$ cd client
$ npm install
$ cd ..

# Install dependencies via yarn
$ yarn install
$ cd client
$ yarn install
$ cd ..
```

3. Run the server.

```bash
# Run server
$ npm run server
```

# More Information

All the notes I took in [Markdown](https://daringfireball.net/projects/markdown/syntax) (.md) format. You can find them in my [Udemy-Notes](https://github.com/Hsins/Udemy-Notes) repository. The note for this course is [here](https://hsins.github.io/Udemy-Notes/The%20Advanced%20Web%20Developer%20Bootcamp/).

# License

Licensed under the MIT License, Copyright © 2017-present Hsins.

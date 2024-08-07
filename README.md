# To-Do-List

This project is a simple To-Do List application by [AR7](https://arvinrezaei.com/). It allows users to add, mark, and delete tasks. The application is built using HTML, CSS, and JavaScript.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Demo

You can view the live demo of the project [here](https://todolist-ar7.netlify.app/).

## Features

- Add tasks
- Mark tasks as completed
- Delete tasks
- Data persistence using localStorage

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/ThisIsAR7/To-Do-List.git
    ```
2. Navigate to the project directory:
    ```sh
    cd To-Do-List-main
    ```
3. Open `index.html` in your web browser to view the To-Do List application.

## Usage

1. Open the `index.html` file in a web browser.
2. Add a task by typing in the input box and clicking the "Add" button.
3. Mark a task as completed by clicking on the task.
4. Delete a task by clicking on the "×" button next to the task.

## LocalStorage

The tasks are saved in the browser's localStorage. This allows the tasks to persist even after the browser is closed.

## Code Overview

### HTML (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="container">
        <div class="todo-app">
            <h2>To-Do List<img src="css/img/icons/check-list.png"></h2>
            <div class="row">
                <input type="text" id="input-box" placeholder="Add Your Text">
                <button onclick="addTask()">Add</button>
            </div>
            <ul id="list-container"></ul>
            <p>Developed and Designed By <a href="https://ar123456.netlify.app">AR7</a></p>
        </div>
    </div>
<script src="js/script.js"></script>
</body>
</html>
```

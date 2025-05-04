# MWAD-EX_03-To-Do-List-using-JavaScript
## Date:

## AIM
To create a To-do Application with all features using JavaScript.

## ALGORITHM
### STEP 1
Build the HTML structure (index.html).

### STEP 2
Style the App (style.css).

### STEP 3
Plan the features the To-Do App should have.

### STEP 4
Create a To-do application using Javascript.

### STEP 5
Add functionalities.

### STEP 6
Test the App.

### STEP 7
Open the HTML file in a browser to check layout and functionality.

### STEP 8
Fix styling issues and refine content placement.

### STEP 9
Deploy the website.

### STEP 10
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Todo App</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="todo-container">
    <h1>Todo List</h1>
    <input type="text" id="task-input" placeholder="Enter a task..." />
    <button id="add-task">Add Task</button>
    <ul id="task-list"></ul>
  </div>
  <script src="script.js"></script>
</body>
</html>
/* Add to or replace existing App.css */

.todo-container {
    max-width: 500px;
    margin: 60px auto;
    padding: 30px;
    background: #ffffff;
    border-radius: 12px;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  
  input[type="text"] {
    width: 65%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-size: 16px;
  }
  
  button {
    padding: 10px 12px;
    margin-left: 5px;
    background-color: #4caf50;
    color: white;
    border: none;
    border-radius: 6px;
    font-size: 14px;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  button:hover {
    background-color: #45a049;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
    margin-top: 25px;
  }
  
  li {
    background: #f9f9f9;
    margin-bottom: 12px;
    padding: 15px;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .completed {
    text-decoration: line-through;
    color: #888;
  }
  
  .actions {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  .status {
    font-weight: bold;
    color: #333;
  }
  
```


## OUTPUT
![image](https://github.com/user-attachments/assets/fb16952e-675a-4721-96b9-f46e285e665b)





## RESULT
The program for creating To-do list using JavaScript is executed successfully.

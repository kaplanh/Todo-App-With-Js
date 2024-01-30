# Todo App

![Checkout App]()


[Click Me!]()

## Description

The project aims to create a Todo App using JS and Css.

## Problem Statement

- Your company has recently started on a project that aims to create a Todo App. So you and your colleagues have started to work on the project.

## Project Skeleton 

```
Todo App (folder)
|
|----readme.md                        
|----index.html
|----style.css
|----app.js
|----app_localStorage.js 
``` 


### At the end of the project, the following topics are to be covered;

- HTML
  - nth-child()
   ```
    ul li:nth-child(even) {
    background: #dde6f5;
  }
   
  ```
- CSS
  - overflow 
  - @media query

 ```
@media screen and (max-width: 576px) {
    li p {
        font-size: 0.8rem;
    }
}
  ```
  
  
- JS
  - DOM Manipulations
    - innerHTML
    - innerText
    - textContent
     
  - DOM Selectors
  - querySelector
  - querySelectorAll
  - const productList = document.querySelector("div.main__product-painel"); //?basina div yazarak belirtirsek performans acisindan daha hizli olur
    
  - Events
    - click
    - load
    - keydown
  
    ```
        todoInput.addEventListener("keydown", (e) => {
    if (e.key === "Enter") {
        btn.click();
    }
    })
    ```
  - Capturing & Bubbling
  - DOM Traversing
    - nextElementSibling
    - nextElementSibling
    - e.target.closest(".main__product-info")
    - if (e.target.classList.contains("fa-plus"))
    - e.target.previousElementSibling.innerText++;
    - firstElementChild
    - children
   
  - localStorage 
    ```
     - localStorage.setItem("todos", JSON.stringify(todos));
 
     - let todos = JSON.parse(localStorage.getItem("todos")) || [];
     
    ```
 
 
 
  
  - Array Methods
  - forEach() & map()
     ```

     function renderSavedTodos() {
    todos.forEach((todo) => {
        createListElement(todo);
    });
    }
     todos.map((todo, index) => {
            if (todo.id == id) {
                todos[index].isDone = !todos[index].isDone;
            }
        });
    ```
  

  
  - if else - if - else  conditions


### At the end of the project, developers will be able to;

- improve coding skills within HTML, CSS and JS 

- use git commands (push, pull, commit, add etc.) and Github as a Version Control System.


## Notes

- You can use HTML, CSS and JS to complete this project.



<p align="center"> ⌛<strong> Happy Coding </strong> ✍ </p>




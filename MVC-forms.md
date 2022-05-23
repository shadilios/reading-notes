[Main Readme](https://github.com/shadilios/reading-notes/blob/main/README.md)  

# MVC

![image](https://cdn.educba.com/academy/wp-content/uploads/2019/03/What-is-MVC-1.png)


<br><hr><br>

### What is a View?

A view is a .cshtml file that communicates with both the controller & the model to render a page & send input to the server.

<br><hr><br>

### How is a view used?

1. Each controller in our project should have a folder named after it that will hold all the views related to it.  
2. Each View folder contains .cshtml files that represent the main elements (webpages) in our View.
3. An example of this is a Welcome view folder that represents a Welcome controller, that holds 2 .cshtml files inside. Each of these files can represent a different webpage, ex: (Info, Contact, About....etc).  


![img](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/overview/_static/views_solution_explorer.png?view=aspnetcore-6.0)

<br><hr><br>

### Why use views?

1. Apps are easier to maintain.
2. "Loosley coupled": You don't have to access/interact with the business logic nor the data to be able to create or edit the views.
3. Easer to test UI.
4. Organized better hence less likely to duplicate code.

<br><hr><br>

### View discovery

A process that takes places after an action returns a view to determine which view file is used.

<br><hr><br>

### Ways to create MVC forms:
1. Weakly typed: The easiest and quickest way to create forms in MVC.
2. Strongly typed: We send objects instead of attributes.
3. Strong typed AJAX: Send data back to the controller.
4. Html, Ajax & Jquery: Ability to use html tags.






# To Do API

This tutorial teaches the basics of building a web API with ASP.NET Core.

In this tutorial, you learn how to:

Create a web API project.
Add a model class and a database context.
Scaffold a controller with CRUD methods.
Configure routing, URL paths, and return values.
Call the web API with Postman.
At the end, you have a web API that can manage "to-do" items stored in a database.

Overview
This tutorial creates the following API:

OVERVIEW
API	Description	Request body	Response body
GET /api/TodoItems	Get all to-do items	None	Array of to-do items
GET /api/TodoItems/{id}	Get an item by ID	None	To-do item
POST /api/TodoItems	Add a new item	To-do item	To-do item
PUT /api/TodoItems/{id}	Update an existing item  	To-do item	None
DELETE /api/TodoItems/{id}    	Delete an item    	None	None

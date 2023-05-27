<h1>SliceAPI</h1> 

## Project description

<p align="justify">
SliceAPI is a lightweight and user-friendly Pizza Management API that allows you to effortlessly handle a collection of pizzas through simple HTTP requests. It provides essential CRUD (Create, Read, Update, Delete) operations, giving you full control over your pizza data.

The project uses ASP.NET Core and follows the RESTful API conventions.
Swagger/OpenAPI is integrated into the project for API documentation and exploration. You can access the Swagger UI at /swagger when running the API in the development environment.
</p>

## API Endpoints

<p align="justify">
Get all pizzas

    URL: /Pizza
    Method: GET
    Response: Returns a list of all pizzas.

Get a pizza by ID

    URL: /Pizza/{id}
    Method: GET
    Parameters: id - The ID of the pizza.
    Response: Returns the pizza with the specified ID.

Create a new pizza

    URL: /Pizza
    Method: POST
    Request Body: JSON object representing the new pizza.
    Response: Returns the created pizza with a generated ID.

Update a pizza

    URL: /Pizza/{id}
    Method: PUT
    Parameters: id - The ID of the pizza to update.
    Request Body: JSON object representing the updated pizza.
    Response: Returns no content if the update is successful.

Delete a pizza

    URL: /Pizza/{id}
    Method: DELETE
    Parameters: id - The ID of the pizza to delete.
    Response: Returns no content if the deletion is successful.
</p>

## Technologies Used :books:

- [C#]
- [ASP.NET Core]

Copyright :copyright: 2023 - SliceAPI

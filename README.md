# eTickets

This is an eCommerce application with ASP.NET MVC and Entity Framework Core that allows a customer with user role to purchase movie tickets using authentication (Asp.Net Identity). 
The users with admin role could manage actors, producers, theaters and movies.

## eTickets Description

The eTickets project is a web application developed using Visual Studio 2022, ASP.Net Core 6.0 MVC, Entity Framework Core (Code-First), Asp.Net Identity Framework and Sql Server for data persistence. 

It also uses Bootstrap/jQuery to improve display. 

The customers with user role could purchase movie tickets. 

The users with admin role could manage actors, producers, theaters and movies.

## Prerequisites

Before starting this project, make sure you have installed Visual Studio 2022.

## Install

1. Clone this repository on your local machine:

   git clone https://github.com/boumhamdifatima/eTickets-AspNet-MVC-eCommerce-Application.git

2. Import the project into your IDE.

3. Configure your database by modifying the `ConnectionStrings` in appsettings.json file to add your database connection information.

4. run the "update-database" command in the package manager console

5. Run the application.


## Features

### Authentication and authorization
This feature allows the user to register and log in/out.
There are two roles: user for clients and admin for the administrator.
Authorization management is based on the two previous roles.


### Customer Features
browse movie list
view the details of a film
Add/remove a movie ticket to cart
View cart items
Place an order using a Paypal payment.
View a customer's order list.

### Fonctionnalités pour l'admin
Visualisertous utilisateurs
Gérer les acteurs(ajouter, visualiser, modifier et supprimer)
Gérer les producteurs(ajouter, visualiser, modifier et supprimer)
Gerer les cinémas(ajouter, visualiser, modifier et supprimer)
Gérer les films(ajouter, visualiser, modifier et supprimer)

## Contribute

If you would like to contribute to this project, please follow these steps:

   Fork the project
   
   Create a new branch (git checkout -b feature/new-feature)
   
   Make changes and add features
   
   Commit changes (git commit -am 'Add new feature')
   
   Push changes to the branch (git push origin feature/new-feature)
   
   Create a new Pull Request 

## Author 

Fatima Boumhamdi - @FatimaBoumhamdi 

## License 

This project is licensed under the MIT License - see the LICENSE file for details.

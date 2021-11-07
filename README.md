# Factory

### By Nick Hennessy

## Technologies Used

* C#
* .NET 5.0
* ASP.NET Core MVC
* Swagger
* Entity Framework Core

## DescriptionParksLookup
This is an API for looking up state and national parks.

## Setup and Installation
* Clone this repository and open in your favorite text editor
* Navigate to ParksLookup.Solution/ParksLookup
* Create the file ParksLookup/appsettings.json and add the following code:
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=parks_lookup;uid=root;pwd=[your password];"
  }
}
* Replace [your password] with your mysql password
* Run the command dotnet restore to install all necessary packages
* Run the command dotnet ef database update to create the database from the Migrations folder
* In the terminal, run the commands dotnet build, then dotnet run
## Swagger
The Swagger interface will be visible at localhost:5001 when the application is run. This will enable you to interact with the get, post, put, and delete endpoints.
## Known Bugs
None
## License
MIT LICENSE
Copyright (c) 2021 Nick Hennessy

## Contact Information
njhnny@gmail.com
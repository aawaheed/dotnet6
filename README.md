# Commands used:
## Scaffold a project
`` dotnet new web -o PizzaStore ``
## Add swagger
`` dotnet add package Swashbuckle.AspNetCore --version 6.2.3``
## Add EF Core for InMemory
`` dotnet add package Microsoft.EntityFrameworkCore.InMemory --version 6.0 ``
## Add EF Core for SQLite
`` dotnet add package Microsoft.EntityFrameworkCore.Sqlite --version 6.0 ``
## Add EF Core Design Package
``  dotnet add package Microsoft.EntityFrameworkCore.Design --version 6.0  ``
## Install EF Core Tools globally
`` dotnet tool install --global dotnet-ef ``
## or alternatively install in the project
`` dotnet new tool-manifest ``
`` dotnet tool install  dotnet-ef ``


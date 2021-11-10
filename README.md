# MovieApp
* A movie web app developed with ASP.NET Core 6 with the MVC pattern<br/>
* Database used is SqlServer with the ORM Entity Framework<br/>
[ASP.NET Core MVC Tutorial](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-6.0&tabs=visual-studio "Microsoft ASP.NET Core MVC")

### Dependencies
In the Package Manager Console (PMC), enter the following commands:
```
Install-Package Microsoft.EntityFrameworkCore.Design -IncludePrerelease
Install-Package Microsoft.EntityFrameworkCore.SqlServer -IncludePrerelease
```
<br/>To create the database with EF Core, use the commands (PMC):
```
Update-Database
```
# ASP.NET Core MVC – Movies App
 
A movie management web application built while learning **ASP.NET Core MVC**, based on the official Microsoft tutorial.
 
## Features
 
- Full CRUD for movies (create, view, edit, delete)
- Search movies by title
- Filter movies by genre (dropdown)
- Server-side and client-side validation using Data Annotations
- CSRF protection with anti-forgery tokens
- Post-Redirect-Get (PRG) pattern after form submissions
## Tech Stack
 
- C# / .NET
- ASP.NET Core MVC
- Entity Framework Core (Code First, Migrations)
- SQL Server LocalDB
- Razor Views, Tag Helpers
- Bootstrap
## Project Structure
 
```
Controllers/   – request handling (MoviesController, HomeController)
Models/        – Movie entity and MovieGenreViewModel
Views/         – Razor views and shared layout
Data/          – EF Core DbContext
Migrations/    – database schema migrations
```

## Key Concepts Practiced
 
- Conventional routing (`{controller}/{action}/{id?}`)
- Model binding and `ModelState` validation
- ViewModels and over-posting protection
- LINQ queries with deferred execution
- Async database operations with EF Core

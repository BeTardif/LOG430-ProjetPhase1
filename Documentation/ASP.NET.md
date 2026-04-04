# Notes ASP.NET 
### Lexique
* DI IoC Container configuration: DI ==> Dependency inversion; IoC => Inversion of control: 
Un patron de conception commun par lequel la dépendences à une logique est délegué à un framework externe au code. Fondement du framework ASP.Net Core, on délègue la logique au framwork.
https://medium.com/@a.ihsan.elmas/inversion-of-control-ioc-ioc-containers-dependency-injection-di-dependency-inversion-e9d52b3a8980

**Fondement de n'importe quelle application ASP.NET Web API**
```
var builder  = WebApplication.CreateBuilder(args);

// IoC Container Configuration (BlackBox principle)
// This is where we add the controllers, services and such.

var app = builder.Build();

// Middleware configuration
// This is where we add the logic and steps for the different end points.
// Maps the controllers

app.Run();
```

* EF Core (Entity Framework Core): 
    ORM facilitant l'intégration de code SQL dans C#


* Middleware: 

* ORM (Object-Relational Mapper): Permet d'intéragir avec du code SQL avec un logic C#

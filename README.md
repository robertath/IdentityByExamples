# identity-aspnetcore
* This repo contains the source code for "Identity in ASP.NET Core"
* Examples of account controller to process the features:
	* Account with 2FA for, Authentication confirmed by email, Logout, Forgot and Reset Passoword


### To `FilmesAPI` project only:

###### Libraries
* Microsoft.AspNetCore.Identity.EntityFrameworkCore
* AutoMapper.Extensions.Microsoft.DependencyInjection
* Microsoft.EntityFrameworkCore
* Microsoft.EntityFrameworkCore.SqlServer
* Microsoft.EntityFrameworkCore.Tools
* Microsoft.Extensions.Logging.Debug
* Microsoft.VisualStudio.Web.CodeGeneration.Design

###### To run application use:
* SqlServer > database IdentityByExamplesDB
* Email> email to manage account authorizations

###### If EF migrations don't exist, create:
```
add-migration "Initial"
```

###### Set migration on database
```
update-database
```



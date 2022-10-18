# identity-aspnetcore
* This repo contains the source code for "Identity in ASP.NET Core"
* Examples of account controller to process the features:
	* Account with 2FA for, Authentication confirmed by email, Logout, Forgot and Reset Passoword


### To `IdentityByExamples` project only:

###### Libraries
* Microsoft.AspNetCore.Identity.EntityFrameworkCore Version="3.1.30"
* AutoMapper.Extensions.Microsoft.DependencyInjection Version="7.0.0"
* Microsoft.EntityFrameworkCore Version="3.1.30"
* Microsoft.EntityFrameworkCore.SqlServer Version="3.1.30"
* Microsoft.EntityFrameworkCore.Tools Version="3.1.30"
* Microsoft.Extensions.Logging.Debug Version="3.1.30"
* Microsoft.VisualStudio.Web.CodeGeneration.Design Version="3.1.4"

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


### To `Email service` project only:
* Service to manage token sends by email

#### Libraries
Microsoft.AspNetCore.Http.Features Version="3.1.30" />
NETCore.MailKit Version="2.0.2" />
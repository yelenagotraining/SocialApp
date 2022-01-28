### To run the program locally
* Clone repo
* execute `dotnet watch run`

### Setting up development environment
* install dotnet core
* install visual studio code
* install node via nvm 
    - [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm)
    - `nvm install lts` or `nvm install [version]`

### Project Setup
* adding a solution file uisng dotnet cli
    - `dotnet new sln`
* creating new project using dotnet cli
    -  `dotnet new webapi -o API'
* add API to the sln file
    - `dotnet sln add API/`

### Set up VS Code
#### Install
* C#
* C# Extensions
* Material 
* Nuget Gallery to install packages
    - Open command pallet and  typing nuget

* Install entity framework, entity framework sql server package
* Create a DbContext class
* Install dotnet ef tools cli
    - `dotnet tool install --global dotnet-ef --version 6.0.1`
* using dotnet ef cli
    * dotnet ef migrations add InitialCreate -o Data/Migrations
    * dotnet ef database update

* dotnet dev-certs https --trust
* npm install -g @angular/cli@12
* ng new client --strict false
* ng serve
* ng add ngx-bootstrap

### Adding the create token logic
Install System.Identity.Models.Token.JWT
In the concrete implimentation of the TokenService include SymmeticSecurityKey 
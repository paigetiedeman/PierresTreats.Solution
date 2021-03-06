<div align="center">

[![Language][language-shield]][language-url]
[![Language][languageH-shield]][languageH-url]
[![Language][languageC-shield]][languageC-url]
[![MIT License][license-shield]][license-url]

<img src="PierresTreats/wwwroot/img/title.png">

#### _By Paige Tiedeman_

#### This is a C# web application that uses MySQL database to store a many to many relationship for Pierre's Bakery.

<br>
 
</div>

## Technologies Used

* C#
* .NET v5.0
* ASP.NET Core MVC
* HTML 
* Bootstrap
* MySQL
* CSS
* MySQL Workbench
* Razor
* Entity FrameworkCore
* .NET Core CLI
* Identity 

## Description

This web application stores Treats and Flavors and connects the Treats to specific flavors using routing techniques. Users have to log in to access Treats

## Installation Requirements

* _Clone or download the zip file of this repository to your desktop_
* _Navigate into the top level directory_
* _Open in your code editor_
* _Commit and push your .gitignore file to your repo_
* _Add the file PierresTreats.Solution/PierresTreats/appsettings.json and insert the following:_
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=paige_tiedeman;uid=[YOUR-UID];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```
* _Insert your MySQL password and user Id_
* _Make sure to have .NET 5.0 installed_
* _Run `$ dotnet restore` to install bin & obj folders_
* _Make sure to have dotnet ef installed globally_


## Steps To Use
* _In your terminal navigate into PierresTreats.Solution/PierresTreats_
* _If Migrations folder is not present run `$ dotnet ef migrations add Initial` to add Migrations folder_
* _Run `$ dotnet ef migrations add addIdentity` and `$ dotnet ef migrations add Authorization`_
* _Then run `$ dotnet ef database update` to create the schema_
* _Run `$ dotnet build` to build the site_
* _Run `$ dotnet run` to start the live server_
* _Click either button to see all Flavors or Treats_
* _After clicking add  put in your inputs and hit submit to reveal the lists!_

## User Stories

<details>
<summary> As A User..</summary>

* I can register, log in and log out with my credentials created.
* I can view Flavors and treats they are linked to
* I can create, view, edit and delete flavors when not logged in.
* I can only view Treats if logged in.
* Logged in I can edit, create, delete and save Treats.

</details>

## Known Bugs

* _N/A_

## License

MIT: See Badge at top for Info
Copyright (c) 2021 Paige Tiedeman

## Contact Information

_Paige Tiedeman @ github.com/paigetiedeman_  

[license-shield]: https://img.shields.io/badge/License-MIT-blue
[license-url]: https://opensource.org/licenses/MIT
[language-shield]: https://img.shields.io/badge/Language-C%23-green
[language-url]: https://docs.microsoft.com/en-us/dotnet/csharp/
[LanguageH-shield]: https://img.shields.io/badge/Language-HTML-red
[LanguageH-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[LanguageC-shield]: https://img.shields.io/badge/Language-CSS-blueviolet
[LanguageC-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
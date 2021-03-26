# _Pierre's Sweet and Savory Treats_
### An independent project for Epicodus

#### _A program that will help patissier Pierre organize his treats._

#### By Dani Renner

## Technologies Used

* _C#_
* _.NET 5.0.102_
* _ASP.NET Core Mvc 4.8_
* _MySQL_
* _Razor_
* _Entity Framework Core_
* _Git_

## Description

_This application creates a database to hold treats and flavors with a many-to-many relationship. One can register for an account and log in to create, update, or delete flavors. All users including guests can see all of Pierre's treats and their corresponding flavors._

## Setup/Installation Requirements

* You can clone the repository to your desktop
* Open a SQL command line in a terminal. Copy and paste the contents of dani_renner.sql and hit enter.
* Quit out of SQL with Ctrl + c
* Navigate to the PierresTreats directory
* Add a file called appsettings.json with the command 'touch appsettings.json'. In that file, you will need to add the following code:
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[dani_renner];uid=root;pwd=password;"
  }
}
* (The 'password' is only necessary if you have a password for your MySQL)
* Save
* Enter "dotnet run" in the terminal and hit enter to start a local host. 
* Ctrl + click the link that populates in the terminal to view the application in the webpage. It is probably http://localhost:5000/
* Use Ctrl + C in the terminal to quit the host and close out of the window in the browser.

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright © 2021 Dani Renner

All Rights Reserved

## Contact Information

_Dani Renner (danijrenner@gmail.com)_

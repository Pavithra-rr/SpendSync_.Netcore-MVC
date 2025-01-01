# SpendSync
It's Web Application which help users to track their money whether it's expenses or incomes. Using ASP.NET Core 6 (Razor Pages) and Synfusion library (Front-End),
This application was able to give great "Data visualization" for the saved records (Expenses & Incomes).

## Content
* [Description](#description)
* [Technologies Used](#technologies-used)
* [Business Logic](business-logic)

## Description
It's Web Application which help users to track their money whether it's expenses or incomes. Using ASP.NET Core 6 (Razor Pages) and Synfusion library (Front-End),
This application was able to give great `Data visualization` for the saved records (Expenses & Incomes). This Application was built with ASP.NET Core 6 and EF core 6
(using visual studio code) and Code First design.

## Technologies Used
As said earlier, this app was built with `ASP.NET Core 6` which is compatible on all operating platforms (linux/Mac/Windows), also EF Core is used which stands for
 `Entity Framework core 6 (Code First principle)`. For database management, we used `SQL Server` which is supported by Microsoft.

## Business Logic
### Tables:
* ##### Categories
which was responsible for storing categories of incomes and expenses user made.
* ##### Transactions
which was responsible for storing transactions made by users through categories we previously mentioned.
##Sample Screenshots
![image](https://github.com/user-attachments/assets/5d28f69d-52b6-47de-9d0d-31e2ee6fe8ca)
![image](https://github.com/user-attachments/assets/aa4dea20-8811-4737-a30e-dbfb39fa3bdd)

![image](https://github.com/user-attachments/assets/b0346e51-7c7c-4909-806c-bc51687723a7)

## Installation :
dotnet add package -v 6.0.24 Microsoft.EntityFrameworkCore
dotnet add package -v 6.0.24 Microsoft.EntityFrameworkCore.Tools
dotnet add package -v 6.0.24 Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Syncfusion.EJ2.AspNet.Core --version 24.1.43
## Run/Create SQL Database
Add-Migration InitialCreate
Update-Database


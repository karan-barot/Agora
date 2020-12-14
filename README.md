# Agora
This is amn E-commerce website created by

- Karan Barot
- Adit Patel
- Nisarg Shah

as final project for the course ASP.NET 

## installation
unzip the folder **Final** and open the solution in visual studio **Final.sln**
generate the dummy database in SSMS give it ant name and run the script file attached in zip folder **script.sql**

```sql
create database demo
```
then run the script **script.sql**

### changing web.config in solution

We need to change the connection sttring in order to connect this newly created database 
```xml
<connectionStrings><add name="DbEntities" connectionString="metadata=res://*/Models.Model1.csdl|res://*/Models.Model1.ssdl|res://*/Models.Model1.msl;provider=System.Data.SqlClient;provider connection string=&quot;data source=DESKTOP-KHESJ82;initial catalog=Db;integrated security=True;MultipleActiveResultSets=True;App=EntityFramework&quot;" providerName="System.Data.EntityClient" /></connectionStrings>
```
in data source  put name of your database

And we are ready to run the project

## Software Specification

- Visual Studio -2019
- .Net Framework 4.8
- Mvc Framework 5
- Entity Framework 3.0
## Database Specification
- SSMS-2019
- SQL Server 2019

## Design Technologies
- CSS
- HTML
- Boot Strap
- Jquery (3.5.1) 
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js" integrity="sha512-bLT0Qm9VnAYZDflyKcBaQ2gg0hSYNQrJ8RilYldYQ1FxQYoCLtUjuuRuZo+fjqhx/qtq/1itJ0C2ejDxltZVFg==" crossorigin="anonymous"></script>
```
- Toastr.js
- AOS libraries
- Jquery Ajax

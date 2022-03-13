# Hair Salon

#### Created by Christen Weston

#### This project let you track your stylists and their clients

## Technologies Used

* Git
* C#
* .NET 5.0
* MVC
* Razor
* Entity
* CSS
* SQL

## Setup Installation Requirements

1. Clone the HairSalon repository
2. Open in your favorite IDE
3. CD into HairSalon
4. Ensure MySql workbench is installed on your machine. If needed, please visit this site to download and install: [MySQLWorkBench]("https://www.mysql.com/products/workbench/")

5. Import the christen_weston.sql file into MySql Workbench:
- Save the file to your desktop
- In the Navigator > Administration window, select Data Import/Restore.
- In Import Options select Import from Self-Contained File.
- Navigate to the sql file you just saved to your desktop.
- Under Default Schema to be Imported To, select the New button.
- Enter the name of your database and remember this name for your appsettings.json file.
- Click Ok.
- Navigate to the tab called Import Progress and click Start Import at the bottom right corner of the window.
- After you are finished with the above steps, reopen the Navigator > Schemas tab. Right click and select Refresh All. The database will appear.

6. Create an appsettings.json
7. Add the following to your appsettings.json replacing the ```[YourDataBaseNameHere]``` and ```[YourPasswordHere]``` with your Database name and your password:
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[YourDataBaseNameHere];uid=root;pwd=[YourPasswordHere];"
  }
}
```
8. run "dotnet build"
9. run "dotnet run" to use the program
10. Enjoy!

# Known Bugs
None

## Date Published
March 2022

## License Info
[MIT License](https://opensource.org/licenses/MIT)
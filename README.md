**Dr. Sillystringz Factory**

#### By **Nathan Conn**

#### This program was designed specifically for Dr. Sillystringz Factory for the purpose of keeping a record of engineers hired and machines in factory.


## Technologies Used

* C#
* NET 5.0
* MVC
* MS Testing



## Description

Dr. Sillystringz needed an application to help him keep track of engineers and machines, and to determine which engineer should be responsible for work on which machine.

## Setup/Installation Requirements

* Clone repository.
* In the command line, run "dotnet restore" in the Salon directory.
* In the command line, run "dotnet build" in  the Salon and directory.
* In the command line, run "dotnet run" while in the Salon directory to run the program.
* You will need to create an appsettings.json file in order to use and store information into the database that is attached. Use the code below and replace the necessary fields with your information:

{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=DBNAMEHERE;uid=root;pwd=PASSWORDHERE;"
    }
}

* In the command line, run "dotnet ef migrations add Initial" (and label each one different with any update you make)
* In the command line, run "dotnet ef database update"


## Known Bugs

*The index page for machines does not seem to want to load, and there is a data error with EngineerID I will need to solve.

## Contact Me

Let me know if you run into any issues or have questions, ideas, or concerns:
nconn34@gmail.com

## License

Copyright (c) 3/26/2022 Nathan Conn.
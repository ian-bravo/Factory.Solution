
# _Dr. Sillystringz's Factory_

#### By _**Ian Bravo**_

#### _This web application will allow Dr. Sillystringz to manage their employees (Engineers) and their equipment (Machines) in an easy to use web application!_

## Technologies Used

* _C# 10.0_
* _HtmL_
* _css_
* _Bootstrap_
* _.Net 6.0_
* _ASP.NET Core MVC 6.0_
* _Entity Framework Core_
* _MySQL Community Server_


## Description

This C# web application will allow Dr. Sillystringz to view their employees (Engineers) and equipment (Machines). Dr. Sillystringz will be able to add/edit/delete both Engineers and Machines according to their staffing needs. Dr. Sillystringz can select a specific Engineer to view their Name along with the Machines they are assigned to. Dr. Sillystringz can also select a Machine to view it's Name and which Engineers are assigned to it. Dr. Sillystringz can view all Engineers and Machines on their Home page.

## Setup/Installation Requirements

Installing/Configuring MySQL:

1. Follow the instructions on this <a href="https://full-time-pre-october.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql">page</a> for installing and configuring MySQL.


Installing dotnet-ef:
1. Run the following command to globally install dotnet-ef tools which will allow you to create migrations and create databases:    
   `$ dotnet tool install --global dotnet-ef --version 6.0.0`

Cloning the Repo:
1. Open the terminal.
2. Change your directory to where you would want the cloned directory.
3. Input the following command into your terminal:  
 `$ git clone https://github.com/ian-bravo/Factory.Solution.git`
4. Using the terminal, navigate to the production directory: "Factory" and create a new file called appsettings.json
5. Within appsettings.json, put in the following code while also replacing the following values with your own values as shown in the code snippet below:
```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-DB-NAME];uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```
* [YOUR-USERNAME-HERE] with your username
* [YOUR-PASSWORD-HERE] with your password
* [YOUR-DB-NAME] with the name of your database

Running the program:
1. Navigate to the project's production directory "Factory" using the terminal.
2. Run the following command to update the database:    
  `$ dotnet ef database update`
3. Within the command line, run the command `$ dotnet watch run` to compile and execute the console application in developer mode.

## Schema

<img src="Factory_Schema.png" alt="schema">

## Known Bugs

* _No known bugs_

## License

MIT License  

Copyright (c) 13-Oct-2023 Ian Bravo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

_For questions or concerns, please email me at bravo.ian@gmail.com_
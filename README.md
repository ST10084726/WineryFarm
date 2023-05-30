# WineryFarm
Develop a Prototype Web Application 
# Winery Farm Website - Harvest Haven Vineyards
The website will have to capture lots of data on the spot
### Introduction
Welcome to the POE2 Winery Farm project! This web application is designed to showcase and manage a winery farm, providing a platform to display information about the farm, its wines, and allowing users to browse and search for wines. Users can also create accounts, manage their profiles, and administrators have access to a management interface for wines, categories, and user accounts.

This project aims to demonstrate the use of ASP.NET Core MVC framework to develop a dynamic web application. It incorporates essential features such as data modeling, routing, views, controllers, and user authentication. By exploring the codebase and running the application locally, you can gain insights into building scalable and interactive web applications using ASP.NET Core.

Feel free to clone the repository, explore the code, and contribute to the project by submitting bug reports, feature requests, or pull requests. Your contributions are highly appreciated

## Installation
1) Download [Visual Studio][https://visualstudio.microsoft.com/]:Version 17.0
2) C# -Language the project is coded in
3) Git bash - A terminal to make the use of git for version control

## Technologies used in the project
- .NET Framework: version 4.7.2
- .NET 6.0(Long-Term Support)
- ASP.NET Core Web App(Model-View-Controller)

## Software Specs
- Visual Studio 2022
- Git version no: 2.36.1
- ML.NET Model Builder
- .NET Framework

## Run the Project
* Download Visual Studio using the link above
* Download the file name "POE2" onto your desktop
* Open the file on Visual Studio
* Either press F5 or above the button Run to start the program
* The website will run on your local chrome/firefox/microsoft egde
* Users will have to register first by filling in their details then logging onto the website
* Fill in your details and the program will begin running and processing the info you have entered

## Project Features 
1) Winery Farm Information: The application provides an overview of the winery farm, including its history, mission, and values.
2) Wine Categories: Different categories of wines are showcased, allowing users to explore wines based on their preferences.
3) User Accounts: Users can create accounts, log in, and manage their profiles, enabling personalized experiences.
4) Administrative Interface: Administrators have access to a management interface to handle wines, categories, and user accounts efficiently.

## Project Structure
The project follows the standard structure of an ASP.NET Core MVC application, with key directories and files:
- Controllers/: Contains the controller classes that handle requests and define actions.
- Models/: Includes the data models used in the application.
- Views/: Contains the CSHTML files responsible for rendering the user interface.
- wwwroot/: Holds static files such as CSS, JavaScript, and images.
- Data/: Includes data access and database-related code.
- Services/: Contains additional services and utilities used in the application.
- Tests/: Includes unit tests for the project

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Kanban
[https://github.com/users/SyurenChetty/projects/7/views/1](https://github.com/users/ST10084726/projects/8/views/1?pane=issue&itemId=29432612)

## Code attribuation
-

## Troubleshooting
* Issue: Application fails to start or throws runtime errors:
1) Solution 1: Make sure you have the .NET 5 SDK installed on your machine. If not, download and install it, then try running the application again.
2) Solution 2: Ensure all the project dependencies are properly restored. Run the following command in the project directory:dotnet restore
3) Solution 3: Check the console output for any error messages or stack traces. Investigate the error details and refer to relevant documentation or online resources for potential solutions

* Issue: Incorrect or missing data in the application
1) Solution 1: Verify that the database has been properly set up and seeded with initial data. If necessary, run the database migration commands to create and populate the required tables: dotnet ef database update
2) Solution 2: Ensure that the data access code is functioning correctly. Review the data models, database context, and data services to ensure the data is retrieved and stored accurately.

* Issue: Styling or layout issues in the application
1) Solution 1: Double-check that all required CSS and JavaScript files are being properly loaded by the application. Inspect the network tab in the browser's developer tools to see if any resources are failing to load.
2) Solution 2: Review the CSS styles and layout definitions to ensure they are correctly applied to the appropriate HTML elements. Check for any conflicting styles or missing classes.

* Issue: User authentication and authorization problems
1) Solution 1: Ensure that the user authentication and authorization settings are properly configured. Review the authentication middleware, user role assignments, and access control rules to ensure they match the intended behavior.
2) Solution 2: Verify that user account creation, login, and profile management functions are working as expected. Check for any error messages or exceptions that might occur during these processes.

## FAQ
```bash
<br /> Q - Can you leave out some information when adding a module?
<br /> A - Yes, this project is built using ASP.NET Core, which is cross-platform and can be deployed to various web servers such as Microsoft IIS, Nginx, or Apache. Refer to the official documentation for instructions on deploying ASP.NET Core applications to your preferred web server

<br /> Q - How can I customize the design and layout of the application?
<br /> A - The project uses CSS styles and Razor syntax for rendering views. To customize the design, you can modify the existing CSS files in the wwwroot/css directory or create new CSS files. Additionally, you can modify the CSHTML files in the Views directory to change the layout, content, and structure of the pages

<br /> Q -  How can I add additional features or functionality to the project?
<br /> A - You can extend the project by adding new controllers, models, and views to implement new features. Start by creating a new controller to handle the desired functionality, define the necessary models, and create corresponding views. Additionally, you can modify existing controllers to add new actions or modify the data access layer to accommodate the new requirements.

```

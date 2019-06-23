# Base .NET Core Web App Template

A base .NET Core project template that scaffolds the structure of a web application enabling you to get started with web applications quickly.
The base web project template creates a .NET Core Web API with intent to be consumed by a separate web front-end. This base project will use Angular for the web front-end but can be switched out for React etc.

This project can be imported as a Visual Studio template for scaffolding for quick startup.

## Prerequisites
- .NET Core 2.2
- [EditorConfig](https://editorconfig.org/)
- IDE/Text editor (Recommended Visual Studio)

## Frameworks and Tools
- .NET Core 2.2
- [EditorConfig](https://editorconfig.org/)
- AutoMapper 

## Design Patterns
- [Clean architecture](https://docs.microsoft.com/en-us/dotnet/standard/modern-web-apps-azure-architecture/common-web-application-architectures#clean-architecture) 
- Dependency Injection
- SOLID principles 
- Root directory structure follows a [convention](https://gist.github.com/davidfowl/ed7564297c61fe9ab814) followed by Microsoft 

## Getting Started
TODO:

## How to export the Web App Template as a Visual Studio Template
1. Open this project in Visual Studio
2. Select Project > Export Template. This will open the Export Template Wizard
3. Select Project template and press Next.
4. Fill the appropriate details and press Finish. This will produce a Template project in the form of a .zip folder.
5. Move the .zip folder into the location: "%USERPROFILE%\Documents\<Visual Studio version>\Templates\ProjectTemplates". For example: C:\Users\john.doe\Documents\Visual Studio 2019\Templates\ProjectTemplates.
6. All done! This should now be available as a Visual Studio template and can be seen in the New Project dialog box in Visual Studio.

## How to use the Web App Template as a Visual Studio Template
1. Open Visual Studio
2. To find the template in the New Project dialog box in Visual Studio, expand Installed and then expand the category Visual C#. You will find the template at that location. Select the Template and enter the required specified fields. Press Ok to create the template.
3. Select Build > Clean in Visual Studio
4. Select Debug > Start Debugging (or press F5) to run the project in Debug mode. Select Debug > Start without Debugging (or press ctrl + F5) to run the project without Debug mode. 

## Future Plans
- Publish the web project template to Nuget

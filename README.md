# met-sim-version1-csharp-todo-api

## Setup

Follow this tutorial to create a Create a web API with ASP.NET Core.

https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-7.0&tabs=visual-studio-code

## Issues

We had to work around the Met's restrictions of not allowing users to install system wide software in the student Remote Desktop.
* We installed Visual Studio Code from the Microsoft Store.
* We installed .net7 using Microsoft's dotnet-install.ps1 script
* We created a batch file to ensure VSCode was not using old versions of dotnet.

```bat
set DOTNET_ROOT=C:\Users\<user>\AppData\Local\Microsoft\dotnet\
code
```

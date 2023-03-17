# met-sim-version1-csharp-todo-api

## Issues

We had to work around the Met's restrictions on not allowing users to install system wide software.
* We installed Visual Studio Code from the Microsoft Store.
* We installed .net7 using Microsoft's dotnet-install.ps1 script
* We created a batch file to ensure VSCode was not using old versions of dotnet.

```
set DOTNET_ROOT=C:\Users\CMatchett\AppData\Local\Microsoft\dotnet\
code
```

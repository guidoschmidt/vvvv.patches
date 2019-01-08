# Creating a C# vvvv plugin

### Manage packages (dependencies) vie [NuGet](https://www.nuget.org/)

- Dotnet packages can be managed using [NuGet](https://www.nuget.org/) package manager
- In *Visual Studio*, running build will auto-download all dependencies into a `packages` directory.

---
# Helpfull CLI commands

- `dotnet new sln` - Create a new solution file
- `dotnet sln add *.csproj` - Add an existing C# project file to the solution
- `dotnet restore` - Restores the dependencies and tools of a project.
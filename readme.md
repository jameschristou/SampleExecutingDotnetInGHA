# Example Running a Dotnet Application in Github Actions
This repo has an example showing how to execute a dotnet (.NET 8) application from within a Github Actions workflow.
The application is a simple console application that just print "Hello World!" to the console.

## How it Works
Simply uses dotnet run from within the ubuntu-latest container.
# Exercise 1 - Full stack open part 11

Language of choice:- C#(.NET)

## C# equivalent of Linting ,Testing, and Building

For linting, the C# compiler already has a few lint-like warnings, 
such as reminding you when you've forgotten to await an async method.
For in-depth linting a combination of StyleCop, dotnet-format, SonarLint, Resharper can used.
StyleCop and dotnet-format can be to enforce code formatting best practices and fix many common style issues.
SonarLint and ReSharper can be used for identifying bugs and code smells.

A few of the popular C# testing frameworks are xUnit, nUnit, MSTest and TestDriven.NET.When choosing a test framework, 
check whether the framework is well-suited for the ‘type’ of project your team is working on.
MSTest is the default test framework that is shipped along with Visual Studio.
While xUnit is created with more focus on the community; hence it is easy to expand upon.

 Visual Studio uses MSBuild to load and build managed projects. 
 The project files in Visual Studio (.csproj, .vbproj, .vcxproj, and others) contain MSBuild XML code that executes when you build a project by using the IDE .
 Other good open source build tools to automate your steps after you finished the creation of source code are Cake and Nuke


## Alternatives to Jenkins and GitHub Actions

Some of the popular alternatives to Jenkins and GitHub Actions are Buddy ,CircleCI, TravisCI and TeamCity

## Self-hosted vs. cloud-based environment

 As the Scale and Complexity of project is not known but as the team consist of 6 people, in my opinion 
 a cloud-based environment would be appropriate, as it is easy to setup while saving some precious development time.

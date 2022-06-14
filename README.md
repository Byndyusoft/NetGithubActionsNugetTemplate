[![License](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# .NET Nuget publishing template
This is a template repository with example github actions for .NET nuget packages creation and publishing

# How to use:
 - Remove example solution (ExampleSolution.sln, src and tests folders)
 - add icon reference to packaged projects ([example](src/ExampleProject/ExampleProject.csproj))
 - Change properties in Directory.Build.props file according to your needs (version, package tags, repository url)
 - fix **dotnet-version** in .github/workflows/\*.yml

# Maintainers
[github.maintain@byndyusoft.com](mailto:github.maintain@byndyusoft.com)

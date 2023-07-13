# Template Information (Delete this header before publishing package)

## .NET Nuget publishing template
This is a template repository with example github actions for .NET nuget packages creation and publishing

## How to use:
- Rename ExampleSolution into your solution name (ExampleSolution => MyPackageSolution)
- Change properties in Directory.Build.props file according to your needs (version, package tags, repository url)
- fix **dotnet-version** in .github/workflows/\*.yml

## How to publish pre-release to nuget.org:

Mark *This is a pre-release* checkbox when you create a release.

![image](https://user-images.githubusercontent.com/38452272/184600138-abc74f6e-3c7e-4c0a-ad51-426473f02917.png)

The package version will be *<proj_version>-tags-<tag_name>* where *proj_version* is retrieved from .csproj or Directory.Build.props file.

[![License](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
# PackageName [![Nuget](https://img.shields.io/nuget/v/PackageName.svg)](https://www.nuget.org/packages/PackageName/)[![Downloads](https://img.shields.io/nuget/dt/PackageName.svg)](https://www.nuget.org/packages/PackageName/)

Package description

## Installing

```shell
dotnet add package PackageName
```

## Usage

Usage description

```csharp
  TODO
```

# SecondPackageName [![Nuget](https://img.shields.io/nuget/v/SecondPackageName.svg)](https://www.nuget.org/packages/SecondPackageName/)[![Downloads](https://img.shields.io/nuget/dt/SecondPackageName.svg)](https://www.nuget.org/packages/SecondPackageName/)

Package description

## Installing

```shell
dotnet add package SecondPackageName
```

## Usage

Usage description

```csharp
  TODO
```

# Contributing

To contribute, you will need to setup your local environment, see [prerequisites](#prerequisites). For the contribution and workflow guide, see [package development lifecycle](#package-development-lifecycle).
## Prerequisites

Make sure you have installed all of the following prerequisites on your development machine:

- Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
- .NET (.net version) - [Download & Install .NET](https://dotnet.microsoft.com/en-us/download/dotnet/).

## Package development lifecycle

- Implement package logic in `src`
- Add or adapt unit-tests (prefer before and simultaneously with coding) in `tests`
- Add or change the documentation as needed
- Open pull request in the correct branch. Target the project's `master` branch

# Maintainers
[github.maintain@byndyusoft.com](mailto:github.maintain@byndyusoft.com)

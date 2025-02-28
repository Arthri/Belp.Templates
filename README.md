# Belp.Templates
[![Latest NuGet Release](https://img.shields.io/nuget/v/Belp.Templates?style=flat-square "Latest NuGet Release")](https://www.nuget.org/packages/Belp.Templates/latest)

Templates for MSBuild projects and other files.

## Available Item Templates

### Directory.Build.props
Short Name: `dbprops`

#### Options
None

### Directory.Build.targets
Short Name: `dbtargets`

#### Options
None

### Project Item
Short Name: `proj`

#### Options
- `--sdk <sdk>` (Optional): Specifies the SDK to put in `<Project Sdk="...">`.

## Available Project Templates
None

## Installation

### Prerequisites
- Install .NET 6 SDK or above.

### Install using .NET CLI(NuGet)
1. Open a terminal.
1. Run `dotnet new install Belp.Templates`.

### Install using .NET CLI(GitHub)
1. Download the `.nupkg` from [GitHub Releases](https://github.com/Arthri/Belp.Templates/releases/latest).
1. Open a terminal.
1. Locate and navigate to the package.
1. Run `dotnet new install Belp.Templates.VERSION.nupkg`.

### Uninstallation
1. Open a terminal.
1. Run `dotnet new uninstall Belp.Templates`.

## Usage

### Use from .NET CLI
1. Open a terminal.
1. Navigate to the desired directory.
1. Run `dotnet new <Desired Template>`. For example, `dotnet new dbprops` to create a new Directory.Build.props file.

### Use from Visual Studio
> **Note**: only project templates can be used from Visual Studio at the moment.

1. Open Visual Studio 2022 or later.
1. Click on "Create a new project".
1. Find the desired project template.
1. Fill out the requested fields.

# TechWithAlex.NUnitTests
.NET framework console application projects sample
    - TechWithAlex.SourceProject - Sample source project to be unit tested
    - TechWithAlex.NUnit3Tests - Sample NUnits tests project

## Installation
1. Make sure you have [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download) or newer installed on your machine (projects were developed using .NET 8). Check installation
    ```PS
    dotnet --version
    ```
2. Clone this repository to your local machine.
3. Open the solution in Visual Studio or solution folder in VS Code or your preferred IDE. 
4. Download [nuget.exe](https://www.nuget.org/downloads) or [nunit-console 3.16.0](https://github.com/nunit/nunit-console/releases/tag/3.16.0)
5. Open Command Prompt and navigate to the directory containing .NET Framework project's solution file (.sln).
6. Restore NuGet Packages, change "path":
    ```PS
    <path>\nuget.exe restore .\TechWithAlex.NUnitTests.sln
    ```
6. Build projects:
    ```PS
    dotnet build
    ```

## Usage
1. Run from IDE: Open the solution directory in VS Code or your preferred IDE. 
2. Run from cmd: Open Command Prompt and navigate to the directory containing unit tests .csproj file:

- run unit tests using dotnet
```
dotnet test .\bin\Debug\UnitTests.dll
```

- run unit tests using nunit3.16-console
```
<path>\nunit3-console.exe <path>\TechWithAlex.NUnitTests\TechWithAlex.NUnit3Tests\bin\Debug\TechWithAlex.NUnit3Tests.dll
```

## YT channel
Please check my YouTube channel for step by step implementation or detailed tutorials on automation and more: https://www.youtube.com/@TechWithAlexDuta

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
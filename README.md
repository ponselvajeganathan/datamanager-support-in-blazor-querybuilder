# DataManager Support in Syncfusion Blazor Query Builder

## Overview

This sample demonstrates how to integrate the Syncfusion [Blazor Query Builder](https://www.syncfusion.com/blazor-components/blazor-query-builder) with a DataManager-based data source and display the filtered results. The application allows users to build query conditions visually and applies those rules to the underlying data before rendering the results. This approach helps developers implement advanced filtering experiences without requiring users to manually write query expressions.
 
The sample is built as a Blazor Server application and showcases the interaction between Query Builder-generated rules and data processing logic within the application.

## Key Features

- Uses Syncfusion Query Builder to create filtering rules through a visual interface.
- Configures Query Builder columns based on the underlying data model exposed by the application.
- Integrates Syncfusion DataManager processing to execute filtering operations against the data source.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the verified solution file:

   `QueryBuilderSample.sln`

3. Restore NuGet packages.
4. Ensure the startup project.
5. Build the solution.
6. Run the application using **Ctrl+F5**.
7. Open the application URL displayed by the ASP.NET Core host.

**Visual Studio Code**

1. Clone or download the repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory and restore packages:

```bash
cd QueryBuilderSample
dotnet restore
```

5. Run the application:

```bash
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.

## Project Structure

`Pages/Index.razor` — contains the primary Query Builder configuration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for this feature: https://blazor.syncfusion.com/documentation/query-builder/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
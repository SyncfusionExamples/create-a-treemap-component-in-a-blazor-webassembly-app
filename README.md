# Create a TreeMap Component in a Blazor WebAssembly App

## Overview

This sample demonstrates how to create a Syncfusion [Blazor TreeMap](https://www.syncfusion.com/blazor-components/blazor-treemap) component in a Blazor WebAssembly application. The TreeMap visualizes the top 10 countries by nominal GDP in 2015 using a strongly typed data source. The sample shows how to size TreeMap items based on a numeric field, display labels for each item, apply range-based color mapping, and configure a custom title. It serves as a simple reference for implementing hierarchical data visualization with the Syncfusion TreeMap component in Blazor.

## Key Features

- Renders a TreeMap using the `SfTreeMap` component.
- Binds data through the `DataSource` property using a strongly typed `List<Country>` collection.
- Uses `TValue="Country"` to bind TreeMap items to the custom data model.
- Configures `WeightValuePath="GDP"` to determine the relative size of TreeMap items.
- Uses `RangeColorValuePath="GDP"` to drive color mapping from GDP values.
- Displays a custom title using `TreeMapTitleSettings`.
- Sets the title text and displays country names within TreeMap items using `TreeMapLeafItemSettings`.
- Uses `LabelPath="Name"` to render labels from the data source.
- Configures range based color mapping using `TreeMapLeafColorMapping`.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `CreatingTreeMapSample.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

`CreatingTreeMapSample.sln` — Visual Studio solution file for the Blazor WebAssembly TreeMap sample.

`Client/Pages/Index.razor` — Main sample page that configures and renders the `SfTreeMap` component, defines the `Country` model, and provides the GDP data source.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/treemap/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
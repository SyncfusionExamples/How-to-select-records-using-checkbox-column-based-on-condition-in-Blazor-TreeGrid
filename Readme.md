# Select Record using CheckBox Column Based on Condition in Blazor TreeGrid

## Overview

This sample demonstrates conditional row selection in the Syncfusion [Blazor TreeGrid](https://www.syncfusion.com/blazor-components`) component using a checkbox column. The implementation shows how to render a checkbox selection column through the `ShowCheckbox` property and automatically select records during initial rendering by invoking the `SelectCheckboxes` method based on a predefined condition. This approach is useful when business rules require specific records to be preselected while preserving TreeGrid hierarchy-selection behavior.

**Documentation**: https://blazor.syncfusion.com/documentation/treegrid/selection#checkbox-selection

## Key Features

- Demonstrates checkbox-based row selection in the Syncfusion TreeGrid.
- Uses the `ShowCheckbox` property to render a selection checkbox column.
- Uses the `SelectCheckboxes` method to programmatically select TreeGrid records.
- Demonstrates conditional record selection during initial component rendering.
- Supports hierarchical record selection within a TreeGrid data structure.
- Shows how checkbox selection can be combined with parent-child data relationships.
- Illustrates automatic selection logic without requiring user interaction.
- Demonstrates TreeGrid selection configuration using built-in checkbox selection functionality.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `SelectRecordUsingCheckBox.sln`

3. Restore NuGet packages.
4. Ensure the startup project is:

   `SelectRecordUsingCheckBox`

5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory containing `SelectRecordUsingCheckBox.csproj`.

```bash
dotnet restore
dotnet run
```

## Project Structure

`Pages/Index.razor` — Contains the primary Syncfusion TreeGrid implementation, checkbox column configuration, conditional selection logic, and programmatic invocation of the `SelectCheckboxes` method.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for checkbox selection: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/selection#checkbox-selection

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
---
layout: default
title: TableGen
parent: TableGen User Guide
nav_order: 1
---

# TableGen
{: .no_toc }
Import your spreadsheets, PDF and Word document into Revit as Legend Views, Schedule Views and Drafting Views.
Collaborate with non-Revit users and bring the beauty of your Excel Tables, PDF and Word documents into Revit.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# TableGen

There are three main ways to import files with TableGen. Each has different results in terms of visual fidelity and model weight.

1. Image import (Excel, Word, PDF) - Imports the content as images into a Legend or Drafting view, allowing you to set the resolution (DPI). 

2. Table import into Legend or Drafting view (Excel) - Converts the Excel table into Revit elements (text and linework). 

3. Table import into Schedule (Excel) - Places the data into the schedule header section.


## Add files

The first step is to add the files you want to import. You can do this in multiple ways:

- Drag & Drop - Drag one or more supported files from window explorer and drop them into the main TableGen grid.

- Add Table - Click the "Add Table" button and use the file dialog to select one or more supported files.

- Browse link ("click here to browse") - Opens the file dialog and allows you to select one or more supported files.

![TableGen selecting data to import](../../../assets\images\TableGen\TG-270-AddFiles.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


## Worksheet Selection Window

Once you drop or select the files to add, the worksheet selection window opens and lets you create multiple views in one operation by selecting which worksheets (and which region in each worksheet) should be imported. It also allows defining the default properties that will be applied to the new views.

- Files table: Each added file is displayed in here, you can use the context menu to switch to Relative/Absolute path.

- Excel files can be expanded to view and configure their worksheets. 

  - Worksheet selection: Use the checkboxes to choose which worksheets will be imported.

  - Region selection: For each worksheet, use the dropdown to pick the source range: Named Region, Print Area, or Used Range.

- Word and Pdf files cannot be expanded, but the view count field is editable, allowing you to create multiple views for the same file (you can edit the pages later).

- Default View Properties: Set the properties to be applied to every view created from this selection. The available properties are: Type (Table/Image), View Type (Legend/Drafting/Schedule), View Scale, and Black and White.

- Search: You can use the search bar on top to filter files by file name or path.

- When pressing "Ok", the views will be added to TableGen. The default view name will be the name of the Worksheet (Excel files) or the file name (Word/Pdf).

![TableGen selecting data to import](../../../assets\images\TableGen\TG-270-WorksheetSelectionWindow.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Named Regions in Excel

Named regions allow you to specify the range that you want to import into Revit. To create them follow the following steps:

1. In the worksheet you want to import select the desired range of cells, and then choose a name and type it in the Name Box - located to the left of the formula bar (see image below).
After creating the named region, save the Excel file to import it.

    ![TableGen selecting data to import](../../../assets\images\TableGen\TG-SelectRegionExcel.png)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. You can also to create multiple worksheet regions and each one can be individually imported to Revit.

    ![TableGen selecting data to import](../../../assets\images\TableGen\TG-MultipleRegions.png)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>


---


## Manage imported tables

The main grid is the central place to review and edit all imported tables. Each row represents a view and can be configured directly inline.

![TableGen batch actions 01](../../../assets\images\TableGen\TG-270-MainTable.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


- **Checkbox** - selects rows for batch operations. Check the header checkbox to select or deselect all rows at once.

- **Status** - indicates the current state of each entry. Hover over the icon for a tooltip description.

- **Source** - shows the file type (Excel, Word, PDF). Use the column header dropdown to filter by file type.

- **Type** - toggles between Table and Image import mode. Use the column header dropdown to filter by type. Word and PDF files only support Image mode.

- **View Name** - the name of the Revit view that will be created or updated. Click to rename it directly.

- **DPI** - sets the image resolution. Only active for Image type entries.

- **Auto Sync** - when enabled, this view will automatically be updated if there are changes to the file, it triggers whenever the Revit model is opened.

- **Black and White** - removes all color formatting on import (text and borders become black, backgrounds transparent). Only available for Table type entries.

- **Last Modified** - shows the last modified date of the source file.

- **Region / Page Selection** - for Excel files, two dropdowns let you select the worksheet and the named region or range. For Word and PDF files, use the first dropdown to choose All pages or a custom selection.  
    ```yaml
    # Note:
    When using custom page selection, type page numbers and/or page ranges separated by commas, counting from the start of the document. For example, typing "1, 3, 5-7" will add pages 1, 3, 5, 6, and 7 as images.
    ```

- **View Type** - the Revit view type to create: Legend, Drafting, or Schedule. Cannot be changed after the view has been created in Revit.

- **View Scale** - sets the scale of the Revit view.

- **File Path** - shows the path to the source file. Can be toggled between absolute and relative path via the context menu or batch action.


## Batch Actions

The "Batch Actions" dropdown allows you to perform various actions on multiple views at once. To use them, check the desired views using their checkboxes and then click the action.

![TableGen batch actions 01](../../../assets\images\TableGen\TG-270-BatchActions.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

- **Update Views** - redraws the linked Revit views using the source file.

- **Duplicate Views** - creates a copy of the selected views.

- **Reload From** - relinks the selected views to a new file location. When a single view is selected, you are prompted to choose a file. When multiple views are selected, you are prompted to choose a folder, and each file is matched by name within that folder. Useful when source files have been moved or reorganised.

- **Absolute/Relative Path** - toggles the file path format for the selected entries.

- **Open Files** - opens the source files in their default application.

- **Open Folders** - opens the folders containing the source files.

- **Delete Views** - removes the selected views from Revit and from the TableGen grid.

- **Unlink View** - removes the link to the Revit view and deletes the TableGen entry.

The context menu, accessible by right-clicking on any row in the grid, allows you to run the same commands on the currently selected rows. It also has an additional command:
-  **Open View** - opens the view in Revit


## Tables synchronization

### Refresh table

Click the Sync button to refresh the information displayed in the grid, updating the Last Modified date, available Worksheets, and Regions for each entry. This does not update the Revit views themselves.

### Auto Sync

The Auto Sync checkbox, available for each view in the main grid, enables automatic synchronization. When enabled, the view will be automatically updated in Revit when the model is opened, if changes are detected in the source file.

## Black and White – Remove color formatting

Use this option to ignore all Excel colors when importing tables, keeping the result black and white.
Where to find it:
- Checkbox Column in the main window ("Black & White")
- In the Worksheet Selection window, in the Default View Properties, a checkbox labeled "Black & White – Remove color formatting".

What it does when enabled:
- Converts all text to black 
- Converts all borders to black 
- Removes cell background colors (background becomes transparent)

    ![TableGen right-click](../../../assets\images\TableGen\TG-270-Black&White.gif)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
---

If you want to find out more about TableGen and explore detailed tutorials on how to use it, visit our YouTube channel. There, you'll find a series of videos that can help answer questions and improve your knowledge. Be sure to check it out and subscribe to keep up to date with our news and tips!

[DiRoots Channel](https://www.youtube.com/@DiRootsNews){: .btn .btn-di-orange }
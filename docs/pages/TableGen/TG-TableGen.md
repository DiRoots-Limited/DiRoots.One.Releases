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

There are three main ways to import files with TableGen. Each has different results in terms of visual fidelity, editability, and model weight.

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

- Excel files can be expanded to view and configure its worksheets. 

  - Worksheet selection: Use the checkboxes to choose which worksheets will be imported.

  - Region selection: For each worksheet, use the dropdown to pick the source range: Named Region, Print Area, or Used Range.

- Word and Pdf files cannot be expanded, but the view count field is editable, allowing you to create multiple views for the same file (you can edit the pages later).

- Default View Properties: Set the properties to be applied to every view created from this selection. The available properties are: Type (Table/Image), View Type (Legend/Drafting/Schedule), View Scale, and Black and White.

- Search: You can use the search bar on top to filter files by file name or path.

- When pressing "Ok", the views will be added to TableGen. The default view name will be the name of the Worksheet (Excel files) or the file name (Word/Pdf).

![TableGen selecting data to import](../../../assets\images\TableGen\TG-270-WorksheetSelectionWindow.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Named Regions in Excel

Named regions allow you to specify the range that you want to import into Revit. To create them follow the following steps:

1. In the worksheet you want to import select the desired range of cells, and then choose a name and type it in the Name Box - located to the left of the formula bar (see image below).
After creating the named region, save the Excel file to import it.

    ![TableGen selecting data to import](../../../assets\images\TableGen\TG-SelectRegionExcel.png)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

    You can also to create multiple worksheet regions and each one can be individually imported to Revit.

    ![TableGen selecting data to import](../../../assets\images\TableGen\TG-MultipleRegions.png)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>


---


## Manage imported tables

1. The “Source” column shows the type of file that has been imported, corresponding to the Excel, Word and PDF icons. Click on the column header and filter the imported files.

2. The “Type” column indicates whether the file has been imported as an image or as a table. Click on the column header to filter the types to be created.

3. The WorkSheet, Region and View Type columns are editable via the drop-down list.

    ```yaml
    # Note:
    Note that it is not possible to edit the WorkSheet and Region columns of Word and PDF files.
    ```

    ![TableGen manage table](../../../assets\images\TableGen\TG-ManageFiles.gif)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Use the searchbox to search by documents imported.

### Batch Actions

The “Batch actions” allow the user to perform certain actions on the imported files. The user has to select the required files and go to the “Batch actions” drop-down list.

- Update Views:
- Duplicate Views:
- Delete Views

    ![TableGen batch actions 01](../../../assets\images\TableGen\TG-Batch01.gif)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

- Open Files:
- Open Folders:
- Absolute/Relative Path:
- Unlink View:

![TableGen batch actions 02](../../../assets\images\TableGen\TG-Batch02.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can also find these options using the context menu by right-clicking on the desired file.

    ![TableGen right-click](../../../assets\images\TableGen\TG-ContextMenu.gif)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Tables synchronization

### Refresh table

Click on the Sync button and refresh the Excel data: Last Modified, WorkSheets, and Regions.

### Auto Sync

You can select the checkbox to anable automatic table synchronization. That is, whenever the Revit model is started, it will be synchronized to to look for the most recent file updates.

---

## Black and White – Remove color formatting

Use this option to ignore all Excel colors when importing tables, keeping the result black and white.
Where to find it:
- Checkbox Column in the main window ("Black & White")
- In the Worksheet Selection window, in the Default View Properties a checkbox labeled "Black & White – Remove color formatting".

What it does when enabled:
- Converts all text to black 
- Converts all borders to black 
- Removes cell background colors (background becomes transparent)

    ![TableGen right-click](../../../assets\images\TableGen\TG-270-Black&White.gif)  
    <sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
---

If you want to find out more about TableGen and explore detailed tutorials on how to use it, visit our YouTube channel. There, you'll find a series of videos that can help answer questions and improve your knowledge. Be sure to check it out and subscribe to keep up to date with our news and tips!

[DiRoots Channel](https://www.youtube.com/@DiRootsNews){: .btn .btn-di-orange }
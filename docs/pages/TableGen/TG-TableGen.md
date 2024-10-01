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

## Import from Excel

Follow the firsts steps:

1. Choose a spreadsheet you want to import into Revit and make a selection of the range of cells you want to bring to Revit, and then name the previously selected range of cells and hit Enter.
After selecting the data, save the Excel file to import it.

![TableGen selecting data to import](../../../assets\images\TableGen\TG-SelectRegionExcel.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can also to create multiple worksheet regions and each one can be individually imported to Revit.

![TableGen selecting data to import](../../../assets\images\TableGen\TG-MultipleRegions.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

2. Select the TableGen from the DiRootsOne menu, and click on the Add Tables button. The next step is to select the Excel file.

3. The fields will be filled in by default, but you can change them to complete the process. 

- In the firts dropdown list select Excel file.
- Then select the if you wan to import as table or image.
- Select the Excel file in your browser.
- Number of copies: the TableGen will import the number of copies filled in this field.
- WorkSheet: choose the current WorkSheet.
- WorkSheet Region: choose the selection created in the Excel file.
- View Type: choose if you want to import like a Legend View, Schedule View or Drafting View.
- Assign a view scale.

![TableGen import Excel](../../../assets\images\TableGen\TG-ImportExcel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

Confirm the import on the OK button, and wait a few seconds for the import to complete.

---

## Import from Word

Word documents are imported by images into Revit.

Follow the steps:

- Select the Word file to import.
- Number of copies: the TableGen will import the number of copies filled in this field.
- Open the dropdown and select All Pages or Selected.
    - If you choose only "selected" pages, you need to enter the pages number you want.
    - Sepate pages by commas counting from the start of the document. E.g. typing "1, 3, 5-7" will add pages 1, 3, 5, 6, and 7 as images.
- Open the dropdown list and select the density (DPI) of the image to be created.
- View Type: choose if you want to import like a Legend View, Schedule View or Drafting View.
- Assign a view scale.

![TableGen import word](../../../assets\images\TableGen\TG-ImportWord.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

Confirm the import on the OK button, and wait a few seconds for the import to complete.

---

## Import PDF

PDF documents are imported by images into Revit.

Follow the steps:

- Select the PDF file to import.
- Number of copies: the TableGen will import the number of copies filled in this field.
- Open the dropdown and select All Pages or Selected.
    - If you choose only "selected" pages, you need to enter the pages number you want.
    - Sepate pages by commas counting from the start of the document. E.g. typing "1, 3, 5-7" will add pages 1, 3, 5, 6, and 7 as images.
- Open the dropdown list and select the density (DPI) of the image to be created.
- View Type: choose if you want to import like a Legend View, Schedule View or Drafting View.
- Assign a view scale.

![TableGen import PDF](../../../assets\images\TableGen\TG-ImportPDF.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

Confirm the import on the OK button, and wait a few seconds for the import to complete.

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

If you want to find out more about TableGen and explore detailed tutorials on how to use it, visit our YouTube channel. There, you'll find a series of videos that can help answer questions and improve your knowledge. Be sure to check it out and subscribe to keep up to date with our news and tips!

[DiRoots Channel](https://www.youtube.com/@DiRootsNews){: .btn .btn-di-orange }
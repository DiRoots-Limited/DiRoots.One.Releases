---
layout: default
title: Selection Tab
parent: SheetLink User Guide
nav_order: 1
---

# SheetLink
{: .no_toc }
Export your Revit model data (by categories, elements, schedules) to Excel and Google Sheets. Edit the data and import it back to update the model.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Model Categories

The first step is to select the SheetLink in the DiRootsOne menu and to choose the Model Categories tab. 

Steps:

1. Click radio buttons to switch between Whole Model, Active View or Current Selection to choose the categories.

```yaml
The 'Whole Model' radio button will show the existing all model categories.
The 'Active View' radio button will show the existing categories in the current view.
The 'Current Selection' radio button will show the existing categories in the current selection.
```

2. Use the checkboxes above the table to select to Include Linked Files and to Export by Type ID

![SheetLink including linked files and exporting by type ID](../../assets\images\SH-LinkedFile-TypeID.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>


3. Use the checkboxes to select specific categories or use the checkbox in the table header to select all categories.

![SheetLink Selecting Revit categories](../../assets\images\SH-Select-Categoriesgif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Categories

The search box will search for categories contained in the Select Categories column.  

![SheetLink Searching for model categories](../../assets\images\SH-Search-Categories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

## Instance, Type and Read-only

After to choose the categories, the SheetLink has options to see just instance, type and read-only parameters.

Click on the table headers to select the instance parameters.


```yaml
# Note:  
If selected the instance parameters, will show it in the green color.
If selected the type parameters, will show it in the yellow color.
If selecte the read-only parameters, will show it in the red color.
```
  

![SheetLink select the parameters](../../assets\images\SH-Select-Parameters-gif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Available Parameters

The search box will search for parameters contained in the Available Parameters column.  

![SheetLink Searching for available parameters](../../assets\images\SH-Search-Parameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---
~
## Selected Parameters

Choosing paramenters:
1. Select the parameters in the Available Parameters table.
2. Click in the arrows to add or remove from the Selected Parameters table.


![SheetLink adding and removing parameters](../../assets\images\SH-Add-Remove-Parameters.gif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Selected Parameters

The search box will search for parameters contained in the Selected Parameters column.  

![SheetLink Searching for available parameters](../../assets\images\SH-Search-Selected-Parameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Order the Selected Parameters

Use the arrows above the Selected Parameters table, to order the parameters to export.  

![SheetLink order the selected parameters](../../assets\images\SH-Order-Parameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Isolate Selection

The Isolate Selection button allows to filter the selected categories in a Temporary View (Hide/Isolate).

![SheetLink isolate categories selected](../../assets\images\SH-Isolate-Seletection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Export Project Standards

The Export Project Standards button allows to export the main data about the project to Excel or Google Drive.
![SheetLink Export Project Standard to Excel or Google Drive](../../assets\images\SH-Export-Project-Standard.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Reset Values

Select the Reset Values button to clean all the parameters available and selected.
![SheetLink Reset Values](../../assets\images\Reset-Values.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Preview/Edit

Click to preview and to edit the sheet before exporting.
![SheetLink Reset Values](../../assets\images\SH-Preview-Edit.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.
![SheetLink Reset Values](../../assets\images\SH-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

The excel file is editable and after to editing it you can import through SheetLink.
Caution, open the Instruction tab in your excel file to get the colors legend. 

```yaml
# Note:  
Yellow: Type Value
Red: Read-only Value. This fields can not be edited.
Grey: Parameter does not exist for this element.
```

```yaml
# Note:  
If you are altering the value of 'Type Parameters', ensure that you have the same value for all elements with the same 'Type ID'
```

### Import

If you have made some file edition, import it and update the current model on Revit. Before importing the file, you can preview the sheet to make sure, and after conclude the import.
![SheetLink Import file](../../assets\images\SH-ImportFile.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```

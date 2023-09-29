---
layout: default
title: Model Categories
parent: SheetLink User Guide
nav_order: 2
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

The first step is to select the SheetLink from the DiRootsOne menu and to choose the Model Categories tab. 

Steps:

1. Click on the radio buttons to switch between Whole Model, Active View or Current Selection to choose the categories.

```yaml
The 'Whole Model' radio button will show the all existing model categories.
The 'Active View' radio button will show the existing categories in the current view.
The 'Current Selection' radio button will show the existing categories in the current selection.
```

2. Use the checkboxes above the table to select to Include Linked Files and to Export by Type ID.

![SheetLink including linked files and exporting by type ID](../../../assets\images\SheetLink\SH-LinkedFile-TypeID.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Use the checkboxes to select specific categories, or use the checkbox in the table header to select all categories.

![SheetLink Selecting Revit categories](../../../assets\images\SheetLink\SH-Select-Categoriesgif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Categories

The search box will search for categories contained in the Select Categories column.  

![SheetLink Searching for model categories](../../../assets\images\SheetLink\SH-Search-Categories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Instance, Type and Read-only

After choosing the categories, the SheetLink has options to view instance, type and read-only parameters.

Click on the table headers to select the instance parameters.

```yaml
# Note:  
If selected, the instance parameters, will shown it in the green.
If selected the type parameters, will be shown it in the yellow.
If selected the read-only parameters, will be shown in the red.
```

![SheetLink select the parameters](../../../assets\images\SheetLink\SH-Select-Parameters-gif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Available Parameters

The search box will search for parameters contained in the Available Parameters column.  

![SheetLink Searching for available parameters](../../../assets\images\SheetLink\SH-Search-Parameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Selected Parameters

Parameters selection:
1. Select the parameters in the Available Parameters table.
2. Click on the arrows to add or remove from the Selected Parameters table.

![SheetLink adding and removing parameters](../../../assets\images\SheetLink\SH-Add-Remove-Parameters.gif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Selected Parameters

The search box will search for parameters contained in the Selected Parameters column.  

![SheetLink Searching for available parameters](../../../assets\images\SheetLink\SH-Search-Selected-Parameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Order the Selected Parameters

Use the arrows above the Selected Parameters table, to sort the parameters to be exported.  

![SheetLink order the selected parameters](../../../assets\images\SheetLink\SH-Mc-bx.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Filter elements within a section box

You have the ability to use existing or to duplicate 3D View. Visualize only filtered elements or all elements within Section Box, with ability to define offset from marked elements.

![SheetLink filter elements within a section box](../../../assets\images\SheetLink\SH-Isolate-Seletection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Isolate Selection

The Isolate Selection button allows you to filter the selected categories in a Temporary View (Hide/Isolate).

![SheetLink isolate categories selected](../../../assets\images\SheetLink\SH-Isolate-Seletection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Export Project Standards

The Export Project Standards button allows you to export the main data about the project to Excel or Google Drive. The data to be exported is the Project Information, Object Styles, Line Styles and Families.

![SheetLink Export Project Standard to Excel or Google Drive](../../../assets\images\SheetLink\SH-ac-ExportProjectStandard.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import Project Standards file

You can also edit some Project Information and import to update the current model.

![SheetLink Import Project Standards file](../../../assets\images\SheetLink\SH-El-ImportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Reset Values

Select the Reset Values button to clear all available and selected parameters.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-Mc-ResetValue.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Preview/Edit

Click to preview and edit the sheet before exporting it.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-Preview-Edit.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.

![SheetLink Export sheet](../../../assets\images\SheetLink\SH-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

The Excel file is editable and after editing can be imported through SheetLink.
Caution, open the Instruction tab in your Excel file to get the colors legend. 

```yaml
# Note:  
Yellow: Type Value
Red: Read-only Value. This fields can not be edited.
Grey: Parameter does not exist for this element.
```

```yaml
# Note:  
If you are changing the value of 'Type Parameters', ensure that you have the same value for all elements with the same 'Type ID'
```

### Import

If you have made any edits to the file, import it and update the current model on Revit. Before importing the file, you can preview the sheet to be sure, and then complete the import.

![SheetLink Import file](../../../assets\images\SheetLink\SH-ImportFile.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```

---
layout: default
title: Annotation Categories
parent: SheetLink User Guide
nav_order: 3
---

# SheetLink
{: .no_toc }
Export your Revit model data (by categories, elements, schedules) to Excel and Google Sheets. Edit the data and import it back to update the model.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Annotation Categories

The first step is to select the SheetLink in the DiRootsOne menu and to choose the Annotation Categories tab. 

Steps:

1. Click radio buttons to switch between Whole Model, Active View or Current Selection to choose the categories.

```yaml
# Note:
The 'Whole Model' radio button will show the existing all annotation categories.
The 'Active View' radio button will show the existing annotation categories in the current view.
The 'Current Selection' radio button will show the existing annotation categories in the current selection.
```

2. Use the checkboxes above the table to select to Include Linked Files and to Export by Type ID

![SheetLink including linked files and exporting by type ID](../../../assets\images\SheetLink\SH-IncludeLink.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


3. Use the checkboxes to select specific annotation categories, or use the checkbox in the table header to select all annotation categories.

![SheetLink Selecting annotation categories](../../../assets\images\SheetLink\SH-Select-AnCategories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Categories

The search box will search for annotation categories contained in the Select Categories column.  

![SheetLink Searching for annotation categories](../../../assets\images\SheetLink\SH-Search-AnCategories.gif.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Instance, Type and Read-only

After to choose the categories, the SheetLink has options to see just instance, type and read-only parameters.

Click on the table headers to select the instance parameters, for example.

```yaml
# Note:  
If selected, the instance parameters, will show it in the green color.
If selected the type parameters, will show it in the yellow color.
If selected the read-only parameters, will show it in the red color.
```
  

![SheetLink select the parameters](../../../assets\images\SheetLink\SH-ac-SelectInstance.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Available Parameters

The search box will search for parameters contained in the Available Parameters column.  

![SheetLink Searching for available parameters](../../../assets\images\SheetLink\SH-Search-AvailableParameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Selected Parameters

Choosing parameters:
1. Select the parameters in the Available Parameters table.
2. Click in the arrows to add or remove from the Selected Parameters table.


![SheetLink adding and removing parameters](../../../assets\images\SheetLink\SH-AddRemove.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Selected Parameters

The search box will search for parameters contained in the Selected Parameters column.  

![SheetLink Searching for available parameters](../../../assets\images\SheetLink\SH-Search-Selected-Parameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Order the Selected Parameters

Use the arrows above the Selected Parameters table, to order the parameters to export.  

![SheetLink order the selected parameters](../../../assets\images\SheetLink\SH-ac-OrderParameters.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Isolate Selection

The Isolate Selection button allows filtering the selected annotation categories in a Temporary View (Hide/Isolate).

![SheetLink isolate annotation categories selected](../../../assets\images\SheetLink\SH-ac-IsolateSelection.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Export Project Standards

The Export Project Standards button allows exporting the main data about the project to Excel or Google Drive. The data to be able to export is the Project Information, Object Styles, Line Styles and Families.

![SheetLink Export Project Standard to Excel or Google Drive](../../../assets\images\SheetLink\SH-ac-ExportProjectStandard.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import Project Standards file

You can also edit some Project Information and import to update the current model.

![SheetLink Import Project Standards file](../../../assets\images\SheetLink\SH-El-ImportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Reset Values

Select the Reset Values button to clean all the parameters available and selected.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-ac-ResetValue.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Preview/Edit

Click to preview and to edit the sheet before exporting.
![SheetLink Reset Values](../../../assets\images\SheetLink\SH-ac-Preview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.
![SheetLink export sheet](../../../assets\images\SheetLink\SH-ac-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

The Excel file is editable and after the editing of it you can import through SheetLink.
Caution, open the Instruction tab in your Excel file to get the colors legend. 

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

![SheetLink Import file](../../../assets\images\SheetLink\SH-ac-Import.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```
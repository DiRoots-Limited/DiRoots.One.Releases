---
layout: default
title: Schedules
parent: SheetLink User Guide
nav_order: 5
---

# SheetLink
{: .no_toc }
Export your Revit model data (by categories, elements, schedules) to Excel and Google Sheets. Edit the data and import it back to update the model.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Schedules

The first step is to select the SheetLink from the DiRootsOne menu and choose the Schdules tab.
Make sure that you have created a schedule in Revit, to be exported by SheetLink from DiRootsOne. 

Steps:

1. In this tab, you can choose between selecting a schedule from the Whole Model or from the Active View.

```yaml
The 'Whole Model' radio button will show all existing schedules.
The 'Active View' radio button will show the existing schedules in the current view.
```

2. Use the checkboxes above the table to select to Export by Type ID.

![SheetLink including exporting by type ID](../../../assets\images\SheetLink\SH-Sc-TypeID.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>


3. Use the checkboxes in the Select Schedule table to choose the schedules to be exported by SheeLink.

![SheetLink choosing schedules](../../../assets\images\SheetLink\SH-Sc-SelectSchedule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

4. Right-click on the schedule to choose the option to view it.

![SheetLink open schedule view](../../../assets\images\SheetLink\SH-Sc-OpenSchedule.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>


### Search Schedules

The search box will search for schedules contained in the Select Schedules column.

![SheetLink Searching for schedules](../../../assets\images\SheetLink\SH-Sc-SearchSchedule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Filter elements within a section box

You can use the existing 3D view or duplicate it. Visualize only filtered elements or all elements within Section Box, with ability to define offset from marked elements.

![SheetLink filter elements within a section box](../../../assets\images\SheetLink\SH-Sc-bx.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Isolate Selection

The Isolate Selection button allows filtering the elements from the selected Schedules in a Temporary View (Hide/Isolate).

![SheetLink isolate the elements from schedules](../../../assets\images\SheetLink\SH-Sc-Isolate.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Export Project Standards

The Export Project Standards button allows yoy to export the main project data to Excel or Google Drive. The data to be exported is the Project Information, Object Styles, Line Styles and Families.

![SheetLink Export Project Standard to Excel or Google Drive](../../../assets\images\SheetLink\SH-Sc-ExportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Import Project Standards file

You can also edit some Project Information and import to update the current model.

![SheetLink Import Project Standards file](../../../assets\images\SheetLink\SH-Sc-ImportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Instance, Type and Read-only

After choosing the schedules, SheetLink has options to see only instance, type and read-only parameters of the schedules.

Click on the table headers to select the instance parameters, for example.

```yaml
# Note:  
If selected, the instance parameters, will shown it in the green.
If selected the type parameters, will be shown it in the yellow.
If selected the read-only parameters, will be shown in the red.
```
  
![SheetLink select the parameters](../../../assets\images\SheetLink\SH-Sc-Instance.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Reset Values

Select the Reset Values button to clear all the selected schedules.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-Sc-ResetValues.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Preview/Edit

Click to preview and edit the sheet before exporting it.

![SheetLink Preview](../../../assets\images\SheetLink\SH-Sc-Preview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.

![SheetLink Export sheet](../../../assets\images\SheetLink\SH-Sc-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

```yaml
# Note:  
Choose to keep formatting of the schedule, or export as a template file. If you choose to keep format, you will not be able to import data back to Revit.
```

See below for the difference between the exported sheets, keeping the format and the template sheet.

![SheetLink difference between the sheets](../../../assets\images\SheetLink\SH-Sc-Sheets.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

The template Excel file is editable and after the editing, can be imported through SheetLink.
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

If you have made any edits to the file, import it and update the schedules in Revit. Before importing the file, you can preview the sheet to make sure, and then complete the import.
![SheetLink Import file](../../../assets\images\SheetLink\SH-Sc-Import.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```

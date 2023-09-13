---
layout: default
title: Selection Tab
parent: SheetLink User Guide
nav_order: 4
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

The first step is to select the SheetLink in the DiRootsOne menu and to choose the Schdules tab.
Make sure that you have created a schedule on Revit, to be exported by SheetLink from DiRootsOne. 

## Select Schedules

Follow the steps:

1. On this tab, you can choose between to select a schedule from Whole Model or from the Active View.

```yaml
# Note:
The 'Whole Model' radio button will show all existing schedules.
The 'Active View' radio button will show the existing schdules in the current view.
```

2. Use the checkboxes above the table to select to Export by Type ID.

![SheetLink including exporting by type ID](../../assets\images\SH-Sc-TypeID.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

3. Use the checkboxes in the Select Schedule table to choose the schedules to be exported by SheeLink.

![SheetLink choosing schedules](../../assets\images\SH-Sc-SelectSchedule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

4. Click with the right mouse button on the schedule to choose the option to visualize it.~

![SheetLink open schedule view](../../assets\images\SH-Sc-OpenSchedule.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Schedules

The search box will search for schedules contained in the Select Schedules column.

![SheetLink Searching for schedules](../../assets\images\SH-Sc-SearchSchedule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

## Parameters

### Filter elements within a section box

You have the ability to use existing or to duplicate 3D View. Visualize only filtered elements or all elements within Section Box with ability to define offset from marked elements.

![SheetLink filter elements within a section box](../../assets\images\SH-Sc-bx.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Isolate Selection

The Isolate Selection button allows to filter the elements from the selected Schedules in a Temporary View (Hide/Isolate).

![SheetLink isolate the elements from schedules](../../assets\images\SH-Sc-Isolate.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Export Project Standards

The Export Project Standards button allows to export the main data about the project to Excel or Google Drive. The data to able to export is the Project Information, Object Styles, Line Styles and Families.

![SheetLink Export Project Standard to Excel or Google Drive](../../assets\images\SH-Sc-ExportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Import Project Standards file

You can also edit some Project Information and import to update the current model.

![SheetLink Import Project Standards file](../../assets\images\SH-Sc-ImportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Instance, Type and Read-only

After to choose the schedules, the SheetLink has options to see just instance, type and read-only parameters from the schedules.

Click on the table headers to select the instance parameters for example.

```yaml
# Note:  
If selected the instance parameters, will show it in the green color.
If selected the type parameters, will show it in the yellow color.
If selecte the read-only parameters, will show it in the red color.
```

![SheetLink select the parameters](../../assets\images\SH-Sc-Instance.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Reset Values

Select the Reset Values button to clean all the selected schedules.

![SheetLink Reset Values](../../assets\images\SH-Sc-ResetValues.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Preview/Edit

Click to preview and to edit the sheet before exporting.

![SheetLink Preview](../../assets\images\SH-Sc-Preview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.

![SheetLink Export sheet](../../assets\images\SH-Sc-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

```yaml
# Note:  
Choose to keep formatting of the schedule, or export as a template file. If you choose keeping format, you will not be able to import data back to Revit.
```

See bellow the difference between the exported sheets, keeping the format and the template sheet.

![SheetLink difference between the sheets](../../assets\images\SH-Sc-Sheets.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

The template excel file is editable and after to editing it you can import through SheetLink.
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

If you have made some file edition, import it and update the schedules on Revit. Before importing the file, you can preview the sheet to make sure, and after conclude the import.

![SheetLink Import file](../../assets\images\SH-Sc-Import.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```

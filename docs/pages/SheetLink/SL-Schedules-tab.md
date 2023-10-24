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
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


3. Use the checkboxes in the Select Schedule table to choose the schedules to be exported by SheeLink.

![SheetLink choosing schedules](../../../assets\images\SheetLink\SH-Sc-SelectSchedule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

4. Right-click on the schedule to choose the option to view it.

![SheetLink open schedule view](../../../assets\images\SheetLink\SH-Sc-OpenSchedule.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


### Search & Filtering

#### Find Schedules

The search box will search for schedules contained in the Select Schedules column.

![SheetLink Searching for schedules](../../../assets\images\SheetLink\SH-Sc-SearchSchedule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


#### Filter Parameters 

The parameters can be filtered by Instance, Type and Read-only.
  
![SheetLink select the parameters](../../../assets\images\SheetLink\SH-Sc-Instance.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:  
Instance parameters are displayed in green.
Type parameters are displayed in yellow.
Read-only parameters are displayed in red.
```
---

### Preview/Edit

Click to preview and edit the sheet before exporting it.

![SheetLink Preview](../../../assets\images\SheetLink\SH-Sc-Preview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export

Click to export the sheet to Google Drive, Excel or Morta.

#### Export Options

```yaml
# Note:  
Choose to keep formatting of the schedule, or export as a template file. 
If you choose to keep format, you will not be able to import data back to Revit.
```
To export the linked elements use the 'Keep formatting of Schedules' option.

![SheetLink linked elements warning](../../../assets\images\SheetLink\SL-Sc-Linked-Elements-Warning.png)  

![SheetLink Schedules Export Options](../../../assets\images\SheetLink\SL-Sc-Export-Options.png)  

See below for the difference between the exported sheets, keeping the format and the template sheet.

![SheetLink difference between the sheets](../../../assets\images\SheetLink\SH-Sc-Sheets.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

The template Sheet file is editable and after the editing, can be imported through SheetLink.
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

#### 1. Export to Excel file.

Choose the folder location to export the Excel file, and wait for a few seconds for the export process.

![SheetLink export to excel file](../../../assets\images\SheetLink\SH-Sc-excel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

#### 2. Export to Google Drive.

Connect to your Google Drive account, and then select a folder to export the schedule to.

![SheetLink export to Google Drive](../../../assets\images\SheetLink\SH-Sc-googledrive.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

#### 3. Export to Morta.

To export sheet to Morta, make sure you are connected to the Morta API. Don't worry if you're not connected, just go to your Morta profile > Integrations and click on the New API Key button. Copy the created key, and paste it into the Morta API Key field in SheetLink.
Now, choose your project into Morta and click on Upload to Morta button.

```yaml
# Note:  
To learn more about connecting to the Dead API, click on "How to get the API Key" link.
```

![SheetLink export to Morta](../../../assets\images\SheetLink\SH-Sc-Morta.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

Note that maybe can exist a table with the same name and you can choose to Create a new table with a suffix or Overwrite existing tables.

![SheetLink table with the same name](../../../assets\images\SheetLink\SL-Sc-Name.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can also choose a Table type to export sheet, according you have in your selected project.

![SheetLink table type](../../../assets\images\SheetLink\SL-Sc-tabletype.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import

If you have made any edits to the file, import it and update the schedules in Revit. Before importing the file, you can preview the sheet to make sure, and then complete the import.
![SheetLink Import file](../../../assets\images\SheetLink\SH-Sc-Import.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```
### Other Features


#### Isolate Selection

The Isolate Selection button allows filtering the elements from the selected Schedules in a Temporary View (Hide/Isolate).

![SheetLink isolate the elements from schedules](../../../assets\images\SheetLink\SH-Sc-Isolate.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

#### Create a section box

You can use the existing 3D view or duplicate it. Visualize only filtered elements or all elements within Section Box, with ability to define offset from marked elements.

![SheetLink filter elements within a section box](../../../assets\images\SheetLink\SH-Sc-bx.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

#### Export Project Standards

The Export Project Standards button allows yoy to export the main project data to Excel or Google Drive. The data to be exported is the Project Information, Object Styles, Line Styles and Families.

![SheetLink Export Project Standard to Excel or Google Drive](../../../assets\images\SheetLink\SH-Sc-ExportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

#### Import Project Standards file

You can also edit some Project Information and import to update the current model.

![SheetLink Import Project Standards file](../../../assets\images\SheetLink\SH-Sc-ImportProject.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

#### Reset Values

Select the Reset Values button to clear all the selected schedules.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-Sc-ResetValues.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

---
layout: default
title: Model Categories
parent: SheetLink
nav_order: 2
nav_sections:
  - title: "Instance, Type and Read-only"
    anchor: instance-type-and-read-only
  - title: "Selected Parameters"
    anchor: selected-parameters
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

1. Click a radio button to choose which categories to show:
   - **Whole Model** shows all existing model categories.
   - **Active View** shows the categories in the current view.
   - **Current Selection** shows the categories in the current selection. If elements are already selected in Revit when you open the tab, this option is chosen for you.

2. Use the checkboxes above the table to include linked files and export by Type ID. Export by Type ID exports only the type parameters, with one row per type, so the instance parameters are not available. With Whole Model, it also lists the types that are not placed in the model.

   ![SheetLink including linked files and exporting by type ID](../../../assets\images\SheetLink\SH-LinkedFile-TypeID.gif)<br />
   <sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Use the checkboxes to select specific categories, or use the checkbox in the table header to select all categories. Select Hide un-checked categories below the table to show only the checked categories.

   ![SheetLink Selecting Revit categories](../../../assets\images\SheetLink\SH-Select-Categoriesgif.gif)<br />
   <sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Categories

The search box will search for categories contained in the Select Categories column.  

![SheetLink Searching for model categories](../../../assets\images\SheetLink\SH-Search-Categories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Instance, Type and Read-only

After choosing the categories, the SheetLink has options to view instance, type and read-only parameters.

Click on the table headers to select the instance parameters.

Right-click the Available Parameters or Selected Parameters list to choose Order By Instance, Order By Type or Select All.

{: .note }
If selected, the instance parameters, will shown it in the green.
If selected the type parameters, will be shown it in the yellow.
If selected the read-only parameters, will be shown in the red.

The Family + Type (editable) parameter is listed for categories that contain family instances. It is not available with Export by Type ID. In Excel it becomes a Family and a Type column with dropdown lists, and the chosen Family and Type are applied to the elements on import. If a Family or Type is not valid, Excel shows an Invalid Family or Invalid Type alert.

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

Click to preview and edit the sheet before exporting it. Reset Values in the Preview tab discards your edits and reloads the sheet. Click Update Model in the Preview tab to write the edited values directly to the Revit model, without exporting to Excel first.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-Preview-Edit.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export

Click to export the sheet to Google Drive or Excel. The Export Options dialog opens first. Open Excel File After Export is selected by default and opens the Excel file when the export is finished.

![SheetLink Export sheet](../../../assets\images\SheetLink\SH-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

The Excel file is editable and after editing can be imported through SheetLink.
{: .note }

Open the Instruction tab in your Excel file to view the color legend.
{: .note }

> **Yellow:** Type value  
> **Red:** Read-only value; this field cannot be edited.  
> **Grey:** Parameter does not exist for this element.
{: .note }

If you are changing the value of 'Type Parameters', ensure that you have the same value for all elements with the same 'Type ID'.
{: .note }

### Import

If you have made any edits to the file, import it and update the current model on Revit. Before importing the file, you can preview the sheet to be sure, and then complete the import. To preview, choose Preview Import in the Import dropdown and select the file. The file opens in the Preview tab, where you can edit it and click Update Model to import it.

![SheetLink Import file](../../../assets\images\SheetLink\SH-ImportFile.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

During import, choose a file from Google Drive or Excel and monitor the progress bar.
{: .note }
---

Let's go to the next tab to manage the Annotation Categories.

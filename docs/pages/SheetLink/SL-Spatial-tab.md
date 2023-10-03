---
layout: default
title: Spatial
parent: SheetLink User Guide
nav_order: 6
---

# SheetLink
{: .no_toc }
Export your Revit model data (by categories, elements, schedules) to Excel and Google Sheets. Edit the data and import it back to update the model.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Spatial

The first step is to select the SheetLink from the DiRootsOne menu and to choose the Spatial tab.
Make sure you have rooms or spaces created in the model, to be exported by SheetLink from DiRootsOne. 

Steps:

1. Use the checkboxes above the table to select the rooms or spaces to get the parameters.

![SheetLink selecting rooms or spaces](../../../assets\images\SheetLink\SH-Sp-SelectRooms.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Use the checkboxes above the table to select the Include Linked Files option.

![SheetLink including linked files](../../../assets\images\SheetLink\SH-Sp-IncludeLinked.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Rooms or Spaces

The search box will search for Rooms or Spaces contained in the Select column.

![SheetLink Searching for Rooms or Spaces](../../../assets\images\SheetLink\SH-Sp-SearchRoom.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Highlighted Elements

Select some rooms or spaces and right-click to choose to highlight the elements.

```yaml
# Note:  
Make sure you have the correct view opened to highlight the room.
If you do not have the correct view opened, the SheetLink can find the view, but could take a long time.
```

![SheetLink highlight Rooms or Spaces](../../../assets\images\SheetLink\SH-Sp-Higlight.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Instance and Read-only

After choosing the Rooms or Spaces, the SheetLink has options to see only the instance and read-only parameters.

Click on the table headers to select the instance parameters, for example.

```yaml
# Note:  
Rooms and Spaces do not have type parameters, so in this case only the instance and read-only options will appear.

```yaml
# Note:  
If selected the instance parameters, will show it in the green color.
If selected the read-only parameters, will show it in the red color.
```
  
![SheetLink select the parameters](../../../assets\images\SheetLink\SH-Sp-Instance.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Available Parameters

The search box will search for parameters contained in the Available Parameters column.  

![SheetLink Searching for available parameters](../../../assets\images\SheetLink\SH-Sp-SearchParam.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Selected Parameters

Parameter selection:
1. Select the parameters in the Available Parameters table.
2. Click on the arrows to add or remove from the Selected Parameters table.


![SheetLink adding and removing parameters](../../../assets\images\SheetLink\SH-Sp-AddRemove.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Selected Parameters

The search box will search for parameters contained in the Selected Parameters column.  

![SheetLink Searching for selected parameters](../../../assets\images\SheetLink\SH-Sp-SearchSelected.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Order the Selected Parameters

Use the arrows above the Selected Parameters table, to sort the parameters to be exported.  

![SheetLink order the selected parameters](../../../assets\images\SheetLink\SH-Sp-Order.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Reset Values

Select the Reset Values button to clear all the available parameters and selected parameters.

![SheetLink Reset Values](../../../assets\images\SheetLink\SH-Sp-Reset.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Preview/Edit

Click to preview and to edit the sheet before exporting it.
![SheetLink Preview](../../../assets\images\SheetLink\SH-Sp-Preview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.

![SheetLink Export sheet](../../../assets\images\SheetLink\SH-Sp-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

The Excel file is editable and after the editing of it you can import through SheetLink. The Spacial SheetLink allows you to create more rooms on Excel file exported, or export an empty Excel file template, to create rooms.

Caution, open the Instruction tab on Excel file to get the colors legend and other information. 

```yaml
# Note:
Yellow: Type Value.
Red: Read-only Value. This fields can not be edited.
Grey: Parameter does not exist for this element.
```

```yaml
# Note:
To create new Rooms or Spaces you should add new rows of information. Provide a minimum of Number, Name, and Phase parameter values to create correctly Rooms and Spaces. Please don’t input values to the GUID(hidden) and Element ID columns for new rows. Revit will automatically assign GUID and Element ID when elements are created.
```

Follow the example below.
![SheetLink creating rooms](../../../assets\images\SheetLink\SH-Sp-CreateRooms.png)  
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

Note if you have created rooms or spaces in the Excel file, these will be created on Revit and can now be assigned to the model.

![SheetLink assign created rooms](../../../assets\images\SheetLink\SH-Sp-CreateRoom.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


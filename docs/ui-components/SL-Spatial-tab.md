---
layout: default
title: Selection Tab
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

# Spatial

The first step is to select the SheetLink in the DiRootsOne menu and to choose the Spatial tab.
Make sure that you have rooms or spaces created in the model, to be exported by SheetLink from DiRootsOne. 

Steps:

1. On this tab, you can choose between to select parameters from Rooms or Spaces to export by SheetLink.
In the fisrt drop-down select witch option you want.

2. Use the checkboxes above the table to select the rooms or spaces to get the parameters.

![SheetLink selecting rooms or spaces](../../assets\images\SH-Sp-SelectRooms.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

3. Use the checkboxes above the table to select to Include Linked Files.

![SheetLink including linked files](../../assets\images\SH-Sp-IncludeLinked.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Rooms or Spaces

The search box will search for Rooms or Spaces contained in the Select column.

![SheetLink Searching for Rooms or Spaces](../../assets\images\SH-Sp-SearchRoom.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Highlighted Elements

Select some Rooms or Spaces and click with the right mouse button to choose to highlight the elements

```yaml
# Note:  
Make sure you have the correct view opened to highlight the room.
If you do not have the correct view opened, the SheetLink can find the view, but could take a long time.
```

![SheetLink highlight Rooms or Spaces](../../assets\images\SH-Sp-Higlight.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

## Instance and Read-only

After to choose the Rooms or Spaces, the SheetLink has options to see just instance and read-only parameters.

Click on the table headers to select the instance parameters for example.

```yaml
# Note:  
Rooms and Spaces do not have type parameters, so in this case will appear just the instance and read-only options.
```

```yaml
# Note:  
If selected the instance parameters, will show it in the green color.
If selecte the read-only parameters, will show it in the red color.
```
  
![SheetLink select the parameters](../../assets\images\SH-Sp-Instance.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Available Parameters

The search box will search for parameters contained in the Available Parameters column.  

![SheetLink Searching for available parameters](../../assets\images\SH-Sp-SearchParam.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

## Selected Parameters

Choosing parameters:
1. Select the parameters in the Available Parameters table.
2. Click in the arrows to add or remove from the Selected Parameters table.


![SheetLink adding and removing parameters](../../assets\images\SH-Sp-AddRemove.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Search Selected Parameters

The search box will search for parameters contained in the Selected Parameters column.  

![SheetLink Searching for selected parameters](../../assets\images\SH-Sp-SearchSelected.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Order the Selected Parameters

Use the arrows above the Selected Parameters table, to order the parameters to export.  

![SheetLink order the selected parameters](../../assets\images\SH-Sp-Order.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Reset Values

Select the Reset Values button to clean all the available parameters and selected parameters.

![SheetLink Reset Values](../../assets\images\SH-Sp-Reset.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

---

### Preview/Edit

Click to preview and to edit the sheet before exporting.
![SheetLink Preview](../../assets\images\SH-Sp-Preview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Export

Click to export the sheet to Google Drive or Excel.

![SheetLink Export sheet](../../assets\images\SH-Sp-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

The excel file is editable and after to editing it you can import through SheetLink. The Spacial SheetLink allows you to create more rooms on excel file exported, or export an empty excel file template, to create rooms.

Caution, open the Instruction tab on excel file to get the colors legend and other information. 

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

Follow the example bellow.
![SheetLink creating rooms](../../assets\images\SH-Sp-CreateRooms.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

### Import

If you have made some file edition, import it and update the schedules on Revit. Before importing the file, you can preview the sheet to make sure, and after conclude the import.

![SheetLink Import file](../../assets\images\SH-Sc-Import.png)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>

```yaml
# Note:  
- Import file from Google Drive or from Excel.
- Track the file import progress bar.
```

Note if you have created rooms or spaces in the excel file, it will be created on Revit, and now you can assign to the model.

![SheetLink assign created rooms](../../assets\images\SH-Sp-CreateRoom.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/revit-to-excel-sheetlink/).</sub>


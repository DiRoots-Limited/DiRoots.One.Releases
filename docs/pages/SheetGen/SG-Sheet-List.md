---
layout: default
title: Sheet list
parent: SheetGen User Guide
nav_order: 2
---

# SheetGen
{: .no_toc }
Batch create Drawing Sheets, place Views based on a pre-defined template, and easily manage Drawing Sheets revisions. Export and sheets/views lists to/from Excel.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Sheet List

The first step is to select the SheetGen from the DiRootsOne menu and choose the Sheet List tab.
This page will show all sheets in the project.

```yaml
# Note:
You must have at least one sheet created, to be used as a template in SheetGen.
```
### Sheet template

The first step before you start managing the sheets in SheetGen, is to create a sheet as a template. Basically, you need to create a sheet and fill it in, organizing the views as you wish. So, that will be used to generate new sheets on SheetGen, which will have the same settings as the template sheet. A sheet template is simply a sheet with some views in place.

![SheetGen sheet template example](../../../assets\images\SheetGen\SG-Sl-SheetTemplate.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

## New Sheet

1. Click on the New Sheet button, or right-click on an existing sheet and choose the Create Sheets from sheet template option.

![SheetGen create new sheet](../../../assets\images\SheetGen\SG-Sl-NewSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Fill the fields for the new sheet.

- Number of Sheets - put the number of sheets you want to create.
- Populate View from template - Create the new sheet with the same view settings as the template sheet.
- Keep Legends - you can choose to keep the legends as the template sheet.
- Keep Schedules - you can choose to keep the schedules as the template sheet.

![SheetGen fill the fields](../../../assets\images\SheetGen\SG-Sl-FillFields.png)
<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Select the existing sheet to be  used as a template for the new sheet.

### Search sheet

The search box will look for the sheets contained in the project.

![SheetGen search existing sheet](../../../assets\images\SheetGen\SG-Sl-SearchTemplate.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

4. Note that the new sheets appear in the list of sheets, but have not yet been created in the project. To complete the creation, click Apply.

![SheetGen apply new sheets](../../../assets\images\SheetGen\SG-Sl-ApplySheets.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Actions between the sheets

### Open Sheet

Right-click on the sheet and choose Open sheet option, to see the new sheet you have created.

![SheetGen open sheet](../../../assets\images\SheetGen\SG-Sl-OpenSheet.gif)
<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Duplicate Sheet

You can perform this action for individual sheets by right-clicking and choosing the Duplicate option, or you can perform this action in batch for several sheets simultaneously. To duplicate in batch, select the sheets you want, and in the Batch Actions list, choose Duplicate.

![SheetGen duplicate sheet](../../../assets\images\SheetGen\SG-Sl-DuplicateSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

1. Options for duplicating individual sheets.

- Set a number of copies
- Select the checkbox if you want to Duplicate Views from sheet
- Select the checkbox if you want to Keep Legends from sheet
- Select the checkbox if you want to Keep Schedules from sheet
- Select the checkbox if you want to Copy Revisions from sheet
- Select the checkbox if you want to Copy Title Block Parameter Values from sheet

```yaml
# Note:
If you prefer, you could select the checkbox Change Template for copies, so the list of sheets will be able to select another one.
```

![SheetGen duplicate individual sheet](../../../assets\images\SheetGen\SG-Sl-DuplicateIndividual.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Options for duplicating sheets in batch.

- Set a number of copies
- Select the checkbox if you want to Duplicate Views from sheet
- Select the checkbox if you want to Keep Legends from sheet
- Select the checkbox if you want to Keep Schedules from sheet
- Select the checkbox if you want to Copy Revisions from sheet
- Select the checkbox if you want to Copy Title Block Parameter Values from sheet

![SheetGen duplicate sheets in batch](../../../assets\images\SheetGen\SG-Sl-DuplicateBatch.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Delete Sheet

You can perform this action for individual sheets by right-clicking and choosing the Delete Sheet option, or you can perform this action in batch for several sheets simultaneously. To delete in batch, select the sheets you want, and in the Batch Actions list, choose Delete.

![SheetGen delete sheet](../../../assets\images\SheetGen\SG-Sl-DeleteSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Add parameters columns

By default, the list of sheets will only shows the the number and name of the sheet. Right-click under the column header and add the desired parameters.

![SheetGen add parameters columns](../../../assets\images\SheetGen\SG-Sl-AddParameters.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Edit sheets Number and Name

To edit the individual sheets, double-click on the cell you want to edit (number or name), and enter the text edit.

![SheetGen editing sheet](../../../assets\images\SheetGen\SG-Sl-EditCell.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import/Export excel file
 
If you have several sheets created in the project, this tool makes editing much easier. Export an Excel file, edit it as you want, then import it into SheetGen and update the number and name of the sheets. Note that in the Sheet Name header column has a lock icon, by activating this icon, the column will be locked for any editing.
In the Excel file exported you can numbering, naming, changing parameters and also add new rows to create new Sheets.

![SheetGen add sheets on excel file](../../../assets\images\SheetGen\SG-Sl-ExcelEdit.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

1. Export the excel file from sheet list.

![SheetGen export excel file from sheets](../../../assets\images\SheetGen\SG-Sl-ExportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Once you have edited the Excel file, import it to SheetGen.

![SheetGen import excel file](../../../assets\images\SheetGen\SG-Sl-Import.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Rename

SheetGen also allows sheets to be renamed in batch. To do this, select the sheets you want and click Rename. 
Then define a Prefix, a Suffix, enter the name that will be replaced and finally the name that will replace it.

![SheetGen rename sheets](../../../assets\images\SheetGen\SG-Sl-Rename.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Build Number and Build Name

1. Similar the Rename tool, SheetGen has a Build Number. Select the sheets you want and click Build Number.
Then set the Default Field Separator, Custom Field, Custom Separator, Counter and add or remove Parameters.

![SheetGen build number](../../../assets\images\SheetGen\SG-Sl-BuildNumber.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. For the Build Name tool, it is the same steps. Select the sheets you want and click to Build Name.
Then define the Default Field Separator, Custom Field, Custom Separator, and add or remove Parameters.

![SheetGen build name](../../../assets\images\SheetGen\SG-Sl-BuildName.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Save V/S Set

To organize the project sheets, especially when there are many sheets created, SheetGen offers the tool to save sets.
To create a new set, select the sheets you want to separate into this set and click on New Set, then assign a name to finish creating the set.

![SheetGen new set](../../../assets\images\SheetGen\SG-Sl-NewSet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can also add sheets to an existing set.

![SheetGen existing set](../../../assets\images\SheetGen\SG-Sl-ExistingSet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Filter by V/S Sets

Once you have organized the project sheets into sets, you can apply filters to make the work process easier.

![SheetGen apply filter](../../../assets\images\SheetGen\SG-Sl-FilterSet.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Clear editions

1. Click the Clear all Modifications button, and reset all edition applied to the sheet names and numbers, in the table view by the Rename, Build Name or Build Number commands.

![SheetGen clear all](../../../assets\images\SheetGen\SG-Sl-ClearAll.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Click on the Clear Staging button, and clear the staging cached modifications.

```yaml
# Note:
With this tool, only changes that have not yet been applied will be cleared. Changes that have been applied cannot be cleared.
```

![SheetGen clear staging](../../../assets\images\SheetGen\SG-Sl-ClearStaging.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
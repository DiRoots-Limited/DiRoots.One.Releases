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

The first step is to select the SheetGen in the DiRootsOne menu and to choose the Sheet List tab.
On this page will show all existing sheets in the project.

```yaml
# Note:
You must have at least one sheet created, to be used as a template in SheetGen.
```

## New Sheet

1. Click on the New Sheet button, or click with the right mouse button on an existing sheet and choose the option Create Sheets from template.

![SheetGen create new sheet](../../assets\images\SG-Sl-NewSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

2. Fill the fields about the new sheet.

- Number of Sheets - put the number of sheets you want to create.
- Populate View from template - Create the new sheet with the same view settings as the template sheet.
- Keep Legends - you can choose to keep the legends as the template sheet.
- Keep Schedules - you can choose to keep the schedules as the template sheet.

![SheetGen fill the fields](../../assets\images\SG-Sl-FillFields.png)
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

3. Select the existing sheet that will be assign as the template for the new sheet.

### Search sheet

The search box will search for sheets contained in the projet.

![SheetGen search existing sheet](../../assets\images\SG-Sl-SearchTemplate.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

4. Note that the new sheets appear in the list of sheets but have not yet been created in the project. To complete the creation, click Apply.

![SheetGen apply new sheets](../../assets\images\SG-Sl-ApplySheets.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

---

## Actions between the sheets

### Open Sheet

Click with the right mouse button on the sheet and choose the option Open Sheet, to view the new sheet created.

![SheetGen open sheet](../../assets\images\SG-Sl-OpenSheet.gif)
<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

### Duplicate Sheet

You can perform this action for individual sheets by clicking the right mouse button and choosing the Duplicate option, or you can perform this action in batch for several sheets simultaneously. To duplicate in batch, select the sheets you want, and in the Batch Actions list, choose Duplicate.

![SheetGen duplicate sheet](../../assets\images\SG-Sl-DuplicateSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

1. Options to duplicate individual sheets.

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

![SheetGen duplicate individual sheet](../../assets\images\SG-Sl-DuplicateIndividual.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

2. Options to duplicate sheets in batch.

- Set a number of copies
- Select the checkbox if you want to Duplicate Views from sheet
- Select the checkbox if you want to Keep Legends from sheet
- Select the checkbox if you want to Keep Schedules from sheet
- Select the checkbox if you want to Copy Revisions from sheet
- Select the checkbox if you want to Copy Title Block Parameter Values from sheet

![SheetGen duplicate sheets in batch](../../assets\images\SG-Sl-DuplicateBatch.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

### Delete Sheet

You can perform this action for individual sheets by clicking the right mouse button and choosing the Delete Sheet option, or you can perform this action in batch for several sheets simultaneously. To duplicate in batch, select the sheets you want, and in the Batch Actions list, choose Delete.

![SheetGen delete sheet](../../assets\images\SG-Sl-DeleteSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

### Add parameters columns

By default, the list of sheets will only show the sheet number and the sheet name. Click the right mouse button under the column header and add the desired parameters.

![SheetGen add parameters columns](../../assets\images\SG-Sl-AddParameters.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

---

## Edit sheets Nuumber and Name

To edit the sheets individually, set double-click on the cell you want to edit (number or name), and enter text editing.

![SheetGen editing sheet](../../assets\images\SG-Sl-EditCell.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

### Import/Export excel file

If you have several sheets created in the project, this tool makes editing much easier. Export an excel file, edit it as you wish, then import it into SheetGen and update the number and name of the sheets. Note that in the Sheet Name header column has a lock icon by activating this icon, the column will be locked for any editing.

![SheetGen editing sheet](../../assets\images\SG-Sl-LockColumn.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

1. Export the excel file from sheet list.

![SheetGen export excel file from sheets](../../assets\images\SG-Sl-ExportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

2. Import exel file to update the sheet list.

![SheetGen import excel file](../../assets\images\SG-Sl-ImportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

### Rename

SheetGen also allows sheets to be renamed in batch. To do this, select the sheets you want and click Rename. 
Then define a Prefix, a Suffix, enter the name that will be replaced and finally the name that will replace it.

![SheetGen rename sheets](../../assets\images\SG-Sl-Rename.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

### Build Number and Build Name

1. Similar to the Rename tool, the SheetGen have the Build Number. Select the sheets you want and click to Build Number.
Then define the Default Field Separator, Custom Field, Custom Separator, Counter and add or remove Parameters.

![SheetGen build number](../../assets\images\SG-Sl-BuildNumber.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

2. For the Build Name tool, it is the same steps. Select the sheets you want and click to Build Name.
Then define the Default Field Separator, Custom Field, Custom Separator, and add or remove Parameters.

![SheetGen build name](../../assets\images\SG-Sl-BuildName.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetLink](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>
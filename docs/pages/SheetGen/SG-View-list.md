---
layout: default
title: View list
parent: SheetGen User Guide
nav_order: 3
---

# SheetGen
{: .no_toc }
Batch create Drawing Sheets, place Views based on a pre-defined template, and easily manage Drawing Sheets revisions. Export and sheets/views lists to/from Excel.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# View List

After creating the project sheets and organizing their names and sets, we go to the View List tab to define the views for each sheet.

1. To get started, click on the View Manager button to manage the views in your model.
On this page, you'll find all the views in the model, and in All column, choose whether you want to manage all the views or a specific type of view.

![SheetGen manage views](../../../assets\images\SheetGen\SG-Vl-ManageView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Views tab

### Open View

Right-click on the view and choose Open view.

![SheetGen open view](../../../assets\images\SheetGen\SG-Vl-OpenView.png)
<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Duplicate View

You can perform this action for individual views by right-clicking and selecting the Duplicate option, or you can perform this action in batch for several views simultaneously. To duplicate in batch, select the views you want, and in the Batch Actions list, choose Duplicate.

![SheetGen duplicate views](../../../assets\images\SheetGen\SG-Vl-DuplicateView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Duplicate View with Detailing

If you right-click, and click Duplicate View Duplicate with Detailing, both the model geometry and the detail geometry are copied into the new view.

### Duplicate View as a Dependant

All dependent views, remain synchronous with the primary view and all other dependent views, so that when view-specific changes (such as view scale and annotations) are made in one view, they are reflected in all views.

```yaml
# Note:
You cannot create a dependent view from another dependent view.
```

### Delete View

You can perform this action for an individual view by clicking the right mouse button and choosing the Delete view option, or you can perform this action in batch for several views simultaneously. To Delete in batch, select the views you want, and in the Batch Actions list, choose Delete.

![SheetGen delete sheet](../../../assets\images\SheetGen\SG-Vl-DeleteView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Add parameters columns

By default, the list of views will only show the name of the view and the list of view. Right-click under the column header and add the desired parameters.

![SheetGen add parameters columns](../../../assets\images\SheetGen\SG-Vl-AddParameters.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Import/Export excel file

If you have several views created in the project, this tool makes editing much easier. Export an Excel file, edit it to the name as you wish, then import it into SheetGen and update the views.

![SheetGen export view](../../../assets\images\SheetGen\SG-Sl-ExcelEdit.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

1. Export the excel file from view list.

![SheetGen export excel file from sheets](../../../assets\images\SheetGen\SG-Sl-ExportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2.  Once you have edited the Excel file, import it to SheetGen.

![SheetGen import excel file](../../../assets\images\SheetGen\SG-Vl-Import.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Rename

SheetGen also allows views to be renamed in batch. To do this, select the views you want and click Rename. 
Then define a Prefix, a Suffix, enter the name that will be replaced and finally the name that will replace it.

![SheetGen rename views](../../../assets\images\SheetGen\SG-Vl-Rename.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Build Name

Like the Rename tool, the SheetGen have the Build Name. Select the views you want and click to Build Name.
Then set the Default Field Separator, Custom Field, Custom Separator and add or remove Parameters.

![SheetGen build name](../../../assets\images\SheetGen\SG-Vl-BuildName.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Save V/S Set

To organize the views of the model, especially when there are many views created, SheetGen offers the tool to save sets of views.
To create a new set, select the views you want to separate into this set and click on New Set, then assign a name to finish creating the set.

![SheetGen new set](../../../assets\images\SheetGen\SG-Vl-NewSet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can also add views to an existing set.

![SheetGen existing set](../../../assets\images\SheetGen\SG-Vl-AddtoSet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Filter by V/S Sets

Once you have organized the model views into sets, you can apply filters to make the work process easier.

![SheetGen existing set](../../../assets\images\SheetGen\SG-Vl-FilterSet.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Clear editions

1. Click on the Clear all Modifications button, and reset all edition applied to view names in the table view made by the Rename or Build Name commands.

![SheetGen clear all](../../../assets\images\SheetGen\SG-Vl-Clean.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## View Template tab

This tab allows you to manage the view templates you have created by renaming or creating a build name.

1. Select the view templates you want and click Rename. Assign a Prefix, Suffix, the name to Replace and the new Name.

![SheetGen rename view templates](../../../assets\images\SheetGen\SG-Vl-RenameViewTemplate.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Select the view templates that you want and click to Build Name. In this case, you can manage the Default Field Separator, Custom Field, Custom Separator and assign the view parameters to build the name.

![SheetGen view templates build name](../../../assets\images\SheetGen\SG-Vl-BuildNameView.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Import/Export sheets

Return to the List of Views tab and click on the Export button to generate an Excel file. In the Excel file exported you can numbering, naming, changing parameters and also add new rows to create new Sheets.

![SheetGen export sheets](../../../assets\images\SheetGen\SG-Vl-ExportSheets.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

1. Export the excel file from sheet list.

![SheetGen export excel file from sheets](../../../assets\images\SheetGen\SG-Sl-ExportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>

2. Once you have edited the Excel file, import it to SheetGen.

![SheetGen import excel file](../../../assets\images\SheetGen\SG-Sl-Import.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen](https://diroots.com/revit-plugins/batch-create-revit-sheets-and-place-views-with-sheetgen/).</sub>


---

## Apply filter by template

As with the filters by set, apply filters by sheet templates and see the views assigned to each template.

![SheetGen apply filters](../../../assets\images\SheetGen\SG-Vl-Template.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Filter by V/S Sets

Apply filters to the sheet sets created.

![SheetGen apply filters](../../../assets\images\SheetGen\SG-Vl-FilterbySet.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Add views to sheets

The third column shows the views to be applied to the sheets. To add them, simply click on the "more options" button and then Select. Then choose the view you want and click Select to add it to the sheet. The Views columns allow adding more than one view per sheet.

![SheetGen add views](../../../assets\images\SheetGen\SG-Vl-AddViewSheet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

In the select view panel you can choose the view type in the list, select some parameters and if you want to see just the unapplied views, click Hide Placed Views and then see only the unselected views.

![SheetGen add views](../../../assets\images\SheetGen\SG-Vl-AddViewSettings.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Remove view from sheet

To remove a view from the sheet, click on the "more options" button, and choose the Remove option, or in the select view panel, select the Remove View checkbox, search the current view and click on the Remove button.

![SheetGen remove views](../../../assets\images\SheetGen\SG-Vl-RemoveView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Open view

Click on the "more options" button and select Open View. Note that the current view will be opened in Revit.

![SheetGen open views](../../../assets\images\SheetGen\SG-Vl-OpenView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Clear Staging

Click on the Clear Staging button, and clear the staging cached modifications.

```yaml
# Note:
With this tool, only changes that have not yet been applied will be cleared. Changes that have been applied cannot be cleared.
```

![SheetGen clear staging](../../../assets\images\SheetGen\SG-Vl-Clear.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>














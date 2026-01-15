---
layout: default
title: View list
parent: SheetGen User Guide
nav_order: 3
---

# SheetGen
{: .no_toc }
Batch create Sheets and Placeholder sheets, place Views on Sheets based on a pre-defined template, and easily manage Drawing Sheets revisions. Export sheets/views lists to/from Excel.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# View List

After creating the project sheets and organizing their names and sets, we go to the View List tab to define the views for each sheet.

1. To get started, click on the View Manager button to manage the views in your model.
On that tool, you'll find all the views in the model, and in All column, choose whether you want to manage all the views or a specific type of view. For more information visit the [View Manager User Guide](/docs/ViewManager-user-guide)

![SheetGen manage views](../../../assets\images\SheetGen\SG-Vl-ManageView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Import/Export excel file

If you have several views you want to place in the project, exporting to excel makes editing much easier. Export an Excel file, edit it as you wish, then import it into SheetGen to update the views placements.

1. Export the excel file from view list.

![SheetGen export views in sheets](../../../assets\images\SheetGen\SG-Vl-ExportSheets.png)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2.  Once you have edited the Excel file, import it to SheetGen.

![SheetGen import excel file](../../../assets\images\SheetGen\SG-Vl-Import.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

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

---

Let's go to the next tab to manage the Revision List.














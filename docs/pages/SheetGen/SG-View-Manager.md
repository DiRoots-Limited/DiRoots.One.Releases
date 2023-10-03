---
layout: default
title: View Manager
parent: SheetGen User Guide
nav_order: 5
---

# SheetGen
{: .no_toc }
Batch create Drawing Sheets, place Views based on a pre-defined template, and easily manage Drawing Sheets revisions. Export and sheets/views lists to/from Excel.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Views tab

The View Manager is a tool for managing the existing views in the project and performing actions such as renaming them, organizing them by sets, exporting them and even duplicating them. 

## Views

In the second column choose the view type to show in this column.

![View Manager manage views](../../../assets\images\SheetGen\SG-Vm-ViewType.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Add parameters columns

By default, the list of views will only show the name of the view and the list of view. Right-click under the column header and add the desired parameters.

![View Manager add parameters columns](../../../assets\images\SheetGen\SG-Vm-Parameters.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Manual actions

### Open View

Right-click on the view and select the Open View option.

![View Manager manage views](../../../assets\images\SheetGen\SG-Vm-OpenView.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Duplicate Views

Right-click on the view and it will show you three options for duplicating it.

1. Duplicate: duplicate view without details.

2. Duplicate with Detailing: duplicate view with all detail geometry and annotation into the new view.

![View Manager duplicate view](../../../assets\images\SheetGen\SG-Vm-DuplicateManually.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Delete

Right-click on the view and select the Delete option to remove view.

![View Manager delete view](../../../assets\images\SheetGen\SG-Vm-DeleteManually.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Batch actions

### Duplicate Views

Select the views and click on the Batch Actions list.

1. Duplicate: duplicate views without details.

2. Duplicate with Detailing: duplicate views with all detail geometry and annotation into the new views.

3. Duplicate as a Dependant: all dependent views, remain synchronous with the primary view and all other dependent views, so that when view-specific changes (such as view scale and annotations) are made in one view, they are reflected in all views.

![View Manager duplicate view](../../../assets\images\SheetGen\SG-Vm-DuplicateBatch.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Delete

Select the views and click on the Delete button.

![View Manager delete view](../../../assets\images\SheetGen\SG-Vm-DeleteBatch.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Import/Export

Export an Excel file, edit it as you want, then import it into View Manager and update the number and name of the sheets. You can also import this Excel file in another project to use as a template.

1. Export the excel file from view list.

![View Manager export excel file from views](../../../assets\images\SheetGen\SG-Vm-Export.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Import exel file to update the views list.

![View Manager import excel file](../../../assets\images\SheetGen\SG-Vm-Import.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Rename

View Manager also allows views to be renamed in batch. To do this, select the views you want and click to Rename. 
Then define a Prefix, a Suffix, enter the name that will be replaced and finally the name that will replace it.

![View Manager rename views](../../../assets\images\SheetGen\SG-Vm-Rename.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub

## Build Name

For the Build Name tool, select the views you want and click to Build Name.
Then define the Default Field Separator, Custom Field, Custom Separator, and add or remove Parameters.

![View Manager build name](../../../assets\images\SheetGen\SG-Vm-BuildName.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Save V/S Set

To organize the project views, especially when there are many views created, View Manager offers the tool to save sets.
To create a new set, select the views you want to separate into this set and click on New Set, then assign a name to finish creating the set.

![View Manager new set](../../../assets\images\SheetGen\SG-Vm-SaveSet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Filter by V/S Sets

Once you have organized the project views into sets, you can apply filters to make the work process easier.

![View Manager apply filter](../../../assets\images\SheetGen\SG-Vm-FilterSet.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Clear all modifications

Click the Clear all Modifications button, and reset all edits applied to the view names and numbers, in the table view using the Rename command.

![View Manager clear all](../../../assets\images\SheetGen\SG-Vm-Clear.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

# View Templates tab

Manage all View Templates in this tab.

## Rename

View Manager also allows view templates to be renamed in batch. To do this, select the view templates you want and click to Rename. 
Then define a Prefix, a Suffix, enter the name that will be replaced and finally the name that will replace it.

![View Manager rename view templates](../../../assets\images\SheetGen\SG-Vt-RenameTemplate.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub

## Build Name

For the Build Name tool, select the view templates you want and click to Build Name.
Then define the Default Field Separator, Custom Field, Custom Separator, and add or remove Parameters.

![View Manager build name](../../../assets\images\SheetGen\SG-Vt-BuildNameTemplate.gif)

<sub>Note: the version on the image may not reflect the [latest version of SheetGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
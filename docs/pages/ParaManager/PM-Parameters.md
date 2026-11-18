---
layout: default
title: Parameters
parent: ParaManager
nav_order: 1
nav_sections:
  - title: "Add Parameters"
    anchor: add-parameters
  - title: "Import/Export"
    anchor: importexport
---

<span id="paramanager"></span>

# ParaManager
{: .no_toc }
Manage Revit parameters inside project and family environments. Create new parameters, modify existing parameters, export/import parameters to/from Excel and Shared Parameters file.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Parameters

Let's start with the Parameters tab. In this window you can create new parameters, import and export them and make some batch edits.

## Add Parameters

Click on the Add Parameters button to create a new parameter.

![ParaManager add parameter](../../../assets\images\ParaManager\PM-Pm-AddParameter.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Edit the new parameter

1. Double-click on the new parameter and rename it.

2. In the Discipline column, open the list and assign the new parameter to a specific Discipline.

3. In the Type of Parameter column, choose the ideal type for it.

4. Select the group to assign the parameter to, in the Group Under column.

5. Choose between Instance or Type parameter in the last default column.

![ParaManager edit new parameter](../../../assets\images\ParaManager\PM-Pm-EditParameter.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Individual actions

1. Right-click on the parameter and select Duplicate Parameter.

2. Right-click on the parameter and click to Delete Parameter.

![ParaManager individual actions](../../../assets\images\ParaManager\PM-Pm-IndividualActions.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Batch Actions

Select the parameter and click to batch editing. Batch editing allows you to delete or duplicate parameters.

![ParaManager batch actions](../../../assets\images\ParaManager\PM-Pm-Batch.png)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Show Existing Parameters

Select the Show Existing Parameters checkbox to list the parameters that already exist in the project together with the new ones. Clear it to list only the new parameters.

![ParaManager existing parameters](../../../assets\images\ParaManager\PM-Pm-ExistingParameter.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Additional Attributes

Right-click on the column header and select additional attributes for the columns.

![ParaManager existing parameters](../../../assets\images\ParaManager\PM-Pm-AdditionalAttibutes.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Import/Export

### Export to Excel

Click on the Import/Export list, and select Export to Excel option. The next step is to select the parameters and click to export.

In the Save dialog, choose the file type: .xlsm (default), .xlsx or .xls. Only the .xlsm file includes the category selector. Select Open Excel file after export to open the file when the export finishes.

![ParaManager export parameters to excel](../../../assets\images\ParaManager\PM-Pm-ExporttoExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import from Excel

Click on the Import/Export list, and select Import from Excel option. Select the Excel file and then select the parameters to import.

You can select a .xls, .xlsx or .xlsm file.

{: .note }
An Excel file exported from the Families tab cannot be imported into a project. ParaManager shows a message and imports nothing.

![ParaManager import parameters from excel](../../../assets\images\ParaManager\PM-Pm-ImportParameters.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export Shared Parameters

Click on the Import/Export list, and select Export Shared Parameters option. The next step is to select the parameters and click to export the txt file.

![ParaManager export shared parameters](../../../assets\images\ParaManager\PM-Pm-ExportShared.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import Shared Parameters

If you have a txt Parameters file, you can import it into the current project. Click on the Import/Export list, and select Import Shared Parameters option.
The next step is to select the file and choose the parameters to import.

![ParaManager import shared parameters](../../../assets\images\ParaManager\PM-Pm-ImportShared.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Parameters

The search box filters the parameters by parameter name or value.

![ParaManager search parameters](../../../assets\images\ParaManager\PM-Pm-SearchParameters.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

{: .note }
Click Next button to go to the Categories tab and assign the parameters to categories.

---

Let's go to the next tab to manage the Categories.
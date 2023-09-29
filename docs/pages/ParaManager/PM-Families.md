---
layout: default
title: Families
parent: ParaManager User Guide
nav_order: 4
---

# ParaManager
{: .no_toc }
Manage Revit parameters inside project and family environments. Create new parameters, modify existing parameters, export/import parameters to/from Excel and Shared Parameters file.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Families

In this window we can create parameters assigned only to families, that is, the parameters created in this tab will not appear in the project's parameter list.
Let's get to know the tool:

## Add Parameter

You can create new parameters to add to the families. Click on the Add Parameter button and define the data.

![ParaManager Add Parameter](../../../assets\images\ParaManager\PM-Fm-AddParameter.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Manual actions

Right-click on the parameter and select Duplicate or Delete option.

![ParaManager duplicate and delete](../../../assets\images\ParaManager\PM-Fm-DuplicateDelete.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Batch Actions

Select the parameters and choose from the Batch actions list:

1. Duplicate parameters.

![ParaManager duplicate in batch](../../../assets\images\ParaManager\PM-Fm-DuplicateBatch.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Delete parameters.

![ParaManager delete in batch](../../../assets\images\ParaManager\PM-Fm-DeleteBatch.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Modify

Modify allows you to add a suffix and/or prefix to parameters marked with a checkbox. It also allows you to replace part of the parameter name with a new value.

![ParaManager modify](../../../assets\images\ParaManager\PM-Fm-Modify.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:
Note that manual name modification in the list view is allowed.
```

### Clear modifications

By clicking the clear button ParaManager will restore original parameter names.

```yaml
# Note:
This tools can be used before applying Modify functionality or manually editing names.
```

![ParaManager clear modify](../../../assets\images\ParaManager\PM-Fm-Clear.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Import/Export

### Export to Excel

Click on the Import/Export list, and select Export to Excel option. The next step is to select the parameters and click to export.

![ParaManager export parameters to excel](../../../assets\images\ParaManager\PM-Fm-ExportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import from Excel

Click on the Import/Export list, and select Import from Excel option. Select the Excel file and then select the parameters to import.

![ParaManager import parameters from excel](../../../assets\images\ParaManager\PM-Fm-ImportExcel.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Export Shared Parameters

Click on the Import/Export list, and select Export Shared Parameters option. The next step is to select the parameters and click to export the txt file.

![ParaManager export shared parameters](../../../assets\images\ParaManager\PM-Fm-ExportShared.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Import Shared Parameters

If you have a txt Parameters file, you can import it into the current project. Click on the Import/Export list, and select Import Shared Parameters option.
The next step is to select the file and choose the parameters to import.

![ParaManager import shared parameters](../../../assets\images\ParaManager\PM-Fm-ImportShared.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Search Families

The search box will search for families contained in the Schedules.

![ParaManager search families](../../../assets\images\ParaManager\PM-Fm-Search.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Hide un-checked

Select this checkbox to hide the families and parameters unselected.

![ParaManager hide un-checked](../../../assets\images\ParaManager\PM-Fm-HideUnchecked.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Parameters from Nested Elements

The management of family parameters can also be done in nested families. Click on a family and in the Revit Modify menu, click on Edit Family.
Note that in the DiRootsOne package menu, the ParaManager plugin will be active, access it to manage the parameters of the nested family.

### Parameters tab

This tab is similar to the parameter management tab in general, but in this case the parameters will be replicated like in Revit's Family Types window.

![ParaManager Parameters tab](../../../assets\images\ParaManager\PM-Fm-ParametersFamily.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Nested Instance

This tab contains a list of all the instance nested items in this family. So when you click on the elements, the table on the right will show all the parameters of the current element.

![ParaManager nested instance](../../../assets\images\ParaManager\PM-Fm-NestedInstance.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

Select the paramenter and click on Add Nested Parameters, and then select if you want to create a instance or type level parameter.

![ParaManager add nested instance](../../../assets\images\ParaManager\PM-Pm-AddNestedInstance.png)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Nested Type

This tab contains a list of all the type nested items in this family. So when you click on the elements, the table on the right will show all the parameters of the current element.

![ParaManager nested type](../../../assets\images\ParaManager\PM-Fm-NestedType.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

Select the paramenter and click on Add Nested Parameters, and then select if you want to create a instance or type level parameter.

![ParaManager add nested instance](../../../assets\images\ParaManager\PM-NT-AddNestedType.png)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Nested Families

This tab contains a list of all the nested families. So when you click on the elements, the table on the right will show all the parameters of the current element.

![ParaManager nested type](../../../assets\images\ParaManager\PM-NF-NestedFamilies.png)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Shared Editor

This tab is similar to the Shared Editor management tab in general, but in this case the parameters will be replicated like in Revit's Family Types window.

![ParaManager Shared Editor](../../../assets\images\ParaManager\PM-Se-SharedEditor.png)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
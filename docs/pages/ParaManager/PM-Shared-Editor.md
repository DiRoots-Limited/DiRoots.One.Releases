---
layout: default
title: Shared Editor
parent: ParaManager User Guide
nav_order: 5
---

# ParaManager
{: .no_toc }
Manage Revit parameters inside project and family environments. Create new parameters, modify existing parameters, export/import parameters to/from Excel and Shared Parameters file.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Shared Editor

The Shared Parameter Editor window is very similar to Revit's parameter management functionality, but with a very user-friendly interface, and by using DiRootsOne's ParaManager, you can manage all your project parameters, shared parameters, by families and categories in one place. Lets start the steps:

## Load Shared Parameters File (SP File)

Click on the Load SP File button and choose the parameters file to import.

![ParaManager import shared parameters](../../../assets\images\ParaManager\PM-Se-LoadFile.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Add Parameter

Create new shared parameters by clicking on the Add Parameter button and then defining the data.

![ParaManager add shared parameters](../../../assets\images\ParaManager\PM-Se-AddParameter.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

### Manual actions

1. Right-click on the parameter and select the Duplicate or Delete option.

![ParaManager duplicate and delete](../../../assets\images\ParaManager\PM-Se-ManualDuplicateDelete.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Right-click on the parameter and select New Guid to generate a new Guid to replace the current one.

![ParaManager duplicate and delete](../../../assets\images\ParaManager\PM-Se-ManualGuid.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Batch Actions

Select the parameters and choose from the Batch actions list:

1. Duplicate shared parameters.

![ParaManager duplicate in batch](../../../assets\images\ParaManager\PM-Se-BatchDuplicate.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Delete shared parameters.

![ParaManager delete in batch](../../../assets\images\ParaManager\PM-Se-BatchDelete.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Generate New Guid.

![ParaManager new guid](../../../assets\images\ParaManager\PM-Se-GuidBatch.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Groups

To create a shared parameter you need at least one group to assign it to, so we have the default group, but you can also create new groups as in the Shared Parameters window in Revit.
Click on the Groups button to manage it by creating, editing and removing groups.

![ParaManager add shared parameters](../../../assets\images\ParaManager\PM-Se-Groups.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Rename

Rename button allows you to add a suffix and/or prefix to parameters marked with a checkbox. Ir also allows you to replace part of the parameter name with a new value.

![ParaManager rename](../../../assets\images\ParaManager\PM-Se-Rename.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:
Note that manual name modification in the list view is allowed.
```

### Clear modifications

The clear button has options to clean all changes made in the current ParaManager session or to unload files without saving the changes.

![ParaManager clear modifications](../../../assets\images\ParaManager\PM-Se-Clear.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Search Shared Parameters

The search box will search for shared parameters contained in the Schedules.

![ParaManager search shared parameters](../../../assets\images\ParaManager\PM-Se-Search.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Save

When you have finished managing the shared parameters, save them in a txt file so that they can be used in other projects.

![ParaManager save shared parameters](../../../assets\images\ParaManager\PM-Se-Save.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
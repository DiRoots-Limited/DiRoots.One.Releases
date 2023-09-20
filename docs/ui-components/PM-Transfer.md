---
layout: default
title: Transfer
parent: ParaManager User Guide
nav_order: 3
---

# ParaManager
{: .no_toc }
Manage Revit parameters inside project and family environments. Create new parameters, modify existing parameters, export/import parameters to/from Excel and Shared Parameters file.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Transfer

In this tab, the Transfer tool allows to "copy" paramaters from families to another one.
There are two ways to choose the family to copy the parameters:

1. Select Family: click on this button and select the element in the view to manage it parameters.

![ParaManager select element](../../assets\images\PM-Tr-SelectFamily.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager](https://diroots.com/revit-plugins/manage-revit-parameters-in-projects-and-families-with-paramanager/).</sub>

2. Open the Family list: select the family in this list to transfer the parameters.

![ParaManager select family](../../assets\images\PM-Tr-SelectFamilyList.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager](https://diroots.com/revit-plugins/manage-revit-parameters-in-projects-and-families-with-paramanager/).</sub>

---

## Modify

Modify will allow you to add a suffix and/or prefix to parameters marked with a checkbox. Also, it provides the ability to replace part of the parameter name with a new value.

![ParaManager modify](../../assets\images\PM-Tr-Modify.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager](https://diroots.com/revit-plugins/manage-revit-parameters-in-projects-and-families-with-paramanager/).</sub>

```yaml
# Note:
Note that manual name modification in the list view is allowed.
```

### Clear Modify

By clicking the clear button ParaManager will restore original parameter names.

```yaml
# Note:
This tools can be used before applying Modify functionality or manually editing names.
```

![ParaManager clear modify](../../assets\images\PM-Tr-Clear.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager](https://diroots.com/revit-plugins/manage-revit-parameters-in-projects-and-families-with-paramanager/).</sub>

### Hide un-checked

Select this checkbox to hide the families unselected.

![ParaManager hide un-checked](../../assets\images\PM-Tr-HideUnselected.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager](https://diroots.com/revit-plugins/manage-revit-parameters-in-projects-and-families-with-paramanager/).</sub>

---

## Apply

After selecting the family in the table on the left, select the parameters to be transferred/copied to the other family.
Now select the family that should receive the selected parameters in the table on the right. To complete, click Apply to transfer the parameters to the chosen family.

![ParaManager Apply](../../assets\images\PM-Tr-Apply.gif)

<sub>Note: the version on the image may not reflect the [latest version of ParaManager](https://diroots.com/revit-plugins/manage-revit-parameters-in-projects-and-families-with-paramanager/).</sub>

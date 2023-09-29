---
layout: default
title: Worksets
parent: FamilyReviser User Guide
nav_order: 4
---

# FamilyReviser
{: .no_toc }
Manage your Revit families (rename, add prefix and suffix, save them in an organised way) and worksets (modify worksets by category or create your own rules).
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Worksets

The FamilyReviser also allows you to manage and create worksets from categories. Let’s start learning more about:

1.	Choose the categories you want to manage by selecting the radio button between Whole Model, Active View or Current Selection.

![FamilyReviser view categories](../../../assets\images\FamilyReviser\FR-Ws-SelectCat.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2.	Open the list of categories to choose which one to assign the workset to. By default, all categories will be selected, but you can choose as many as you like.

![FamilyReviser select categories](../../../assets\images\FamilyReviser\FR-Ws-Categories.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3.	Now click on the Manage Workset button, to open the Worksets panel. Manage the current worksets or create new worksets, and save them.

![FamilyReviser manage workset](../../../assets\images\FamilyReviser\FR-Ws-ManageWorkset.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

4. The next step is to select the families of the selected categories and select the corresponding workset in the WorkSet column.

![FamilyReviser assign workset](../../../assets\images\FamilyReviser\FR-Ws-AssignWorkset.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

```yaml
# Note:
Make sure everything is correct and click Apply to save the changes.
```

## Create Rules

This tool allows to filter the categories by rules to assign the corresponding worksets.

1. Click on the New button to create a condition and then, in the first list select the categories to filter.

2. Select the field you want to filter by from the second list and choose the condition (Equal, Not equal, Contains).

3.	Now, in the text field, enter the value to be filtered and click on Apply to make the filter.

![FamilyReviser create rules](../../../assets\images\FamilyReviser\FR-Ws-Rule.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Save Rule

Click the Save button and choose a location to save the rule for use in another project.

### Open Rule

You can create a repository to save the rules and then, when you are working in a new project, you don’t need to create the rule again, you can just Open a saved rule and apply in the current model.

## Rules panel

In this panel, manage all the existing rules to be applied in the current model. Select a rule to see it in the table.

![FamilyReviser rules panel](../../../assets\images\FamilyReviser\FR-Ws-ManageRules.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Refresh

Use this button to refresh the table whenever you make any changes, to get the new data.

![FamilyReviser refresh](../../../assets\images\FamilyReviser\FR-Ws-Refresh.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Undo

This button resets the settings not applied to the model. If you want to restore information, click the Undo button.

![FamilyReviser undo changes](../../../assets\images\FamilyReviser\FR-Ws-Undo.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
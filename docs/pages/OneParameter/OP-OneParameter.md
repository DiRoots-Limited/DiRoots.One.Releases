---
layout: default
title: OneParameter
parent: OneParameter
nav_exclude: true
nav_order: 1
nav_sections:
  - title: "Select Parameter"
    anchor: select-parameter
---

<span id="oneparameter"></span>

# OneParameter
{: .no_toc }
An Autodesk Revit plugin to bulk edit values from Instance/Type Parameters in your Revit model with a single click.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


Edit values from Instance/Type Parameters in your Revit model in bulk. With OneParameter, you can add prefixes/suffixes, replace, and clear multiple Parameter values with a single click.

{: .new }
To make it easier to see the parameter values, use a schedule view.

## Select Parameter

1. Use the radio button to choose the scope: Whole Model, Active View or Selection. Selection works only on the elements selected in Revit. If elements are selected when you start OneParameter, it opens in Selection. When you return to the window after changing the selection in Revit, the lists refresh.

2. First, the user has to select a parameter to manage. Use the Categories list to choose the categories whose parameters are shown. In the table on the left, use the Parameter Type list to filter the parameters by Instance or Type.

   ![Filter Instance and Type parameters](../../../assets\images\OneParameter\OP-FilterInstanceType.gif)<br />
   <sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Use the searchbox to search for a specific parameter.

   ![Search parameters](../../../assets\images\OneParameter\OP-Search.gif)<br />
   <sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

4. Click on the buttons below the table to sort the parameters by Type or Instance. Click the same button again to clear the sorting.

![Sort parameters](../../../assets\images\OneParameter\OP-Sort.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Filter by Parameter Value

After selecting a parameter, enter a value assigned to the parameter to be searched for.

1. Choose how to match the value: Contained (the value is part of the parameter value), Entire value, Empty or Not Empty. For Empty and Not Empty no value is needed.

2. Enable or disable the "Case Sensitive" option (the Aa button) to find values with upper and lower case letters.

3. Click Find. The elements found are listed in a grid with the columns Category, Family, Type, Element ID, Current Value and New Value. In family documents a Nested column is also shown. In the bottom left corner, "Total Items" shows the number of elements found.

4. To see the elements in the model, select rows in the grid, right-click and choose Show Elements.

![Find parameter values](../../../assets\images\OneParameter\OP-FilterValue.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Prefix/Suffix

When a parameter is selected, add a prefix and a suffix to the values assigned to the parameter, just enter a value and click add.

{: .note }
The prefix and suffix are only added to the elements found with Find (Filter by parameter value). Click Find first. The result is shown in the New Value column and is written to the model when you click Apply.

![Add prefix and suffix](../../../assets\images\OneParameter\OP-PrefixSuffix.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Parameter Value

When a parameter is selected, use the Parameter Value tools.

{: .note }
The actions in the Parameter Value section only affect the elements found with Find (Filter by parameter value). Click Find first. They change the New Value column; nothing is written to the model until you click Apply.

1. Click the "Clear Values" button at the bottom to empty the New Value column of all listed elements. Confirm the message that appears. Click Apply to write the empty values to the model.

   ![Clear parameter value](../../../assets\images\OneParameter\OP-ClearValue.gif)<br />
   <sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Choose "Replace entire value" or "Replace only searched value". The second option replaces the first occurrence of the searched value inside each parameter value and is available only when the match option is Contained.

3. Enter a value and click the "Add" button to add the value in bulk to the New Value column.

![Add value](../../../assets\images\OneParameter\OP-Add.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Apply

Changes are first shown in the New Value column and are not written to the model yet. Review the column, then click the Apply button at the bottom to write the new values to the elements listed in the grid.

---

### Clear inputs

In order to perform actions on another parameter, click on the "Clear inputs" button to clear all fields and start actions on another parameter.

![Clear inputs](../../../assets\images\OneParameter\OP-ClearInput.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneParameter/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

If you want to find out more about OneParameter and explore detailed tutorials on how to use it, visit our YouTube channel. There, you'll find a series of videos that can help answer questions and improve your knowledge. Be sure to check it out and subscribe to keep up to date with our news and tips!

[DiRoots Channel](https://www.youtube.com/@DiRootsNews){: .btn .btn-di-orange }

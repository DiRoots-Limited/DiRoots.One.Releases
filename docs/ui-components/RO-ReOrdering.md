---
layout: default
title: ReOrdering
parent: ReOrdering User Guide
nav_order: 1
---

# ReOrdering
{: .no_toc }
Easily renumber instance Revit parameters by using a prefix, a suffix, and a multiplier (manually or following a path/detail line).
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# ReOrdering

The ReOrdering plugin allows the user to organize elements in the ideal order.

Follow the steps below:

1. The first step is to select whether you want to apply filters based on the Whole Model, the Active View or the Current Selection. Select the radio button to choose the view.

![ReOrdering select model view](../../assets\images\RO-WholeModel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

2. Now, use the checkboxes to select the categories to filter. Note that, once you have selected the categories, on the Family table will show the existing families to be selected.

![ReOrdering select the categories](../../assets\images\RO-SelectCategories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

3. When selecting the desired family, note that the Type table will be active for selecting element types.

![ReOrdering select the families](../../assets\images\RO-SelectFamilyType.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

```yaml
# Note:
Note that the header of the Category, Family and Type tables is an accordion component. Click on these headings to expand and collapse the view of the tables.
```

---

## Define Value

1. The first step is to select from the first list which parameter you want to apply the new order to.

2. The next step is to fill the fiels bellow.

- Prefix: this field it is not mandatory, but you can enter a value.
- Start | Step: Define the number at which the order should begin, and the steps that should advance the number sequence.
- Suffix: this field it is not mandatory, but you can enter a value.

![ReOrdering fill the information](../../assets\images\RO-DefineValue.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Rules

Create new rules or edit existing ones.
You can choose to define a prefix and suffix to apply the element numbering, but if you prefer you can create a rule to name the numbering. Select the Rules checkbox and the prefix and suffix fields will be locked. Click on the button to add a new rule, and the window will open with the parameters that can be added to the element numbering. 

![ReOrdering rules](../../assets\images\RO-Rule.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

3. To complete the order of the elements, choose the order to be followed.

- Manually: manually select elements in the model to apply the numbering value. You will be able to apply incremental and non-incremental values.

![ReOrdering manually](../../assets\images\RO-Manually.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

- Crossing: to renumber elements draw a detail line and all elements of the that fit criteria above will be numbered. If the line touches the element it will be counted.

![ReOrdering crossing](../../)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

- Vertex: to renumber elements draw a line and all elements that line endpoint (vertex) touch will be numbered. Line drawing direction/orientation will be taken into account.

![ReOrdering vertex](../../)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

- Auto: Random place unique number is chosen elements in the model. Values will be directly applied to the parameter you chose above.

![ReOrdering auto](../../assets\images\RO-Auto.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---

## Remove values

Once you have selected the category, family and type and set the values, click on the Remove all Values button to clear the assigned values.

![ReOrdering remove values](../../assets\images\RO-Remove.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---

## Preview Colors

By default, the selected elements have no colors assigned. Select the Preview Colors checkbox to assign colors to the elements.

![ReOrdering preview colors](../../assets\images\RO-PreviewColors.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Gradient Colors

In the Gradient list, select the gradient you prefer.

![ReOrdering auto](../../assets\images\RO-Gradient.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Configure

Click on the Configure button to edit or delete the current color ramps and create a new custom color ramp.

![ReOrdering auto](../../assets\images\RO-Configure.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Apply Colors

Select the Apply Colors button to add the current colors to the view model.

![ReOrdering applu colors](../../assets\images\RO-ApplyColor.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Apply to Views

You can choose the views to which you want to apply the current colors. Select the views to add in this window and click Apply.

![ReOrdering apply to views](../../assets\images\RO-ApplytoView.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---

## Update or duplicate view

You have the ability to use existing or to duplicate 3D view. Visualize only filtered elements or all elements within Section Box with ability to define offset form marked elements.

- In the first list, select a view
- Set an Offset buffer from the section bounding box
- You can replace the selected view, or can select the Duplicate Selected View checkbox.
- Rename the duplicate view.
- Select the Isolate Selected Elements checkbox, to save the view with the isolated elements.
- Click the Apply button to finish.

![ReOrdering save view](../../assets\images\RO-View.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---

## Save Selection

Click on Save Selection button, and enter the name of the selection to save it. Note that, if you go to the Manage menu in Revit and click on the Load button, the new selection you have created will appear.

![ReOrdering save selection](../../assets\images\RO-SaveSelection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---

## Isolate Selection

The Isolate Selection button, will isolate the filtered elements in a Temporary Hide/Isolate view. Click on Unisolate Selection to restore the view.

![ReOrdering isolate selection](../../assets\images\RO-Isolate.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---

### Reset

The Reset button will clear all the selected elements and the numbers assigned.

![ReOrdering reset](../../assets\images\RO-Reset.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Reset Overrides

The Reset Overrides tool allows you to clear the colors applied to the views. You can choose to clear the current view or several views.
When you select the multiple views option, a window will open for you to choose the views you want to clear, and then just click Reset Overrides. The views will then be restored to their original view.

![ReOrdering reset overrides](../../assets\images\RO-ResetOverrides.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

### Create Legend

When you click on Create Legend, a window will open for you to enter a name for the legend, and whether you want to itemize instances. If you choose this option, you'll have to select which columns you want to itemize.
Once you've clicked Create, you can see the new legend you've created in the list of legends in the revit.

![ReOrdering create legend](../../assets\images\RO-Legend.gif)  
<sub>Note: the version on the image may not reflect the [latest version of ReOrdering](https://diroots.com/revit-plugins/renumber-revit-elements-using-a-prefix-a-suffix-and-a-multiplier-with-reordering/).</sub>

---
layout: default
title: Visualize
parent: OneFilter User Guide
nav_order: 5
---

# OneFilter
{: .no_toc }
Quickly find your families in Revit models. Search by category, parameter name and value. Find elements within Areas, Masses, Rooms, Spaces, and Zones.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Visualize

In this tab, you can filter by existing categories and apply colors to them. Let's get started:

1. The first step is to select whether you want to apply filters based on the Whole Model, the Active View or the Current Selection. Select the radio button to choose the view.

![OneFilter selecting model view](../../assets\images\OF-Vs-WholeModel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

2. Now, use the checkboxes to select the categories to filter.

![OneFilter choose categories](../../assets\images\OF-Vs-SelectCategories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

3. Select the parameter you want to filter in the Select Parameter table.

![OneFilter select a parameter](../../assets\images\OF-Vs-SelectParameter.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Apply Colors

Select the Apply Colors button to add the current colors to the view model.

![OneFilter select a parameter](../../assets\images\OF-Vs-ApplyColor.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Apply to Views

You can choose the views to which you want to apply the current colors. Select the views to add in this window and click Apply.

![OneFilter select a parameter](../../assets\images\OF-Vs-ApplytoView.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

---

## Set colors

By default, elements are assigned the preview colors.

### Randomize

Click the Randomize button to update the colors assigned to the elements at random.

![OneFilter randomize colors](../../assets\images\OF-Vs-Randomize.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Preferences

Click on the Preferences button to edit or delete the current color ramps and create a new custom color ramp.

![OneFilter preferences](../../assets\images\OF-Vs-Preferences.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Gradient Colors

1. Select the Gradient Colors checkbox to assign it to elements.

2. In the Gradient list, select the gradient you prefer.

![OneFilter gradient](../../assets\images\OF-Vs-GradientColor.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

---

## Export

### Export to Excel

Click on the Export list and select the Export to Excel option. Note that the assigned colors will be exported in the Excel file.

![OneFilter export to Excel](../../assets\images\OF-Vs-ExportExcel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Export to Google Drive

Click on the Export list and select the Export to Google Drive option. Note that the assigned colors will be exported in the Google Drive.

![OneFilter export to Google Drive](../../assets\images\OF-Vs-ExportDrive.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Export IDs to CSV

Click on the Export list and select the Export IDs to CSV option.

![OneFilter export IDs to CSV](../../assets\images\OF-Vs-ExportID.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

---

## Update or duplicate view

Mark with checkbox elements that you want isolate with the Section Box. You have the ability to use existing or to duplicate 3D view. Visualize only filtered elements or all elements withi Section Box with ability to define offset form marked elements.

- In the first list, select a view
- Set an Offset buffer from the section bounding box
- You can replace the selected view, or can select the Duplicate Selected View checkbox.
- Rename the duplicate view.
- Select the Isolate Selected Elements checkbox, to save the view with the isolated elements.
- Click the Apply button to finish.

![OneFilter views](../../assets\images\OF-Vs-View.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

---

## Save Selection

Click on Save Selection button, and enter the name of the selection to save it. Note that, if you go to the Manage menu in Revit and click on the Load button, the new selection you have created will appear.

![OneFilter save selection](../../assets\images\OF-Vs-SaveSelection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

---

## Isolate Selection

The Isolate Selection button, will isolate the filtered elements in a Temporary Hide/Isolate view. Click on Unisolate Selection to restore the view.

![OneFilter isolate selection](../../assets\images\OF-Vs-IsolateElements.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Reset

The Reset button will clear all the filters applied on Filter tab.

![OneFilter reset filter](../../assets\images\OF-Vs-Reset.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Reset Overrides

The Reset Overrides tool allows you to clear the colors applied to the views. You can choose to clear the current view or several views.
When you select the multiple views option, a window will open for you to choose the views you want to clear, and then just click Reset Overrides. The views will then be restored to their original view.

![OneFilter reset overrides](../../assets\images\OF-Vs-ResetOverrides.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Create Legend

When you click on Create Legend, a window will open for you to enter a name for the legend, and whether you want to itemize instances. If you choose this option, you'll have to select which columns you want to itemize.
Once you've clicked Create, you can see the new legend you've created in the list of legends in the revit.

![OneFilter create legend](../../assets\images\OF-Vs-Legend.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>

### Select

Click on Select button to select the elements in the current view.

![OneFilter visualize](../../assets\images\OF-Vs-Select.gif)  
<sub>Note: the version on the image may not reflect the [latest version of OneFilter](https://diroots.com/revit-plugins/revit-advanced-filter-onefilter/).</sub>
---
layout: default
title: Template Transfer
parent: ViewManager
nav_order: 4
nav_sections:
  - title: "Select Origin Template"
    anchor: select-origin-template
  - title: "Select Origin Properties"
    anchor: select-origin-properties
  - title: "Select Destination Templates"
    anchor: select-destination-templates
---

# ViewManager
{: .no_toc }
Manage all the Views in your project, as well as View Templates and View Range settings in a single window.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Template Transfer tab

{: .note }
The Template Transfer tab is available for premium users only.

The Template Transfer allows you to copy the View Template properties from several View Templates.

## Select Origin Template

Select an Origin View Template to copy its properties.

1. In the first table, use the first drop-down list to filter the view templates by Disciplines.

2. The second drop-down list allows you to filter view templates by View Types.

3. Use the search box to search for view template names.

![Selecting Origin View Template](../../../assets\images\ViewManager\VM-Tt-Origin.gif)

<sub>Note: the version on the image may not reflect the [latest version of ViewManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Edit View Template

Right-click on the Origin View Template and select Edit View Template to open the Revit window and manage it.

![Edit View Template](../../../assets\images\ViewManager\VM-Tt-Edit.gif)

<sub>Note: the version on the image may not reflect the [latest version of ViewManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Select Origin Properties

In this table, you can choose one or more properties from the Origin View Template to copy to another.

1. Use the search box to search for view template properties.

2. Use the checkboxes to select the properties.

3. For the V/G Overrides properties (the Model, Annotation, Analytical Model and Import categories, the Filters and the Revit Links), a count of the items to transfer (for example 12/40) and a "..." button appear on the row once you check it. By default all items are transferred. Click the "..." button to choose which items to transfer: use the search box to find items, and select the items you want. The Model, Annotation and Analytical Model lists also have a discipline filter. Click Apply to keep the choice. Items you do not select keep the settings they have in the destination view templates.

4. For the Filters, the picker also has an Override behavior choice, which sets what happens to the filters that already exist in the destination view templates:

   - Add only new - do not change existing filters
   - Add and overwrite existing filters (the default)
   - Replace all filters - destination filters are removed

{: .warning }
Replace all filters removes the filters of the destination view templates that are not in the origin selection.

{: .note }
Check the option Hide unchecked properties to see only the selected properties.

The View Scale is also transferred when you select it.

![Selecting Origin Properties](../../../assets\images\ViewManager\VM-Tt-Properties.gif)

<sub>Note: the version on the image may not reflect the [latest version of ViewManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Select Destination Templates

Choose one or more Destination View Templates to transfer the selected properties.

1. In this table, use the first drop-down list to filter view templates by Disciplines.

2. The second drop-down list allows you to filter view templates by View Types.

3. Use the search box to search for view template names.

4. Click the Apply button to transfer the selected properties to the destination view templates.

{: .note }
Check the Hide unchecked templates option to see only the chosen destination view templates.

![Selecting Destination View Templates](../../../assets\images\ViewManager\VM-Tt-Destination.gif)

<sub>Note: the version on the image may not reflect the [latest version of ViewManager/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

Let's go to the next tab to manage the View Ranges.
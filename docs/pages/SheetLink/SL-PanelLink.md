---
layout: default
title: PanelLink
parent: SheetLink User Guide
nav_order: 7
---

# SheetLink
{: .no_toc }
Export your Revit model data (by categories, elements, schedules) to Excel and Google Sheets. Edit the data and import it back to update the model.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# PanelLink

PanelLink is a tool to export the properties of electrical distribution panels to Exce.

## Select Panel Schedules

In the first table, select the panels to export the properties.
Use the search box to search for the panels.

![PanelLink select panel](../../../assets\images\SheetLink\SL-Pl-SelectPanel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Properties table

Note that when you select a panel, its properties will be shown, separated into two tables, the Electrical Equipment table and the Electrical Circuit table.
If you prefer, you can select from the first list of tables whether you want to filter instance, type or read-only properties.

```yaml
# Note:
Properties are identified by colors that represent the instance, type and read-only properties.
```

![PanelLink properties table](../../../assets\images\SheetLink\SL-Pl-Properties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Reset

Clear all selections made.

![PanelLink reset](../../../assets\images\SheetLink\SL-Pl-Reset.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Export

Click on the Export button and choose whether you want to export to Excel or Google Drive.

```yaml
# Note:
Note that, you can keep formatting of the schedules, but you wont be able to import the data back to Revit.
```

![PanelLink export](../../../assets\images\SheetLink\SL-Pl-Export.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Import

Select the Import button and choose to import from Exel file or Google Drive, then update the current model.

![PanelLink import](../../../assets\images\SheetLink\SL-Pl-Import.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>
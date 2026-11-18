---
layout: default
title: PanelLink
parent: SheetLink
nav_order: 7
nav_sections:
  - title: "Select Panel Schedules"
    anchor: select-panel-schedules
  - title: "Reset"
    anchor: reset
  - title: "Export"
    anchor: export
  - title: "Import"
    anchor: import
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

PanelLink is a tool to export the properties of electrical distribution panels to Excel.

## Select Panel Schedules

In the first table, select the panels to export the properties.
Use the search box to search for the panels. Select Hide un-checked elements below the table to show only the checked panels. Right-click a panel and choose Open View to open it.

![PanelLink select panel](../../../assets\images\SheetLink\SL-Pl-SelectPanel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Properties table

Note that when you select a panel, its properties will be shown, separated into two tables, the Electrical Equipment table and the Electrical Circuit table.
If you prefer, you can select from the first list of tables whether you want to filter instance, type or read-only properties.

{: .note }
Properties are identified by colors that represent the instance, type and read-only properties.

![PanelLink properties table](../../../assets\images\SheetLink\SL-Pl-Properties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Reset

Clear all selections made.

![PanelLink reset](../../../assets\images\SheetLink\SL-Pl-Reset.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Export

Click on the Export button and choose whether you want to export to Excel or Google Drive.

{: .note }
Note that, you can keep formatting of the schedules, but you wont be able to import the data back to Revit. In the Export Options dialog, Keep Formatting of the Schedules is selected by default and Open Excel File After Export opens the Excel file when the export is finished. If you keep the formatting and have selected more than one panel, the Excel button becomes Export to Folder and one file is created for each panel.

![PanelLink export](../../../assets\images\SheetLink\SL-Pl-Export.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Import

Select the Import button and choose to import from Excel file or Google Drive, then update the current model.

{: .note }
Import from Google Drive is available for premium users only.

![PanelLink import](../../../assets\images\SheetLink\SL-Pl-Import.gif)  
<sub>Note: the version on the image may not reflect the [latest version of SheetLink/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

If you want to find out more about PanelLink and explore detailed tutorials on how to use it, visit our YouTube channel. There, you'll find a series of videos that can help answer questions and improve your knowledge. Be sure to check it out and subscribe to keep up to date with our news and tips!

[DiRoots Channel](https://www.youtube.com/@DiRootsNews){: .btn .btn-di-orange }
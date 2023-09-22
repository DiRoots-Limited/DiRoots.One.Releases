---
layout: default
title: Import Table
parent: TableGen User Guide
nav_order: 1
---

# TableGen
{: .no_toc }
Import your spreadsheets into Revit as Legend Views, Schedule Views and Drafting Views.
Collaborate with non-Revit users and bring the beauty of your Excel Tables into Revit.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# TableGen

## Import a table

Follow the firsts steps:

1. Choose a spreadsheet that you would like to import into Revit and make a selection of the information you want to bring it.
After to select the data, save the Excel file to import it.

![TableGen selecting data to import](../../assets\images\TableGen\TG-PrepareSheet.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

2. Select the TableGen in the DiRootsOne menu, and click on the Add Tables button. The next step is to select the Excel file.

![TableGen add tables](../../assets\images\TableGen\TG-AddTable.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

2. The fields will be completed by default, but you can change it to complete the process. 

- Number of copies: the TableGen you import the number of copies filled in this field.
- Excel File: select the Excel file to be imported.
- WorkSheet: choose the current WorkSheet to select the data.
- WorkSheet Region: choose the selection created in the Excel file.
- View Type: choose if you want to import like a Legend View, Schedule View or Drafting View.

![TableGen complete fields](../../assets\images\TableGen\TG-CompleteFields.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

3. Confirm the import on the OK button, wait a few seconds for the import.

![TableGen file imported](../../assets\images\TableGen\TG-FileImported.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

You can edit some file information before the "Apply" action, to create the views.

```yaml
# Editable fields:  
View Name: it is a text field and you can change the actual name.
WorkSheet: change the WorkSheet selected on this drop-down field.
Region: drop-down to change the selection made in the excel file.
View Type: change the view type to be create.
```

![TableGen edit file](../../assets\images\TableGen\TG-EditFile.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

4. Click on the Apply button to complete the process, and look of the new views created.

![TableGen create views](../../assets\images\TableGen\TG-ApplyTable.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

All right, now that you've imported your table into the model in Revit, you can work with the imported data, and even add these views to the existing sheets in the model.

![TableGen add table to sheets](../../assets\images\TableGen\TG-AddToSheet.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

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

1. Choose a spreadsheet you want to import into Revit and make a selection of the range of cells you want to bring to Revit, and then name the previously selected range of cells and hit Enter.
After selecting the data, save the Excel file to import it.

![TableGen selecting data to import](../../../assets\images\TableGen\TG-PrepareSheet.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can also to create multiple worksheet regions and each one can be individually imported to Revit.

![TableGen selecting data to import](../../../assets\images\TableGen\TG-Selection.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen](https://diroots.com/revit-plugins/excel-to-revit-as-drafting-legend-and-schedule-views-with-tablegen/).</sub>

2. Select the TableGen from the DiRootsOne menu, and click on the Add Tables button. The next step is to select the Excel file.

![TableGen add tables](../../../assets\images\TableGen\TG-AddTable.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. The fields will be filled in by default, but you can change them to complete the process. 

- Number of copies: the TableGen will import the number of copies filled in this field.
- Excel File: select the Excel file to be imported.
- WorkSheet: choose the current WorkSheet.
- WorkSheet Region: choose the selection created in the Excel file.
- View Type: choose if you want to import like a Legend View, Schedule View or Drafting View.

![TableGen complete fields](../../../assets\images\TableGen\TG-CompleteFields.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

3. Confirm the import on the OK button, and wait a few seconds for the import to complete.

![TableGen file imported](../../../assets\images\TableGen\TG-FileImported.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

You can edit some information in the file before the "Apply" action, to create the views.

```yaml
# Editable fields:  
View Name: it is a text field and you can change the current name.
WorkSheet: change the selected WorkSheet in this drop-down field.
Region: drop-down field to change the selection made in the Excel file.
View Type: change the type of view to be created.
```

![TableGen edit file](../../../assets\images\TableGen\TG-EditFile.png)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

4. Click the Apply button to complete the process and see the new views created.

![TableGen create views](../../../assets\images\TableGen\TG-ApplyTable.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

All right, now that you've imported your table into the model in Revit, you can work with the imported data, and even add these views to the existing sheets in the model.

![TableGen add table to sheets](../../../assets\images\TableGen\TG-AddToSheet.gif)  
<sub>Note: the version on the image may not reflect the [latest version of TableGen/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

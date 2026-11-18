---
layout: default
title: Export
parent: FamilyReviser
nav_order: 1
nav_sections:
  - title: "Preferences"
    anchor: preferences
  - title: "Families in linked models"
    anchor: families-in-linked-models
  - title: "Export families"
    anchor: export-families
---

<span id="familyreviser"></span>

# FamilyReviser
{: .no_toc }
Manage your Revit families (rename, add prefix and suffix, save them in an organised way) and worksets (modify worksets by category or create your own rules).
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Export

Select FamilyReviser from the DiRootsOne menu and open the Export tab. Families can be saved in a repository folder to be used in other projects and make your work easier than ever.

1. To start, select the radio button to choose whether you want to manage All families or only selected Families. Now, choose in the first list to see the families categories, By Category or By Family Name and Type Name.

   ![FamilyReviser select categories](../../../assets\images\FamilyReviser\FR-Ex-Families.gif)

   <sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Select the categories and get the families. Note that there is a tree representing category > family > type, and you can select the level you want.

   ![FamilyReviser choose categories](../../../assets\images\FamilyReviser\FR-Ex-SelectCategory.gif)

   <sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

   {: .note }
   Select the checkbox below the first table to Hide un-checked categories.

3. The second table shows the families of the selected categories, separated by the columns Family name, Repository name and Location.

{: .note }
Make sure the recording location is correct to export the families.

## Preferences
Open the Preferences pop-up window to manage some details for exporting families.

![FamilyReviser open the preferences window](../../../assets\images\FamilyReviser\FR-Ex-OpenPreferences.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Add Repository

Click this button to select or create a new repository folder.

![FamilyReviser add repository](../../../assets\images\FamilyReviser\FR-Ex-AddRepository.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


### Remove Repository

Select one or more repositories and click the Remove repository button. Then confirm that you want to remove it.

![FamilyReviser remove repository](../../../assets\images\FamilyReviser\FR-Ex-RemoveRepository.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Delete Backup Families

Select the Delete Backup Families checkbox to delete Revit's numbered backup files (for example, Door.0001.rfa) in the export folder and its zBackup folder when you export. If the checkbox is cleared, the numbered backup files are moved to the zBackup folder instead.

![FamilyReviser delete backup families](../../../assets\images\FamilyReviser\FR-Ex-DeleteBackup.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Maximum backups

Set the maximum number of backup versions kept for each family in the zBackup folder. Enter a number from 1 to 999 (default 10).

![FamilyReviser maximum backups](../../../assets\images\FamilyReviser\FR-Ex-MaxBackups.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Group export by category

This option allows you to organize families by groups. Thus, if you select this option, a folder will be created for each category of families.

![FamilyReviser group export by categories](../../../assets\images\FamilyReviser\FR-Ex-GroupExport.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Subfolder depth

Set how many levels of subfolders below each repository the Import tab reads. Enter a number from 0 to 5 (default 1).

![FamilyReviser subfolder depth](../../../assets\images\FamilyReviser\FR-Ex-Subfolder.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Families in linked models

{: .note }
The Families in linked models option is available for premium users only.

Select the Families in linked models checkbox, next to the Preferences button, to also export the families of the loaded Revit links. Links that are not loaded, links nested inside another link and in-place families are not listed. Your choice is remembered.

1. Use the list above the categories to choose the source models: All models, Current Model or one or more of the linked models.

2. The second table gets a Linked file name column that shows the model each family comes from.

3. By default, the families of each linked model are exported to a subfolder named after the linked model. If you choose another repository or folder for a row, the families are still saved in a subfolder named after the linked model.

4. A Location shown in red is too long: the full path of the family file is longer than the 259 characters Windows allows, so the file cannot be saved. Choose a shorter location for that row.

If two families would be saved to the same file, a message lists them and asks whether to continue. Only the last of them is kept.

If some families are skipped or cannot be written, a message lists them when the export finishes.

## Export families

Once you have chosen the categories, configured the repositories and locations and defined whether you want to export backups and by grouping, click on Export.

![FamilyReviser export families](../../../assets\images\FamilyReviser\FR-Ex-SelectRepository.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

{: .note }
In Revit 2027, a warning that the feature might crash Revit is shown first. Click Yes to continue.

The families will be exported to the selected location.

![FamilyReviser set the repository](../../../assets\images\FamilyReviser\FR-Ex-Export.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

Let's go to the next tab to Import Families.

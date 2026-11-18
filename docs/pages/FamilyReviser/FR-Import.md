---
layout: default
title: Import
parent: FamilyReviser
nav_order: 2
nav_sections:
  - title: "Import families"
    anchor: import-families
---

# FamilyReviser
{: .no_toc }
Manage your Revit families (rename, add prefix and suffix, save them in an organised way) and worksets (modify worksets by category or create your own rules).
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Import

Import families from your repositories.

1. Open FamilyReviser Import tab and choose a repository and then, open the tree and select the category of the family to import.

   {: .note }
   Note that when you select a family category, it is shown in the second table, with the columns File Name, Version, Repository Name and Location. You can select specific families to import them into the project.

   {: .note }
   Use the Include Repository checkbox to select all repositories, and select the checkbox below the list to Hide un-checked repositories.

   ![FamilyReviser select repository](../../../assets\images\FamilyReviser\FR-Im-SelectRepository.gif)

   <sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

   {: .note }
   To view the family folder, right-click and select Open folder.

   ![FamilyReviser open family folder](../../../assets\images\FamilyReviser\FR-Im-OpenFolder.png)

   <sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

2. Preferences

Open the Preferences pop-up to manage some details for importing families. The Export tab uses the same preferences.

![FamilyReviser open the preferences](../../../assets\images\FamilyReviser\FR-Im-Preferences.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Add Repository

Click this button to select or create a new repository folder.

![FamilyReviser add repository](../../../assets\images\FamilyReviser\FR-Im-AddRepository.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Remove Repository

Select one or more repositories and click the Remove Repository button. Then, confirm that you want to remove it.

![FamilyReviser remove repository](../../../assets\images\FamilyReviser\FR-Im-RemoveRepository.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Delete Backup Families

Select the Delete Backup Families checkbox to delete Revit's numbered backup files (for example, Door.0001.rfa) in the export folder and its zBackup folder when you export. If the checkbox is cleared, the numbered backup files are moved to the zBackup folder instead.

![FamilyReviser delete backup families](../../../assets\images\FamilyReviser\FR-Im-DeleteBackup.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Maximum backups

Set the maximum number of backup versions kept for each family in the zBackup folder when you export. Enter a number from 1 to 999 (default 10).

![FamilyReviser maximum backups](../../../assets\images\FamilyReviser\FR-Im-MaxBackup.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Group export by category

If you select this option, a folder is created for each category of families when you export.

![FamilyReviser group export by categories](../../../assets\images\FamilyReviser\FR-Im-GroupExport.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Subfolder depth

Set how many levels of subfolders below each repository are read in the Include Repository list. Enter a number from 0 to 5 (default 1).

![FamilyReviser subfolder depth](../../../assets\images\FamilyReviser\FR-Im-Subfolder.png)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>


## Import families

After choosing the repository and the family category, and configuring the preferences, click Import.
The families will be imported into the project.

![FamilyReviser import families](../../../assets\images\FamilyReviser\FR-Im-ImportFamily.gif)

<sub>Note: the version on the image may not reflect the [latest version of FamilyReviser/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

Let's go to the next tab to manage and edit Families.

---
layout: default
title: PointKit
parent: PointKit User Guide
nav_order: 1
---

# PointKit
{: .no_toc }
A free Autodesk Revit Add-in to boost your productivity when working with Point Clouds.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Point Cloud

Point Cloud from PointKit is a package of tools to make working with point clouds easier.

## Select Points

Click on Select Points button and choose to Select Points or Select Between Levels.

### Select Points

Click and drag the mouse to select certain points and isolate them.

![PointKit select points](../../../assets\images\PointKit\PK-SelectPoints.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Select Between Levels

Click on the Select Between Levels button and choose the start of the level and the end of the level to isolate the point cloud within this range.

![PointKit select Between Levels](../../../assets\images\PointKit\PK-SelectLevel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Undo and Redo button

When performing actions in Point Cloud, such as isolating certain spaces, click the Undo button to revert to the recent action, and the Redo button to reapply the recent action.

![PointKit undo and redo button](../../../assets\images\PointKit\PK-UndoRedo.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Reset

Click the Reset button to clear all actions and selections made in the point cloud.

![PointKit reset](../../../assets\images\PointKit\PK-Reset.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Show/Hide

Hide or reactivate the visualization of all points clouds in the current view.

![PointKit show/hide](../../../assets\images\PointKit\PK-ShowHide.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Import DXF File

Import a file in DXF format for your current modeling. Clicking on this button will open a window to open the browser and select the file to be imported.

- Select the DXF file on your browse to import.
- Choose a Family Template.
- Select the radio button to choose the orientation of the file to be imported. You can choose to import Center to Center or On Origin to Internal Origin.

![PointKit import dxf](../../../assets\images\PointKit\PK-ImportDXF.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Import ASCII point cloud file

Click and select the ASCII file to be imported from your computer.

![PointKit import ASCII](../../../assets\images\PointKit\PK-ImportASCII.png)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Export

Click to export the current point cloud. 

- Use the checkbox to choose Export Points and Export Mesh.
- In the first list, select the density level to be exported.
- Select the checkbox if you want to Open Family After Export. And then, open the browse to select the file.

```yaml
# Note:
Applied only for .DXF files.
```

- Select Family template
- Select the radio button to choose the orientation of the file to be imported. You can choose to import Center to Center or On Origin to Internal Origin.

![PointKit export](../../../assets\images\PointKit\PK-Export.png)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

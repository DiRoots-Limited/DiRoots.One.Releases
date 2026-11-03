---
layout: default
title: PointKit
parent: PointKit
nav_exclude: true
nav_order: 1
nav_sections:
  - title: "Select Points"
    anchor: select-points
  - title: "Import DXF File"
    anchor: import-dxf-file
  - title: "Import ASCII point cloud file"
    anchor: import-ascii-point-cloud-file
  - title: "Export"
    anchor: export
---

<span id="pointkit"></span>

# PointKit
{: .no_toc }
Autodesk Revit Add-in to boost your productivity when working with Point Clouds.
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Select Points

Click the arrow next to **Select Points** to choose **Select Points** or **Select Between Levels**.

### Select Points

Draw a box around the points you need, and PointKit isolates them.

Steps:

1. Open a plan view that shows the point cloud.
2. Click **Select Points**.
3. Click and drag a box around the points you want to keep.

![PointKit select points](../../../assets\images\PointKit\PK-SelectPoints.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Select Between Levels

Keep only the points between two levels.

Steps:

1. Open a view that shows the point cloud, for example a section. A 3D view must be orthographic, not perspective.
2. Click the arrow next to **Select Points** and choose **Select Between Levels**.
3. Under **Select start and end levels**, choose the start level and the end level. Use **Offsets** to move either limit up or down.
4. Click **Isolate**.

![PointKit select between levels](../../../assets\images\PointKit\PK-SelectLevel.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Undo, Redo and Reset

Step through your selections with the small buttons next to **Select Points**.

- **Undo** reverts the last selection.
- **Redo** reapplies the selection you just undid.
- **Reset** clears all selections, so no points are isolated.

![PointKit undo, redo and reset](../../../assets\images\PointKit\PK-UndoRedo.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Show/Hide

Click **Show/Hide** to hide all point clouds in the current view. If any of them is already hidden, it shows the hidden ones instead.

![PointKit show/hide](../../../assets\images\PointKit\PK-ShowHide.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Import DXF File

Import a DXF file into a new family. PointKit creates the family from the template you choose, opens it and imports the file.

Steps:

1. Click **Import DXF File**.
2. Click **Browse** and select your family templates folder. Then choose a template under **Select Family Template**.
3. Choose how to place the file: **Import Center to Center** or **Import Origin to Internal Origin**.
4. Click **Import** and select the .dxf file.

![PointKit import dxf](../../../assets\images\PointKit\PK-ImportDXF.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Import ASCII point cloud file

Import a point cloud saved as an ASCII text file (.pts or .xyz).

Steps:

1. Click the arrow next to **Import DXF File** and choose **Import ASCII point cloud file**.
2. Select the .pts or .xyz file on your computer.

The file's origin is placed at Revit's internal origin.

![PointKit import ASCII point cloud file](../../../assets\images\PointKit\PK-ImportASCII.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---

## Export

Export the isolated points, or the whole point cloud when nothing is isolated.

Steps:

1. Click **Export**.
2. Choose **Export Points**, **Export Mesh** or both.
3. Choose the density: **Low Density**, **Medium Density** or **High Density**.
4. **Open Family After Export (Only For DXF Files)** is selected by default. It creates a family from the exported .dxf file and opens it: browse to your family templates folder, then choose a family template and the orientation (**Import Center to Center** or **Import Origin to Internal Origin**). Clear the checkbox if you only need the file.
5. Click **Export** and choose where to save the file.

{: .note }
Points alone can be saved as .pts, .xyz or .dxf. When **Export Mesh** is selected, the file is saved as .dxf.

![PointKit export](../../../assets\images\PointKit\PK-Export.gif)  
<sub>Note: the version on the image may not reflect the [latest version of PointKit/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

---
 
If you want to find out more about PointKit and explore detailed tutorials on how to use it, visit our YouTube channel. There, you'll find a series of videos that can help answer questions and improve your knowledge. Be sure to check it out and subscribe to keep up to date with our news and tips!
 
[DiRoots Channel](https://www.youtube.com/@DiRootsNews){: .btn .btn-di-orange }

<sub>Point cloud in the animations: "LiDAR point-cloud: George IV Bridge, National Library of Scotland", University of Edinburgh and National Library of Scotland, [doi.org/10.34812/6ch4-rp49](https://doi.org/10.34812/6ch4-rp49), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Changed: thinned, rotated, recentred, cropped, recoloured, heights shifted and converted for PointKit.</sub>

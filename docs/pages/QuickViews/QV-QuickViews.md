---
layout: default
title: Quick Views
parent: User Guide
nav_order: 1
---

![DiStem Quick Views - Create internal views by Callouts, Elevations and Sections](../../../assets\images\QuickViews\QuickView_LightMode_Icon150px.png)  


# Quick Views
{: .no_toc }
The Quick Views allows you to create multiple views of Callouts, Elevantions and Sections of internal rooms and spaces.

## Core Features
{: .no_toc }
- Create Callouts from rooms and spaces.
- Create Elevations and Sections from rooms and spaces.
- Update views in batch.
- Assign Shared Parameters to views.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Whole Model or Active View

Select the radio button to manage rooms and spaces from the Whole Model or the Active View.
Note that the table will show all the rooms and spaces for the currently selected option. In this table you can see the level, number, name, rooms and spaces, and the Status column shows whether any views have been created.

![DiStem Quick Views - Whole Model or Active View](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Filter Types

In the Type column header, select Rooms and Spaces.

![DiStem Quick Views - choose rooms/spaces](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Linked Files

Select the Linked Files checkbox to also manage linked model rooms/spaces.

![DiStem Quick Views - linked files](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

### Status list

Use the Status list to filter the views created or not.

![DiStem Quick Views - Filter by status](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Callout View

Let's create some Callouts Views. To do this, click on the Callout Settings button.

### View tab

In this tab, you can manage all the details for creating Callout views.

1. Choose the Callout Type

2. Select a scale to apply to the views.

3. Set a level of detail to create the views.

4. Select the Phase of the view.

5. If you want, select a View Template to create it. Note that if a View Template is selected, its settings will override the settings assigned in this window.

6. Set a value for Offset from Callout boudary.

7. Choose whether you want the Callout boudary to be a rectangle or aligned with room/space boundary.

```yaml
#Note:
Use the Info icon to see the example of the boudaries.
```

![DiStem Quick Views - View tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Naming Configuration tab

Let's customize the names of the views.

In the first table, you can see all the existing parameters that you can use to name the views. Select the parameters you want, and click on the arrow button to assign them to the Selected Parameters table. You can also sort the Selected Parameters using the arrows below the table.

```yaml
#Note:
Use the checkbox to also see the Project Information parameters.
```

```yaml
#Note:
Select the checkbox to add a default Field Separator between the selected parameters.
```

![DiStem Quick Views - select parameters to naming](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Enter Custom Fields to name the views.

2. Enter Custom Separators betwen the parameters to be named.

![DiStem Quick Views - custom field and custom separator](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Parameters tab

To manage this tab you need to create at least one Shared Parameter from the Views category. Then, click on Add button to add a Shared Parameter to the views you are going to create.
Once you have added it, open the list to select the parameter and in the second column, assign it a value.

![DiStem Quick Views - Parameters tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Save settigs

Click on Apply to save the settings and then select the rooms and spaces for which you want to create the callout views.
To finish, click on the Create button and wait a few seconds for the views to be created.

```yaml
#Note:
You can also use the Select rooms/spaces buttons to choose them manually.
```

![DiStem Quick Views - create views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Elevation and Section views

Let's create some Elevation and Section views. To do this, select from the list whether you want to create elevation or section views and click on the Settings button.

### View tab

In this tab, you can manage all the details for creating the views.

1. Choose the Elevation/Section Type.

2. Select a scale to apply to the views.

3. Define the level of detail to create the views.

4. Choose the Phase from view.

5. If you want, select a View Template to create it. Note that if a View Template is selected, its settings will override the settings assigned in this window.

6. Select the checkbox to Join Elevation Views into Single Marker. If the room is square or retangle, this option places all the views on a single marker.

![DiStem Quick Views - View tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

Now let's define the section height and offsets to the rooms and spaces.

1. Section Height- open the list and choose if you want to apply the value From Instance or Absoulte, and then define de value to apply it.

2. Define the Offset Bottom value.

3. Enter an Offset Left value.

4. Enter an Offset Right value.

5. Define the distance before boundary.

6. Define the distance after boundary.

7. To conclude, define a Boundary break tolerance. For example, if there are small walls in the room, you can assign a tolerance value to create the views. Whether you want to create a view for each small wall, or a general view, without taking these smaller values into account.

```yaml
#Note:
Use the Info icon to see the boudaries and Offsets examples.
```

![DiStem Quick Views - View tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Naming Configuration tab

Let's customize the names of the views.

In the first table, you can see all the existing parameters that you can use to name the views. Select the parameters you want, and click on the arrow button to assign them to the Selected Parameters table. You can also sort the Selected Parameters using the arrows below the table.

```yaml
#Note:
Use the checkbox to also see the Project Information parameters.
```

```yaml
#Note:
Select the checkbox to add a default Field Separator between the selected parameters.
```

![DiStem Quick Views - select parameters to naming](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

1. Enter Custom Fields to name the views.

2. Enter Custom Separators between the parameters to name.

![DiStem Quick Views - custom field and custom separator](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

Let's create a condition to count the views.

1. Define the follow order by Clockwise or Anticlockwise.

2. Choose the direction to start.

3. Definde the style by number or alphabet.

4. Enter the value to start.

```yaml
#Caution:
To use the View Count condition, you must to select the View Count Parameter, in the previous table.
```

![DiStem Quick Views - custom field and custom separator](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Parameters tab

To manage this tab you need to create at least one Shared Parameter from the Views category. Then, click on Add button to add a Shared Parameter to the views you are going to create.
Once you have added it, open the list to select the parameter and in the second column assign it a text value.

![DiStem Quick Views - Parameters tab](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

### Save settigs

Click Apply to save the settings and select the rooms and spaces for which you want to create Elevations/Sections views.
To finish, click on the Create button and wait a few seconds for the views to be created.

```yaml
#Note:
You can also use the Select rooms button to choose them manually.
```

![DiStem Quick Views - create views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

---

## Right-click actions

Right-click on the room/space within the table and you can:

- Delete Callout and Elevations/Sections.

- Open Callout and Elevations/Sections.

---

## Update Views

Update the views of the selected rooms/spaces. All the views of the selected rooms will be deleted and new views will be created.

```yaml
#Note:
Details and dimensions will be lost.
```

![DiStem Quick Views - create views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>

All done! Verify your created views.

![DiStem Quick Views - created views](../../)  
<sub>Note: the version on the image may not reflect the latest version of the application.</sub>
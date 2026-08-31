---
layout: default
title: Hide in Views
parent: Hide in Views User Guide
nav_order: 1
---

# Hide in Views
{: .no_toc }
Hide or unhide selected Revit elements, or their categories, across multiple views in a single operation.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Hide in Views

Hide in Views allows you to quickly hide or unhide selected elements or their categories across multiple Revit views without updating each view individually.

You can work with either the selected Revit elements or the categories belonging to those elements, and then choose the views where the Hide or Unhide action should be applied.

**GIF reference: Hide in Views workflow**

To be added later

<sub>**Note:** the version shown in the GIF may not reflect the [latest version of Hide in Views/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Select Elements

Steps:

1. Select one or more elements in your Revit project.
2. Open Hide in Views from the "Utilities" panel on the "DiRootsOne" tab.

```yaml
# Note:
If no elements are selected, Hide in Views prompts you to select elements before the tool opens.
```

**Image reference: Selecting elements and opening Hide in Views**

To be added later

## Choose the Hide/Unhide Mode

Choose whether to control the visibility of the selected elements or their categories.

- **Elements** - Hides or unhides only the elements currently selected in Revit.
- **Category** - Hides or unhides the unique categories of the selected elements through Revit Visibility/Graphics.

The status area at the bottom of the window changes according to the selected mode:

- **Elements** - Selected Views: XX of XX | Selected Elements: XX
- **Category** - Selected Views: XX of XX | Categories Collected: XX

Hover over a mode to display its tooltip:

- **Elements tooltip:** Hide or unhide the selected Revit elements in the selected views.
- **Category tooltip:** Hide or unhide the categories of the selected elements through Visibility/Graphics in the selected views.

```yaml
# Note:
Category mode uses Revit Visibility/Graphics category visibility. It does not hide the individual elements.
```

**Categories Collected** represents the number of unique categories identified from the currently selected elements.

**Image reference: Elements and Category options**

To be added later

## Select Target Views

Select one or more views where you want to apply the Hide or Unhide action.

Hide in Views supports the following view types:

- Area Plans
- Ceiling Plans
- Elevations
- Floor Plans
- Sections
- 3D Views

Use the available controls to find and select target views:

- **Search** - Searches views by name.
- **View Type** - Filters the list by supported view type.
- **Checkboxes** - Select individual views.
- **Header checkbox** - Selects or deselects the currently displayed views.
- **Column headers** - Sorts the available views.

The bottom of the window displays the selected-view count:

**Selected Views: XX of XX**

### Active View

The currently active Revit view is marked with an "Active" label.

Hover over the "Active" label to display the tooltip:

**Tooltip:** Currently active Revit view.

### Views with View Templates

In Category mode, views with an applied view template are automatically unchecked, grayed out, and unavailable for selection.

Hover over a disabled view to display the message: "This view is controlled by a view template and cannot be processed." Switch to Elements mode to make these views available again.

**Image reference: Target view selection, Active view, and disabled templated views**

To be added later

## Refresh

While Hide in Views is open, you can change the selected elements or project views in Revit. Click "Refresh" to update Hide in Views with the current Revit state.

"Refresh" performs the following actions:

- Updates the current Revit element selection.
- Updates the selected-element count in Elements mode or recalculates the unique categories in Category mode.
- Reloads the available supported views and reevaluates their view-template status.
- Updates the Active view indicator if the active Revit view has changed.
- Preserves the currently selected target views where they remain valid for the active mode.
- Preserves the selected Elements or Category mode.
- Automatically unchecks and disables views with an applied view template in Category mode.

Hover over "Refresh" to display the tooltip:

**Refresh tooltip:** Refresh the current Revit element selection and available views while preserving the selected views and mode.

**Image reference: Refresh button**

To be added later

## Hide or Unhide

Choose an action:

- **Hide** - Hides the selected elements or collected categories in the selected views, according to the active mode.
- **Unhide** - Unhides the selected elements or collected categories in the selected views, according to the active mode.

In Elements mode, Hide and Unhide use Revit element-level visibility.

```yaml
# Note:
Unhiding an element removes its element-level hide state in the selected view. The element may still remain invisible if other Revit visibility settings or view conditions affect it.
```

In Category mode, Hide and Unhide turn the collected categories off or on through Revit Visibility/Graphics.

```yaml
# Note:
Unhiding a category turns that category back on in the selected view's Visibility/Graphics settings. Elements from that category may still remain invisible if other Revit visibility settings or view conditions affect them.
```

When the operation starts, a separate progress dialog displays the execution progress.

**Image reference: Execution progress dialog**

To be added later

After the operation is complete, a report displays the execution results.

The main Hide in Views window remains open, allowing you to perform additional operations without reopening the tool.

Steps:

1. Select different elements in Revit.
2. Click "Refresh".
3. Adjust the mode or target views if required.
4. Click "Hide" or "Unhide".

**GIF reference: Running multiple Hide/Unhide operations using Refresh**

To be added later

## Undo Considerations

Revit Undo can reverse a Hide or Unhide operation.

```yaml
# Note:
Undo reverses the entire Hide or Unhide batch operation, not individual views. If you perform other Revit actions after Hide or Unhide, multiple Undo steps may be required to return to the Hide or Unhide operation.
```

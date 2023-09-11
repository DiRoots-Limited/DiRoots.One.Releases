---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started
{: .no_toc }

ProSheets is 100% free for personal and commercial usage, regardless of the number of users. 
Not permitted:
-	Sell/resell
-	make modifications to the software.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Download

Download the [latest version of ProSheets](https://diroots.com/revit-plugins/revit-to-pdf-dwg-dgn-dwf-nwc-ifc-and-images-with-prosheets/).


## Install

### Compatibility
- Windows 7, 8, 10 and 11.
- Revit 2017, 2018, 2019, 2020, 2021, 2022 and 2023.

### Prerequisites
- Admin permissions.
- PDF24 (the compatible version will be automatically installed. Dont't do it manually).

```yaml
# Remarks
- the installation is done per-machine
- %ProgramData%\Autodesk\Revit\Addins\
```

### Standard Installation

```yaml
This method is ideal for individuals with admin permissions who want to install ProSheets in one computer.
```

1. Run ProSheets installer.

2. Select the Revit versions and click 'Install'.

![ProSheets Installation First Step](../assets/images/GIFs/PS-Install-Step-1.gif)

3 . Wait for the installation to complete and click 'Finish'.

![ProSheets Installation Finish](../assets/images/PS-Installer-Finished.png)

4. Restart your computer. Don't Skip this step.

### Silent Installation

```yaml
This method is ideal for IT administrators who want to deploy ProSheets to multiple computers.
```

- Install for all compatible Revit versions.

```yaml
# This method will silently install ProSheets for all compatible Revit versions.
<installer-name>.exe /i // /qn accept_eula=1
```

- Exclude specific Revit versions.

```yaml
# In this example ProSheets will NOT be installed for Revit 2017, 2018, and 2019.
<installer-name>.exe /i // /qn accept_eula=1 revit2017="" revit2018="" revit2019=""
```

## Uninstall

### Using the installer User Interface

1. Run ProSheets installer.

2. Select and click 'Remove'.

![ProSheets Uninstall](../assets/images/GIFs/PS-Uninstall.gif)

3 . Wait for the uninstallation to complete and click 'Finish'.

```yaml
# Remarks.
PDF24 shipped with ProSheets won't be uninstalled. If you want to remove it, uninstall it manually.
```

### Using the installer silently

Uninstall ProSheets without user interaction.

```yaml
# This method will remove ProSheets from your computer.
<installer-name>.exe /x // /qn
```

### From the control panel

1. In the search box on the taskbar, type Control Panel and select it from the results.

2. Select Programs > Programs and Features.

3. Press and hold (or right-click) on the program you want to remove and select Uninstall or Uninstall/Change. Then follow the directions on the screen.

## Updates

ProSheets includes an updater to help you keep it up to date. 
The updater will:
- notify you whenever a new version is released (the action is triggered on Revit close event).
- ask you to install now or to remind you tomorrow.

![ProSheets Updater UI](../assets/images/updater-default.png)

### Updater Settings

The following Update Options can be tweaked:
- activate automatic updates.
- check for updates frequency (the default value is 2 days). 
- change the downloads folder.

```yaml
# Pro Tip for Users
By default the automatic updates can't be disabled.
To go around it, you can set up the check for updates frequency to 365 days, for example.
# Keep in mind that it' recommended to keep your apps updated. Plus, we do not provide support for outdated applications.
```

```yaml
# Pro Tip for IT Administrators
By default the automatic updates can't be disabled.
To go around it, there's a configuration file that can be tweaked.

# Steps required
- go to %programdata%\DiRoots.ProSheets\Settings
- open the 'updater.ini' file
- Search for the line 'CheckFrequency=2' and change the value to 365, for example.

# Keep in mind that it' recommended to keep your apps updated. Plus, we do not provide support for outdated applications.
```

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

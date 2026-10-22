---
layout: default
title: Getting Started
nav_order: 2
nav_sections:
  - title: "Download"
    anchor: download
  - title: "Install"
    anchor: install
---

# Getting Started
{: .no_toc }

DiRootsOne is a productivity toolkit for Autodesk Revit. Its tools help you manage model data, filter and inspect models, automate views and sheets, create tables, and work with point clouds.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Download

Download the [latest version of DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).


## Install

### Compatibility
- Revit 2018–2027.
- Windows requirements depend on the Revit version. Revit 2027 requires 64-bit Windows 11; see [Autodesk's Revit system requirements](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/System-requirements-for-Revit-2027-products.html) for details.

### Standard Installation

This method is ideal for installing DiRootsOne on a single computer.

1. Run DiRootsOne installer.

2. Select the Revit versions and click 'Install'.

![DiRootsOne Installation First Step](..\assets\images\One-Installer.gif)

3. Wait for the installation to complete and click 'Finish'.

![DiRootsOne Installation Finish](..\assets\images\One-Installer-Finished.png)

### Silent Installation

This method is for IT administrators deploying DiRootsOne to multiple computers.

- Install for all compatible Revit versions.

```cmd
<installer-name>.exe /i // /qn accept_eula=1
```

- Disable automatic check for update (i.e., users won't be prompted to install updates).

```cmd
<installer-name>.exe /i // /qn accept_eula=1 UPDATER="FALSE"
```

- Exclude specific Revit versions.

```cmd
<installer-name>.exe /i // /qn accept_eula=1 revit2018="" revit2019="" revit2020=""
```

## Uninstall

### Using the installer User Interface

1. Run DiRootsOne installer.

2. Select and click 'Remove'.

![DiRootsOne Uninstall](..\assets\images\One-Installer-Finished.png)

3. Wait for the uninstallation to complete and click 'Finish'.

### Using the installer silently

Uninstall DiRootsOne without user interaction.

```cmd
<installer-name>.exe /x // /qn
```

### From the control panel

1. In the search box on the taskbar, type Control Panel and select it from the results.

2. Select Programs > Programs and Features.

3. Press and hold (or right-click) on the program you want to remove and select Uninstall or Uninstall/Change. Then follow the directions on the screen.

## Updates

The updater checks for new versions as you close Revit. If an update is available, it lets you install it or be reminded the next day.

![DiRootsOne Updater UI](../assets\images\DiRootsOne-Updates.png)

### Updater Settings

By default, Updater Settings does not provide an option to disable automatic update checks. Administrators can change how often the updater checks by editing its configuration file:

1. Go to `%programdata%\DiRoots.DiRootsOne\Settings`.
2. Open `updater.ini`.
3. Change `CheckFrequency=2` to `CheckFrequency=365`, for example, to check less frequently.

For unattended deployments, automatic update checks can also be disabled with the `UPDATER="FALSE"` installer option shown above.

We recommend keeping DiRootsOne up to date. Support is not provided for outdated versions.

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

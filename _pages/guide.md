---
layout: page
title: Guide
include_in_header: true
---

**Last updated**  
Aug 17, 2024

# Guide
This guide describes basic operation of EBG: El Box Glance.
<br>

## 1. Installation

* Visit the Apple Store and search for “ebg or El Box Glance” or [Go to App Store from here](https://apps.apple.com/us/app/el-box-glance/id6449521968?mt=12&itsct=apps_box_badge&itscg=30200).
* Purchase and Install; Click on the price button to purchase the app. After the purchase is complete, the app will automatically download and install on your device.

## 2. Preparation

* Identify your host machine architecture:
    * Use 'aarch64' or 'arm64' for Apple Silicon chips.
    * Use 'x86' or 'amd64' for Intel-based chips.
   
* System Image Installer:
   * Download macOS (ipsw) system image from the official Apple website, compatible with Apple Silicon chips.
   * Download a Linux distro (iso) system image that matches your architecture.

*Note: Official latest macOS release and free systems from various vendors are available to download directly within the setup panel.*

## 3. Working with pre-installed system images (raw,img)

* Starting from version 3.3 import preinstalled image with raw format, a original file won't be edited by changes instead it will be cloned to a sandbox.
* Alternative optition to run a vm with preinstall image:
    * Use Network Block Device (NBD) server.
    * Manually replace a new/existing box image with a pre-installed image on your host machine file system.

## 3. Configuration

    The default configuration of EBG includes:
        x2 Encryption Controller
        x2 Core vCPU
        2GB RAM
        32GB Storage Disk
        Keyboard Device
        Pointing Device
        
* You can adjust these settings as per your requirements within the application.

## 4. Uninstallation

To remove EBG and related data from your host machine, follow these steps:
* Select ‘Erase All Boxes’ from El Box Glance option in the Menu bar.
* Navigate to the Application folder and remove El Box Glance.

## 5. Contact Us

If you have any questions or need further clarification, don’t hesitate to contact us.

    info@elboxglance.com

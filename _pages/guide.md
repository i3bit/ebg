---
layout: page
title: EBG User Guide
include_in_header: true
---

**Last updated**
December 30, 2024

## Guide
This guide explains the basic operations of EBG: El Box Glance.
<br>

## 1. Installation

* Visit the Apple Store and search for "ebg" or "El Box Glance." Alternatively, [access the App Store from this link](https://apps.apple.com/us/app/el-box-glance/id6449521968?mt=12&itsct=apps_box_badge&itscg=30200).
* Proceed with the purchase and installation process. Click on the "Price" button to initiate the transaction. Upon completion, the app will automatically download and install on your device.

## 2. Preparation

* **Host Machine Architecture Identification:**
    * For Apple Silicon chips, use "aarch64" or "arm64" as the processor architecture. Some images of "armv8" may also be compatible.
    * For Intel-based chips, use "x86" or "amd64".
* **System Image Installer:**
    * For Apple Silicon chips, download the macOS (ipsw) system image from the official Apple website.
    * For Intel-based chips, download a Linux distro (iso) system image that corresponds to your architecture.

* **Note:** Official latest macOS releases and complimentary systems from various vendors are conveniently accessible within the setup panel.

## 3. Working with Pre-Installed System Images (raw/img)

* EBG now supports importing pre-installed images in raw/img format, commonly referred to as Master Boot Record (MBR), starting from version 3.3.
* Alternative methods to execute a virtual machine with a pre-installed system image include:
    * Utilizing a Network Block Device (NBD) server.
    * Manually replacing an existing box image with a pre-installed image on your host machine's file system.

## 4. Configuration

The default EBG configuration includes:

    * Two Encryption Controllers
    * Two Core vCPUs
    * 2GB of RAM
    * 32GB of Storage Disk
    * Keyboard Device
    * Pointing Device
    
You can tweak these settings right within the app using the user interface configuration.

## 5. Uninstallation

* To remove EBG and any associated data from your host machine, follow these steps:
    * Select "File" > "Delete All Boxes" from "El Box Glance" menu bar.
    * Navigate to the Application folder and delete the "El Box Glance" application.
    * Remove the app container folder from your system.
    
## 6. Contact Us

Should you have any inquiries or require further clarification, please do not hesitate to contact us.

info@elboxglance.com

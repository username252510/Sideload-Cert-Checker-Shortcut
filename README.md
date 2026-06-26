# 🛠️ Sideload Cert-Checker Shortcut
> A powerful iOS shortcut that instantly checks the status of a signing certifcate pair using FlareStore's publicly available API.

An advanced, native iOS shortcut designed to check your iOS code signing certificates (`.p12`) and provisioning profiles (`.mobileprovision`) against Apple's servers in seconds.

## ⚖️ Disclaimer & ToS Compliance
* **Unofficial Client:** This tool is an independent and community driven project and is not officially affiliated with, endorsed by, or partnered with FlareStore.
* **Liability:** Use this tool at your own risk. I am not liable for how FlareStore handles, stores, processes, or utilizes your certificate pair or password once the data is transmitted to their API. Additionally, I am not responsible for API rate limits, server side data management, key revocations, or any service modifications implemented by FlareStore or Apple.

## 🔗Get The Shortcut

[**Install via iCloud**](https://www.icloud.com/shortcuts/54075212154649d19a52c804a780a3ce)

<sub>Download the raw shortcut file directly from this repository:  
[**Download .shortcut File**](https://github.com/username252510/Sideload-Cert-Checker-Shortcut/raw/6643e774359ab7babc2766b3cb85355828d5a16d/ShortcutFiles/Con%E2%80%99s%20Certificate%20Checker%20V1.shortcut)

## 🚀 Installation & Setup

Follow these steps to install and configure the shortcut on your device with your certificate.

### 📋 Prerequisites
Before setting up the shortcut, ensure you have these ready:
* An iOS device running a recent iOS version with the official Apple **Shortcuts** app installed.
* The certificate files you want to use (your `.p12` file, its password, and your `.mobileprovision` file).

### 📥 Step 1: Download the Shortcut
Choose **one** of the links above to add the utility to your Shortcuts app. Use the iCloud link if you dont know which to use.

### ⚙️ Step 2: Configure Import Questions
When installing the shortcut, iOS should prompt you with **Import Questions** to import your certificates.

1. **Enter Certificate Password:** Enter the password associated with your `.p12` file. If you use a signing app, this is the same password used when importing your certifcate to Feather, Ksign, Esign, etc. Make sure that it is typed 100% correctly with no extra spaces or line breaks, otherwise the checker will fail.
2. **Select .p12 File:** Tap on the blue "File" button, it should open up a native files app window. Navigate to your `.p12` file, select only it, and press open.
3. **Select Provisioning Profile:** Repeat the same step you just did, exept this time select only your `.mobileprovision` file.

### 🛠️ Step 3: Running Diagnostics
Once setup is complete, run the shortcut to test it.

1. Tap on the shortcut name "Con's Certificate Checker V_"
2. In a few seconds it should return a popup with your certifcate status.

Double check that "🔗Valid Pair: Yes:". If it says No it means that you have accidently imported `.p12` and `.mobileprovision` files that aren't associated with eachother. Hold down on the shortcut from the main menu on the shortcut library, and press edit. From here your chosen certificate files should be right there. You can hold down on the blue chosen file (making sure not to accidently drag the file action box), press clear to remove it, and tap on the blue "file" button, and re-import your certificate files. Make sure that you import your `.p12` file on the top box and your `.mobileprovision` on the box under it.


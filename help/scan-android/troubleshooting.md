---
title: Adobe Scan DC for Android
solution: Acrobat DC
---

# Troubleshooting {#troubleshooting}

## Getting more help {#getting-more-help}

The user community is an excellent resource. Feel free to ask a question on the [Adobe Scan Forum](https://forums.adobe.com/community/document-cloud/scanandroid). 

## Bugs & feature requests {#bugs-&-feature-requests}

The team appreciates feedback and ideas, and you can [file a bug or feature request](https://www.adobe.com/go/scaniosfeedback) online.

## Errors and issues {#errors-and-issues}

**Why is the app asking for photo and camera access?**

To use the camera or photo, you must grant the app access to those device features. For configuration details, see [Settings](settings.md).

**Why can't I install Adobe Scan on my device?**

The app can only be installed on devices with Android 6.0 and later.

**Refresh failed. Please check your network connection.**

* Verify you have a good network connection. For example, open a browser and try to open a web page. 
* If you do not have wifi enabled, verify you have checked **Allow Upload on Cellular**.

**Why do I see "Unable to Modify Scan: Files that have been altered outside of Adobe Scan cannot be modified"?**

While the March, 2018 release introduced a new modify scan feature, you cannot modify scanned files which have been altered outside of Adobe Scan. For example, if you have opened a scan in Acrobat and have added comments, added attachments, organized pages, and so on, Adobe Scan will not be able to modify that file.

Troubleshooting OCR {#troubleshooting-ocr}

**Why can't I select, edit, and comment or markup text?**

OCR must be enabled. When it is, you should be able to copy and search text from the scan app. Working with converted text requires Acrobat Reader. If you've installed Acrobat Reader, tap **Open in Acrobat** to work with the text.

**Why does OCR not appear to work on parts of my document?**

Because OCR is a complex conversion that relies on consuming recognizable text, certain document characteristics may degrade the quality of optical character recognition output. For example, the following conditions may impair OCR quality: 

* A dark colored background
* A source document with multiple languages
* A rotated source document
* Scanning under light conditions that are too bright or dark
* A network connection and an Adobe Document Cloud connection is required

**Why does OCR (text recognition) not work or produce a result in English?**

The app is localized in 19 languages and supports text recognition for all of those languages. However, note the following:  

* If the app is installed on an OS using an unsupported language, the default output is English. 
* If you've selected a language to recognize that doesn't match the document language, OCR produces no output. For example, the scanned document is German and you set Danish as the text recognition language. 

## Determining who is logged in {#determining-who-is-logged-in}

The currently logged in user can be viewed by tapping ![image](./images/hamburgericon.png) from either file list screen. The logged in user appears at the top of the screen.

## Determining your application version {#determining-your-application-version}

1. Tap ![image](./images/hamburgericon.png)
1. Tap ![image](./images/infoicon.png) > **About Adobe Scan**. 

## Finding your operating system version {#finding-your-operating-system-version}

1. Open your device's settings screen. 
1. Tap **About Phone** (or **About Device**). 

   >[!NOTE]
   >
   > The path may vary on different devices.

The *Version* field displays your software version.

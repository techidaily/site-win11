---
title: Tackling Incompatible Application Downloads on Microsoft Store
date: 2024-06-25T10:27:37.421Z
updated: 2024-06-26T10:27:37.421Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Incompatible Application Downloads on Microsoft Store
excerpt: This Article Describes Tackling Incompatible Application Downloads on Microsoft Store
keywords: App Compatibility Issues,Windows Store Fixes,Download Errors MS,Software Installation Troubleshoot,Updating Store Downloads,Microsoft Store Solutions,Incompatible App Resolution
thumbnail: https://thmb.techidaily.com/dc5fff1a9acb5e2e1b1bb4c72b06c12c5151a76a3bb3ac96ddd883f3e1ef8520.jpg
---

## Tackling Incompatible Application Downloads on Microsoft Store

 The Microsoft Store lets you install verified apps securely from its app store. However, when you try to install an app, you may encounter an error that says "this app couldn’t be installed." This can happen with a specific app or all the apps you want to install.

 The problem can be as simple as a corrupted Microsoft Store cache or issues with system files. Here are a few troubleshooting steps to quickly resolve this error and get Microsoft Store working again.

## 1\. Run the Microsoft Store Troubleshooter

![windows store apps troubleshooter 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter-1.jpg)

 You can quickly fix common Microsoft Store problems using the Windows Store Apps troubleshooter. It is a built-in troubleshooting utility that can scan and fix issues preventing the Microsoft Store from installing apps.

To run the Windows Store Apps troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshooter.**
3. Next, click on**Other troubleshooters.**
4. Scroll down and click on the**Run** button for Windows Store Apps. The troubleshooter will perform a scan and recommend fixed. Apply any recommended fixes and check for improvements.

## 2\. Clear and Reset the Windows Store Cache Using WSReset

![wsreset clear microsoft store cache](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/wsreset-clear-microsoft-store-cache.jpg)

 WSReset or Windows Store Reset is a built-in utility to reset or clear Windows Store Cache. Resetting the store cache can help you fix temporary glitches preventing you from installing apps from Microsoft Store.

To reset the Windows Store cache:

1. Press the**Win** key and type**wsreset** .
2. Click on**wsreset** –**run command** from the search result. This will open a black Window that will reset the Windows Store cache. The window will close automatically and launch Microsoft Store.
3. Close Microsoft Store and then relaunch the app to see if the error is resolved.

## 3\. Restart the Microsoft Store Install Service

 Microsoft Store Install service provides support for the Microsoft Store and starts on demand. If the service is disabled, you may not be able to install apps from the store resulting in the "this app couldn’t be installed" message.

 To fix the error, check if the service is running. If not, you can enable it manually using the Services snap-in.

To restart Microsoft Store Install Service:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Services** snap-in, locate the**Microsoft Store Install Service** entry.  
![microsoft store install service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-properties.jpg)
4. Right-click on the service entry and select**Properties** .
5. In the**Properties** dialog, check if the**Startup type** is set to**Disabled** .  
![microsoft store install service manual startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-manual-startup-type.jpg)
6. If yes, click the**Startup type** drop-down and select**Manual** .  
![microsoft store install service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-restart.jpg)
7. Click**Apply** and**OK** to save the changes.
8. Next, right-click on**Microsoft Store Install Services** and select**Restart** .

 Close the Services snap-in and launch Microsoft Store. Then, try to install the app and check if the error is resolved.

## 4\. Perform a Microsoft Store Repair

![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 You can use the built-in repair tool to fix common issues that may prevent the Microsoft Store from triggering such errors. Follow these steps to repair the Microsoft Store app.

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed apps** .
4. Next, search for**Microsoft Store.**
5. Click the**three-dots menu** and select**Advanced options.**
6. Scroll down to the**Reset** section.
7. Click on**Repair** and wait for the process to complete.
8. Once done, relaunch Microsoft Store and try to install the app to see if the error is resolved.

## 5\. Manually Reset Microsoft Store Apps

![reset microsoft store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/reset-microsoft-store.jpg)

 You can manually reset the Microsoft Store app from the Settings app. The Reset option will delete all the app data, and you may need to log in to use Microsoft Store again.

To reset Microsoft Store:

1. Press**Win + I t** o open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed apps** to view all the apps installed on your PC.
4. Search for the**Microsoft Store** app.
5. Click the**three-dots menu** and select**Advanced Options.**
6. Scroll down to the**Reset** section.
7. Click on**Reset** and again on the**Reset** button to confirm the action.
8. Once the**reset** is complete, you’ll see a**checkmark** beside the**Reset** button.

 Launch Microsoft Store and sign in with your Microsoft Account if required. Then, try to install the app and check for any improvements.

## 6\. Re-register the Microsoft Store App

![powershell re_register microsoft store app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-re_register-microsoft-store-app.jpg)

 Another way to fix the "this app couldn’t be installed" error is to re-register the Microsoft Store using PowerShell. Here’s how to do it.

1. Make sure**Microsoft Store** is closed.
2. Next, press the**Win key** and type**powershell** .
3. Right-click on**PowerShell** and select**Run as administrator.**
4. In the PowerShell window, type the following command to re-register the app for the current user:  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
5. Wait for the command to process and close PowerShell. Relaunch Microsoft Store and check if you can install the app without the error.

## 7\. Reinstall the Microsoft Store

 You can reinstall Microsoft Store to fix issues with the app due to corrupt app files or bugs. Since clearing the cache didn’t help, you can perform a reinstall to resolve the error.

 Note that Microsoft Store is a system app. As a result, you cannot uninstall it from the Settings panel. Instead, you’ll need to use the**Get-AppxPackage** cmdlet in PowerShell to remove and reinstall the app.

 Make sure to[create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before uninstalling Microsoft Store. When something goes awry, you can use the restore point to undo the changes and restore your PC to its current state.

To reinstall Microsoft Store:

1. Press the**Win** key and type**powershell** .
2. Right-click on Windows PowerShell and select**Run as administrator.**  
![remove microsoft store powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remove-microsoft-store-powershell.jpg)
3. Next, in the PowerShell Windows, type the following command and press Enter:  
`get-appxpackage *store |remove-appxpackage`
4. Once the app is removed, use the following command to reinstall Microsoft Store:  
`Get-AppxPackage -AllUsers Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}  

`
5. Wait for the app to install successfully. Then, type**exit** and press**Enter** to close PowerShell.  
![reinstall microsoft store powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/reinstall-microsoft-store-powershell.jpg)
6. Press**Win** key and type**Microsoft Store** to launch the app.

## Fixing the "This App Couldn’t Be Installed" Error on Windows

 This error is often due to issues with the corrupt app cache and temporary glitches. Use the Windows Store Apps troubleshooter or run the WSreset tool to fix common problems with Microsoft Store. If the issue persists, you can perform a reset or re-register the app to resolve the error.

 That said, if the issue persists with a specific app, you can download the Microsoft Store apps using a third-party service and install them manually on your PC.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mending-your-silent-windows-headset-mic/"><u>Mending Your Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-windows-bar-make-it-transparent-on-win11/"><u>Invisible Windows Bar: Make It Transparent on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-tricks-for-mass-folder-creation-at-a-click-in-windows-oses/"><u>The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-user-sign-in-after-windows-authentication-issues/"><u>Enabling User Sign-In After Windows Authentication Issues</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/maxing-out-melodies-best-5-apps-for-boosting-windows-audio-by-100plus/"><u>Maxing Out Melodies: Best 5 Apps for Boosting Windows' Audio By 100%%+</u></a></li>
<li><a href="https://win11.techidaily.com/studio-2-unleashed-microsofts-near-perfect-creator-tool/"><u>Studio 2 Unleashed: Microsoft's Near-Perfect Creator Tool</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-flow-optimize-your-windows-11-hdd/"><u>Mastering Data Flow: Optimize Your Windows 11 HDD</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-android-and-windows-gameplay-unification-with-google-play/"><u>Bridge Android and Windows: Gameplay Unification with Google Play</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-honor-magic-6-pro-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Honor Magic 6 Pro?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-segmented-screen-success-is-splitcam-superior/"><u>[Updated] 2024 Approved  Segmented Screen Success  Is SplitCam Superior?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unleash-your-creativity-with-personalized-filters-and-melodies-windows-10-photos/"><u>Unleash Your Creativity with Personalized Filters and Melodies (Windows 10 Photos)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-capturing-twitters-fun-android-and-iphone-tips/"><u>[Updated] 2024 Approved  Capturing Twitter's Fun  Android & iPhone Tips</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-secure-tiktok-follower-expansion-companies/"><u>In 2024, Secure TikTok Follower Expansion Companies</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-use-filmora-slideshow-maker-for-making-slideshow-what-is-slideshow-filmora-know-the-steps-to-make-filmora-slideshow-what-are-steps-/"><u>New 2024 Approved How to Use Filmora Slideshow Maker for Making Slideshow? What Is Slideshow Filmora? Know the Steps to Make Filmora Slideshow. What Are Steps to Make Filmora Slideshow Template?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-crystalview-webcam-studio/"><u>In 2024, CrystalView Webcam Studio</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ultimate-guide-cost-effective-pc-screen-recording-apps-for-2024/"><u>Ultimate Guide  Cost-Effective PC Screen Recording Apps for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-transforming-videos-into-photos-the-top-10-conversion-tools/"><u>Updated Transforming Videos Into Photos The Top 10 Conversion Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-ascending-with-asmr-top-strategies-for-video-creation-for-2024/"><u>[Updated] Ascending with ASMR  Top Strategies for Video Creation for 2024</u></a></li>
</ul></div>

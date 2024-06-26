---
title: Unlock Home View in Windows 11 Settings
date: 2024-06-25T11:25:34.408Z
updated: 2024-06-26T11:25:34.408Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Home View in Windows 11 Settings
excerpt: This Article Describes Unlock Home View in Windows 11 Settings
keywords: Unlock Window View,Windows 11 Screen Access,Enable Home Screens,Windows Settings Viewing,Windows 11 Home Screen,Enter Home View Mode,Toggle Home Display
thumbnail: https://thmb.techidaily.com/fb9dc69321147c58e76f643c816e11fbbc732b6fd56c746767b53b83551e6f78.jpg
---

## Unlock Home View in Windows 11 Settings

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  
`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-a-bricked-windows-update-fix/"><u>Bypassing a Bricked Windows Update Fix</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-grammarlys-non-operational-status/"><u>Troubleshooting Grammarly's Non-Operational Status</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-schedule-with-winning-windows-to-dos/"><u>Mastering Your Schedule with Winning Windows To-Dos</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-prior-to-starting-the-window-operating-system-renewal/"><u>Key Steps Prior to Starting the Window Operating System Renewal</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-incompatible-application-downloads-on-microsoft-store/"><u>Tackling Incompatible Application Downloads on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-temporary-path-errors-quick-fix-guide-for-windows-error-1152/"><u>Tackling Temporary Path Errors - Quick Fix Guide for Windows Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-cpu-and-ram-overuse-caused-by-unrealcefsubprocess-on-pcs/"><u>Mitigating CPU and RAM Overuse Caused by UnrealCEFSubprocess on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-gpu-functionality-in-windows-10-and-11-easy-fixes/"><u>Refreshing GPU Functionality in Windows 10 & 11 Easy Fixes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastering-the-art-of-personalizing-video-covers-for-facebook-for-2024/"><u>Mastering the Art of Personalizing Video Covers for Facebook for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-seamless-transitions-the-art-of-color-matching-in-powerdirector/"><u>New Seamless Transitions The Art of Color Matching in PowerDirector</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-samsung-galaxy-a15-5g-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Samsung Galaxy A15 5G Phone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oneplus-11rfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your OnePlus 11RFRP Lock</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-honor-magic-5-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-anonymous-access-to-instagrams-hidden-narratives-device-guide/"><u>In 2024, Anonymous Access to Instagram's Hidden Narratives  Device Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-visionary-tech-that-cares-for-the-earth-for-2024/"><u>[New] Visionary Tech That Cares for the Earth for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-essential-tips-for-saving-and-recording-on-periscope/"><u>[New] Essential Tips for Saving & Recording on Periscope</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-demystifying-vimeos-triplet-plans-for-content-creators/"><u>[Updated] Demystifying Vimeo's Triplet Plans for Content Creators</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-approaches-transforming-pinner-video-links-into-audios/"><u>2024 Approved  Ideal Approaches  Transforming Pinner Video Links Into Audios</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
---
title: Mastering the Art of Installing New Drivers in Windows 11
date: 2024-06-25T09:46:28.287Z
updated: 2024-06-26T09:46:28.287Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Installing New Drivers in Windows 11
excerpt: This Article Describes Mastering the Art of Installing New Drivers in Windows 11
keywords: Windows Driver Update Guide,Windows 11 Driver Installation,Nvidia Driver Installation W11,AMD Firmware Update Windows 11,Windows Drivers for Optimal Performance,Microsoft Windows Hardware Compatibility,New Driver Installation Tips Windows
thumbnail: https://thmb.techidaily.com/afcb9c2878394644f41c39d4475ac640d665c752413696b921520d8ad80368e6.jpg
---

## Mastering the Art of Installing New Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/avoid-windows-zoom-obstacles-stop-code-1132-issues/"><u>Avoid Windows Zoom Obstacles: Stop Code 1132 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-volume-mixer-in-the-action-center-in-windows-11/"><u>How to Enable the Volume Mixer in the Action Center in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-phones-capability-for-windows-recording/"><u>Streamline Phone's Capability for Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-creativity-personalizing-windows-1011-screens/"><u>Unleash Creativity: Personalizing Windows 10/11 Screens</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-blank-windows-11-logins/"><u>Guide to Fixing Blank Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-powertoys-on-win11/"><u>Enhancing User Experience: PowerToys on Win11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-invisible-footage-methods-to-obfuscate-private-elements/"><u>[New] Invisible Footage  Methods to Obfuscate Private Elements</u></a></li>
<li><a href="https://extra-resources.techidaily.com/titling-techniques-an-after-effects-perspective/"><u>Titling Techniques  An After Effects Perspective</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-streamlining-production-workflow-extracting-audio-separately-on-a-mac-with-imovie/"><u>New Streamlining Production Workflow Extracting Audio Separately on a Mac with iMovie</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-essential-tactics-for-adding-vimeo-clips-to-powerpoint-slides/"><u>[New] In 2024, Essential Tactics for Adding Vimeo Clips to PowerPoint Slides</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/podcast-summary-genius-guidance-and-examples-for-2024/"><u>Podcast Summary Genius  Guidance & Examples for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-scriptwriting-a-comprerancial-guide-to-slug-lines/"><u>2024 Approved  Scriptwriting  A Comprerancial Guide to Slug Lines</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-quality-movie-maker-turn-everyday-video-clips-into-a-high-quality-movie-for-2024/"><u>New Quality Movie Maker Turn Everyday Video Clips Into a High Quality Movie for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-best-video-editors-for-windows-11/"><u>Updated 2024 Approved Best Video Editors for Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-discover-the-world-of-screen-capture-with-apowersofts-free-version/"><u>In 2024, Discover the World of Screen Capture with Apowersoft's Free Version</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
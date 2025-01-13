---
title: "Resolving Windows 11: Drivers Not Loading Issue"
date: 2025-01-05T23:03:42.756Z
updated: 2025-01-12T18:20:56.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows 11: Drivers Not Loading Issue"
excerpt: "This Article Describes Resolving Windows 11: Drivers Not Loading Issue"
keywords: Win11 Driver Fix,LoadDriversWin,Win11 Boot Failure,XRDP Error Win,Windows Update Error,Safe Mode for Win11,Loading Drivers Issue
thumbnail: https://thmb.techidaily.com/0f9975c7424be8ab80f0e3edfa04cf204d756fbbde35db8886dbe8cbc049b368.jpg
---

## Resolving Windows 11: Drivers Not Loading Issue

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-your-complete-guide-to-starting-a-zoom-conversation-on-an-android-device/"><u>[New] Your Complete Guide to Starting a Zoom Conversation on an Android Device</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-lightened-transition-tactics/"><u>[Updated] In 2024, Lightened Transition Tactics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-streamlining-media-transfer-fb-video-to-whatsapp/"><u>[Updated] Streamlining Media Transfer FB Video to WhatsApp</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-samsung-galaxy-a05-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Samsung Galaxy A05</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-11s-inability-to-open-files-for-writing/"><u>Correcting Windows 11'S Inability to Open Files for Writing</u></a></li>
<li><a href="https://win11.techidaily.com/credential-manager-your-problem-solving-companion/"><u>Credential Manager: Your Problem-Solving Companion</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-update-restrictions-a-guide-to-uninstalling-apps/"><u>Easing Windows Update Restrictions: A Guide to Uninstalling Apps</u></a></li>
<li><a href="https://fox-blue.techidaily.com/elevating-android-video-to-a-new-level-time-lapse-excellence/"><u>Elevating Android Video to a New Level Time-Lapse Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restoring-touch-key-positions-in-win-11/"><u>Guidelines for Restoring Touch Key Positions in Win 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-realme-v30-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Realme V30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-in-the-win-11-start-menu/"><u>Increase Visible Pins in the Win 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/insights-into-pagefilesys-functionality-on-windows-systems/"><u>Insights Into Pagefile.sys Functionality on Windows Systems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mac-users-launch-your-own-sports-videography-hub/"><u>Mac Users Launch Your Own Sports Videography Hub</u></a></li>
<li><a href="https://win11.techidaily.com/revive-sleeping-pcs-with-keys-and-mice-on-windows-1011/"><u>Revive Sleeping PCs with Keys and Mice on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/seven-strategies-to-start-using-windows-11-widgets/"><u>Seven Strategies to Start Using Windows 11 Widgets</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/troubleshooting-guide-fixing-unrecognized-usb-devices-on-windows-10/"><u>Troubleshooting Guide: Fixing Unrecognized USB Devices on Windows 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/turn-off-youtubes-quick-video-buffering-feature/"><u>Turn Off YouTube's Quick Video Buffering Feature</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-global-precision-advanced-mouse-navigation-via-powertoys/"><u>Unlocking Global Precision - Advanced Mouse Navigation via PowerToys</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>What Pokémon Evolve with A Dawn Stone For Apple iPhone SE (2020)? | Dr.fone</u></a></li>
</ul></div>


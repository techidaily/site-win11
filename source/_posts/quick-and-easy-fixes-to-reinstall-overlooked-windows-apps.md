---
title: Quick and Easy Fixes to Reinstall Overlooked Windows Apps
date: 2024-08-28T00:56:39.572Z
updated: 2024-08-29T00:56:39.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick and Easy Fixes to Reinstall Overlooked Windows Apps
excerpt: This Article Describes Quick and Easy Fixes to Reinstall Overlooked Windows Apps
keywords: Quick Windows Repair,Easy App Reinstall,Restore Missing Windows,Instant App FIX,Fast App Reinstatement,Windows App Recovery,Rapid Fix Overlooked Apps
thumbnail: https://thmb.techidaily.com/e05f2d33f2fefb8dc7c06028c76750542668dde0166f66e5a57d5c818d2809aa.jpg
---

## Quick and Easy Fixes to Reinstall Overlooked Windows Apps

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the[DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the[ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best[ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try[installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://fox-cloud.techidaily.com/new-create-brand-symbols-from-templates-at-no-cost/"><u>[New] Create Brand Symbols From Templates at No Cost</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-top-4-pcmac-full-screen-recorders-ultimate-guide/"><u>[New] Top 4 PC/Mac Full-Screen Recorders  Ultimate Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-understanding-and-executing-photo-gender-modification-online/"><u>[New] Understanding and Executing Photo Gender Modification Online</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-gliding-giants-olympic-skate-tales/"><u>[Updated] 2024 Approved  Gliding Giants  Olympic Skate Tales</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-visualize-success-free-templates-to-elevate-your-youtube-presence-for-2024/"><u>[Updated] Visualize Success  Free Templates to Elevate Your YouTube Presence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cracking-the-code-locating-blue-screens-in-log-files/"><u>Cracking the Code: Locating Blue Screens in Log Files</u></a></li>
<li><a href="https://win11.techidaily.com/customize-win11-optimal-predefined-window-sizes/"><u>Customize Win11: Optimal Predefined Window Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-interface-with-three-column-widgets-in-win11/"><u>Elevate Your Interface with Three-Column Widgets in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-file-management-and-editing-learn-to-use-text-actions-in-snip/"><u>Enhance File Management & Editing: Learn to Use Text Actions in Snip</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-microsoft-edge-on-win11/"><u>Eradicating Microsoft Edge on Win11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-download-compatible-zexmte-bluetooth-dongle-driver-for-windows-10-7-and-8/"><u>Free Download: Compatible ZexMTE Bluetooth Dongle Driver for Windows 10, 7 & 8</u></a></li>
<li><a href="https://techtrends.techidaily.com/guide-to-fixing-hard-drive-issues-in-windows-10-a-step-by-step-tutorial/"><u>Guide to Fixing Hard Drive Issues in Windows 10: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/hibernate-havoc-heres-how-to-quell-the-chaos/"><u>Hibernate Havoc? Here's How to Quell the Chaos</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-the-killer-javascript-issue-on-discord-windows-11/"><u>How to Tackle the Killer Javascript Issue on Discord Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-engage-with-windows-11-privilege-center/"><u>Locate and Engage with Windows 11 Privilege Center</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-kali-linux-setup-on-windows/"><u>Mastering Kali Linux Setup on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-savings-on-windows-11-keys/"><u>Maximizing Savings on Windows 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-fullscreen-challenges-with-sonic-gameplay-w11-version/"><u>Navigating Fullscreen Challenges with Sonic Gameplay, W11 Version</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-elevate-your-edit-6-essential-adobe-premiere-pro-tips-and-techniques/"><u>New 2024 Approved Elevate Your Edit 6 Essential Adobe Premiere Pro Tips and Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/optimize-your-mobile-browsing-with-cleaner-video-playback/"><u>Optimize Your Mobile Browsing with Cleaner Video Playback</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-effective-windows-note-tips-and-tricks/"><u>Quick and Effective Windows Note Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-correcting-the-isdonedll-error-on-windows-11/"><u>Quick Fix: Correcting the ISDone.dll Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedy-restoring-functionality-to-your-windows-pen-device/"><u>Quick Remedy: Restoring Functionality to Your Windows Pen Device</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-the-joy-of-win-11-gaming-master-these-seven-game-changing-tweaks/"><u>Reignite the Joy of Win 11 Gaming: Master These Seven Game-Changing Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/removing-unwanted-html-from-your-windows-11-mail-previews/"><u>Removing Unwanted HTML From Your Windows 11 Mail Previews</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/resolve-your-iphone-13-mini-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>Resolve Your iPhone 13 mini Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-adjustments-through-quick-key-tricks/"><u>Seamless Windows Adjustments Through Quick Key Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resurrect-ccleaner-in-windows-11/"><u>Steps to Resurrect CCleaner in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-elevating-taskmanager-position/"><u>Techniques for Elevating TaskManager Position</u></a></li>
<li><a href="https://win11.techidaily.com/the-fusion-of-ages-seven-windows-characteristics-persisting-into-11/"><u>The Fusion of Ages: Seven Windows Characteristics Persisting Into 11</u></a></li>
<li><a href="https://facebook.techidaily.com/the-rise-of-telegram-amidst-facebook-shutdown/"><u>The Rise of Telegram Amidst Facebook Shutdown</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-list-mastering-youtubes-best-music-reaction-videos-for-2024/"><u>The Ultimate List  Mastering YouTube's Best Music Reaction Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-alternate-antivirus-without-defenders-restrictions/"><u>Tips for Integrating Alternate Antivirus without Defender’s Restrictions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-realme-12-proplus-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Realme 12 Pro+ 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/transform-videos-on-windows-discover-these-8-outstanding-apps/"><u>Transform Videos on Windows - Discover These 8 Outstanding Apps</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-potential-virus-clues-in-windows-task-scheduling/"><u>Understanding Potential Virus Clues in Window's Task Scheduling</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-screens-activatingdeactivating-windows-spotlight-features/"><u>Unlocking Screens: Activating/Deactivating Windows' Spotlight Features</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-get-started-with-free-video-blurring-a-beginners-guide-for-2024/"><u>Updated Get Started with Free Video Blurring A Beginners Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wisdom-3-strategies-for-directory-expedition/"><u>Windows Wisdom: 3 Strategies for Directory Expedition</u></a></li>
</ul></div>

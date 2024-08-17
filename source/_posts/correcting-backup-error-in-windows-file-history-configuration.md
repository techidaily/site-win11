---
title: Correcting “Backup Error” In Windows File History Configuration
date: 2024-08-15T23:52:11.346Z
updated: 2024-08-16T23:52:11.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting “Backup Error” In Windows File History Configuration
excerpt: This Article Describes Correcting “Backup Error” In Windows File History Configuration
keywords: Fix Backup Error Windows,Windows File History Troubleshoot,Resolve File History Fails,Stop Windows Restore Fail,Correcting Backup Issue WinFH,Address Windows History Errors,Mend Windows File History
thumbnail: https://thmb.techidaily.com/e85743b34dfe1708fd7baeaabbf4be530a9d0acc972c34955c94cad23467f1e0.jpg
---

## Correcting “Backup Error” In Windows File History Configuration

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a [problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to [show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.


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
<li><a href="https://fox-http.techidaily.com/new-beginning-zoom-video-calls-on-android-devices/"><u>[New] Beginning Zoom Video Calls on Android Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-how-to-record-your-desktop-screen-on-windows-for-free-3-methods-for-2024/"><u>[New] How to Record Your Desktop Screen on Windows For Free [3 Methods] for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-perfect-photos-effortless-best-10-screenshot-sticker-enhancers-for-smartphones/"><u>[Updated] In 2024, Perfect Photos, Effortless  Best 10 Screenshot-Sticker Enhancers for Smartphones</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-minimizing-motion-blur-with-obs-adjustments-for-2024/"><u>[Updated] Minimizing Motion Blur with OBS Adjustments for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-advancing-photo-viewing-in-windows-11-merge-artistic-layers-and-soundtracks/"><u>2024 Approved  Advancing Photo Viewing in Windows 11  Merge Artistic Layers and Soundtracks</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-elevate-tiktok-visuals-switch-backgrounds-with-confidence-and-precision/"><u>2024 Approved  Elevate TikTok Visuals  Switch Backgrounds with Confidence and Precision</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-remove-the-microsoft-store-app-from-windows-11/"><u>3 Ways to Remove the Microsoft Store App From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-tactics-to-turn-windows-into-a-mac-like-interface/"><u>5 Tactics to Turn Windows Into a Mac-Like Interface</u></a></li>
<li><a href="https://win11.techidaily.com/6-costly-misconceptions-about-affordable-windows-codes/"><u>6 Costly Misconceptions About Affordable Windows Codes</u></a></li>
<li><a href="https://win11.techidaily.com/7-common-concerns-against-moving-to-windows-11/"><u>7 Common Concerns Against Moving to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-10-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-windows-snap-configurations-via-powertoys/"><u>A Comprehensive Guide to Windows Snap Configurations via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-tutorial-on-windows-11-hotspot-setup-procedures/"><u>A Comprehensive Tutorial on Windows 11 Hotspot Setup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-support-tasks-map-windows-troubleshooting-tools/"><u>Accelerate Support Tasks: Map Windows Troubleshooting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-a00f429f-in-windows-camera-functionality/"><u>Addressing Error A00F429F in Windows' Camera Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alt-code-malfunctions-48-characters/"><u>Addressing Windows ALT Code Malfunctions (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies!</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-pc-a-guide-to-optimizing-windows-11-options/"><u>Adjusting Your PC: A Guide to Optimizing Windows 11 Options</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-multi-archive-handling-in-windows-os/"><u>Advanced Multi-Archive Handling in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-the-non-functional-windows-enter-key/"><u>Ameliorating the Non-Functional Windows Enter Key</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bask-in-the-best-of-microsofts-winstore-treasures/"><u>Bask in the Best of Microsoft’s WinStore Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-blue-screens-in-your-daily-computing-life/"><u>Beating Back Blue Screens in Your Daily Computing Life</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-system-uncrashing-win1011s-corrupt-bin-error/"><u>Beating the System: Uncrashing Win10/11's Corrupt Bin Error</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-nubia-z50-ultra-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Nubia Z50 Ultra Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/blending-worlds-kali-installation-guide-for-windows-users/"><u>Blending Worlds: Kali Installation Guide for Windows Users</u></a></li>
<li><a href="https://tech-hub.techidaily.com/hackers-growing-interest-in-targeting-ai-conversational-services-like-chatgpt/"><u>Hackers' Growing Interest in Targeting AI Conversational Services Like ChatGPT</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-itel-p55-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Itel P55 5G?</u></a></li>
<li><a href="https://win11.techidaily.com/1719335120399-python-package-installation/"><u>Python Package Installation:</u></a></li>
<li><a href="https://win11.techidaily.com/1719336618337-quick-fix-guide-overcome-incompatibility-in-windows-xp/"><u>Quick-Fix Guide: Overcome Incompatibility in Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/1719352483219-resurrect-computer-sounds-immediate-action-steps/"><u>Resurrect Computer Sounds – Immediate Action Steps!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/snapchat-savvy-elevating-your-photographic-style-with-app-edits-for-2024/"><u>Snapchat Savvy  Elevating Your Photographic Style with App Edits for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-pathway-to-prime-streaming-from-obs-to-social-media-for-2024/"><u>The Pathway to Prime Streaming  From OBS to Social Media for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-unleashing-your-creative-potential-the-comprehensive-guide-to-volume-automation-and-ducking-with-adobe-premiere-pro-mac-edition-for-2024/"><u>Updated Unleashing Your Creative Potential The Comprehensive Guide to Volume Automation and Ducking with Adobe Premiere Pro (Mac Edition) for 2024</u></a></li>
</ul></div>

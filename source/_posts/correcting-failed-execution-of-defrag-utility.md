---
title: Correcting Failed Execution of Defrag Utility
date: 2024-08-16T00:15:48.403Z
updated: 2024-08-17T00:15:48.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failed Execution of Defrag Utility
excerpt: This Article Describes Correcting Failed Execution of Defrag Utility
keywords: Defrag Fail Fix,Error Defrag Tool,Execute Defrag Correction,Defrag Issue Resolve,Utility Defrag Troubleshoot,Correcting Defrag Malfunction,Restart Failed Defrag Scan
thumbnail: https://thmb.techidaily.com/03b50fa097007316bd728c0f1505911c6985b5446ee8e6c9838cd48c592632a7.png
---

## Correcting Failed Execution of Defrag Utility

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see [ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try [running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. When you're in Command Prompt, type the following command and press Enter:  
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.


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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-easy-process-extracting-youtube-media-directly/"><u>[Updated] 2024 Approved  Easy Process  Extracting YouTube Media Directly</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-breakthrough-in-youtube-saving-technology/"><u>[Updated] In 2024, Breakthrough in YouTube Saving Technology</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-instant-tv-viewing-of-popular-facebook-feeds/"><u>[Updated] Instant TV Viewing of Popular Facebook Feeds</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-phones-to-fantasy-crafting-a-home-for-vr-goggles/"><u>2024 Approved  Phones to Fantasy  Crafting a Home for VR Goggles</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-comprehensive-guide-to-top-8-collaborative-video-collage-tools-android/"><u>2024 Approved  The Comprehensive Guide to Top 8 Collaborative Video Collage Tools (Android)</u></a></li>
<li><a href="https://win11.techidaily.com/add-on-troubleshooters-for-improved-software-functionality/"><u>Add-On Troubleshooters for Improved Software Functionality</u></a></li>
<li><a href="https://win-dash.techidaily.com/brother-mfc-l2740dw-windows-compatible-drivers-download-and-installation-guide/"><u>Brother MFC-L2740DW Windows Compatible Drivers: Download and Installation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-no-click-spaces-within-windows-11-interface/"><u>Combatting No-Click Spaces Within Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/concealed-commands-disguise-power-settings-in-start-screen/"><u>Concealed Commands: Disguise Power Settings in Start Screen</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-what-users-find-flawed-in-windows-11/"><u>Deciphering What Users Find Flawed in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-unravelled-enabling-windows-update/"><u>Error 2E Unravelled: Enabling Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-disabled-status-on-windows-pcs/"><u>Fixing Grammarly Disabled Status on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-path-not-found-on-pc-systems/"><u>Fixing Path Not Found on PC Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-xbox-games-access-error-in-windows-pcs/"><u>Guide to Correct Xbox Games Access Error in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-looks-like-youre-stranded-on-xbox-error/"><u>Guide to Overcoming 'Looks Like You're Stranded' On Xbox Error</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-intel-unison-power-for-effective-pc-phone-calls/"><u>Harnessing Intel Unison Power for Effective PC Phone Calls</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-google-chrome-from-creating-random-tabs/"><u>How To Prevent Google Chrome From Creating Random Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-the-aw-snap-error-in-chrome/"><u>How to Stop the Aw, Snap! Error in Chrome</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-conquering-video-design-challenges-with-filmora-tips/"><u>In 2024, Conquering Video Design Challenges with Filmora Tips</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-turn-off-unsolicited-game-suggestions-for-w11/"><u>Learn to Turn Off Unsolicited Game Suggestions for W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-windows-11-boots-a-triad-of-tips/"><u>Mastering Faster Windows 11 Boots: A Triad of Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-github-desktop-on-windows-11-a-complete-guide/"><u>Mastering GitHub Desktop on Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-and-search-features-in-windows-11-os/"><u>Mastering Highlight & Search Features in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-password-storage-windows-text-file-security-tips/"><u>Mastering Password Storage: Windows Text File Security Tips</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-computers-visual-experience-with-enhanced-vram/"><u>Optimize Your Computer's Visual Experience with Enhanced VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-makers-code-0x8007043c-issue/"><u>Overcoming Windows Media Maker's Code 0X8007043C Issue</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-forcing-printer-deletion-in-win-1011/"><u>Quick Guide: Forcing Printer Deletion in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-google-nearby-sharing-service-in-windows/"><u>Re-Establishing Google Nearby Sharing Service in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-discovery-of-software-installs-for-windows-users/"><u>Seamless Discovery of Software Installs for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-disk-differentiation-hdd-and-ssd-recognition-on-pcs/"><u>Simplifying Disk Differentiation: HDD & SSD Recognition on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-rectifying-file-history-missteps-in-windows-os/"><u>Steps for Rectifying File History Missteps in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-eliminating-restricted-admin-windows-alert/"><u>Strategies for Eliminating Restricted Admin Windows Alert</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-no-permission-on-windows-file-viewing/"><u>Strategies to Avoid 'No Permission' On Windows File Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/subnet-adjustment-for-win11-users/"><u>Subnet Adjustment for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-windows-based-counter-strike-play/"><u>Supercharge Windows-Based Counter-Strike Play</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-snap-open-apps-in-windows-11/"><u>Swiftly Snap Open Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-pc-performance-deficiencies-amidst-intel-errors/"><u>Tackling PC Performance Deficiencies Amidst Intel Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-problem-code-0x800f0922/"><u>Tackling Windows Update Problem - Code 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tango-dancing-devices-androidwindows-synchro/"><u>Tech Tango: Dancing Devices - Android/Windows Synchro</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-of-control-for-winapps-and-browsers/"><u>The Blueprint of Control for WinApps & Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-way-to-clean-clear-notes/"><u>The Obsidian Way to Clean, Clear Notes</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-to-remove-microsoft-store-from-pcs/"><u>Three Methods to Remove Microsoft Store From PCs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-y36i-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo Y36i Phone Pattern Lock</u></a></li>
<li><a href="https://win11.techidaily.com/top-quick-strategies-for-black-screen-in-wins-1011/"><u>Top Quick Strategies for Black Screen in Wins 10/11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-honor-play-7t-by-fonelab-android-recover-music/"><u>Undelete lost music from Honor Play 7T</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pc-potential-by-clearing-windows-temp-files/"><u>Unlock Your PC Potential by Clearing Windows Temp Files</u></a></li>
<li><a href="https://hardware-help.techidaily.com/upgrade-to-the-latest-nvidia-rtx-3080-ti-drivers-on-windows-download-now/"><u>Upgrade to the Latest NVIDIA RTX 3080 Ti Drivers on Windows - Download Now!</u></a></li>
</ul></div>

---
title: A Handy Guide to Resolving Windows Filesystem Problems
date: 2024-08-15T23:21:05.375Z
updated: 2024-08-16T23:21:05.375Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Handy Guide to Resolving Windows Filesystem Problems
excerpt: This Article Describes A Handy Guide to Resolving Windows Filesystem Problems
keywords: Fixing Windows FS Issues,Windows File Error Troubleshooting,Solve Windows Filesystem Woes,Unlock Windows Storage Glitches,Resolving Windows Disk Problems,Windows Filesystem Repair Guide,Steps for Windows FS Fix
thumbnail: https://thmb.techidaily.com/d168a05f3f195d26d6b5e0381b43203121c261c3de6a774edbf948a46452563c.png
---

## A Handy Guide to Resolving Windows Filesystem Problems

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on [how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to [utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://fox-links.techidaily.com/new-homemade-video-making-top-5-efficient-methods-you-must-know-for-2024/"><u>[New] Homemade Video Making  Top 5 Efficient Methods You Must Know for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-cut-to-the-chase-8-simple-youtube-thumbnail-builders/"><u>[Updated] In 2024, Cut-to-the-Chase  8 Simple YouTube Thumbnail Builders</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-the-artisans-path-to-crafting-confidential-snaps/"><u>2024 Approved  The Artisan's Path to Crafting Confidential Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-dialer-on-windows-11/"><u>Accessing Dialer on Windows 11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/budget-marvels-in-depth-analysis-of-caixuns-75-4k-android-tv/"><u>Budget Marvels: In-Depth Analysis of Caixun's 75 4K Android TV</u></a></li>
<li><a href="https://win11.techidaily.com/changing-nat-types-for-better-connection-performance-in-win1110/"><u>Changing NAT Types for Better Connection Performance in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/clear-windows-11-cache-cutting-out-the-clutter/"><u>Clear Windows 11 Cache: Cutting Out the Clutter</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-new-home-for-onedrive-folder-in-windows/"><u>Configuring New Home for OneDrive Folder in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnostics-policy-service-is-not-running-solved/"><u>Diagnostics Policy Service Is Not Running [Solved]</u></a></li>
<li><a href="https://win11.techidaily.com/digital-canvas-on-windows-desktops-tips-and-tricks/"><u>Digital Canvas on Windows Desktops: Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/disentangling-same-account-issues-on-a-device/"><u>Disentangling Same-Account Issues on a Device</u></a></li>
<li><a href="https://win11.techidaily.com/easing-frustrations-with-a-fix-to-non-working-pen-devices-in-windows/"><u>Easing Frustrations with a Fix to Non-Working Pen Devices in Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/expertise-amplified-pearsons-gsl-enhanced-with-mondly/"><u>Expertise Amplified - Pearson's GSL Enhanced with Mondly</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-redmi-note-12-4gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi Redmi Note 12 4Gwith/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-file-system-errors-in-windows-10-and-11/"><u>How to Fix File System Errors in Windows 10 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-samsung-galaxy-f15-5g-by-drfone-android/"><u>How to Show Wi-Fi Password on Samsung Galaxy F15 5G</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-windows-admin-imposed-setup-barriers/"><u>How to Tackle Windows 'Admin-Imposed' Setup Barriers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-s24-ultra-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy S24 Ultra by Phone Number | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-steps-to-clear-up-steam-errors-in-games-on-windows/"><u>Immediate Steps to Clear Up Steam Errors in Games on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-primary-screening-footage-study-and-off-the-cuff-selections/"><u>In 2024, Primary Screening Footage Study and Off-the-Cuff Selections</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-smooth-sailing-through-sequences-with-kinemaster/"><u>In 2024, Smooth Sailing Through Sequences with Kinemaster</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mac-audio-tools-for-effective-classroom-capture/"><u>Mac Audio Tools for Effective Classroom Capture</u></a></li>
<li><a href="https://win11.techidaily.com/make-the-best-out-of-what-you-have-even-without-11/"><u>Make the Best Out of What You Have, Even Without 11</u></a></li>
<li><a href="https://win11.techidaily.com/making-older-computers-more-comfortable-for-seniors/"><u>Making Older Computers More Comfortable for Seniors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-low-resource-utilization-wlanextexe/"><u>Mastering Low Resource Utilization: Wlanext.EXE</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-a-guide-to-fixing-windows-11-issues/"><u>Mastering Troubleshooting: A Guide to Fixing Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resurrect-inactive-windows-email-rule-configurations/"><u>Methods to Resurrect Inactive Windows Email Rule Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-window-11-wallpaper-settings-for-individual-monitors/"><u>Navigating Window 11 Wallpaper Settings for Individual Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-windows-error-0xc0000001/"><u>Overcoming the Challenge of Windows Error 0XC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-playstation-services-on-pc-and-laptops/"><u>Quick Fixes for PlayStation Services on PC & Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/routine-task-for-eliminating-steam-dns-cache-on-pc/"><u>Routine Task for Eliminating Steam DNS Cache on PC</u></a></li>
<li><a href="https://win11.techidaily.com/shining-up-dull-desktops-with-vibrant-colors/"><u>Shining Up Dull Desktops with Vibrant Colors</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-unresponsive-windows-media-files/"><u>Steps to Rectify Unresponsive Windows Media Files</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-increase-windows-disk-size-securely/"><u>Strategies to Increase Windows Disk Size Securely</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-iomap64-bsod-errors-in-windows-108/"><u>Strategies to Resolve IOMap64 BSOD Errors in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-file-sharing-software-on-windows-os/"><u>The Best File-Sharing Software on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-tracking-disk-space-usage-in-windows-pcs/"><u>The Ultimate Guide to Tracking Disk Space Usage in Windows PCs</u></a></li>
</ul></div>

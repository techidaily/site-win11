---
title: Reversing Windows 11 FS Errors Swiftly
date: 2024-09-11T09:47:14.332Z
updated: 2024-09-12T09:47:14.332Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing Windows 11 FS Errors Swiftly
excerpt: This Article Describes Reversing Windows 11 FS Errors Swiftly
keywords: Win11 FS Fix,Reverse OS Error,Quick FS Repair,FS Recovery Win,Error Resolution Win,Speedup OS Fixing,Swift Win FS Cure
thumbnail: https://thmb.techidaily.com/b034e397cf58f21c63fc5dd80cb149d6528213f9e99cf7ed2375f403fbf9fc3e.jpg
---

## Reversing Windows 11 FS Errors Swiftly

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123482/16836" target="_top" id="2123482">
  <img src="//a.impactradius-go.com/display-ad/16836-2123482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123482/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123470/16836" target="_top" id="2123470">
  <img src="//a.impactradius-go.com/display-ad/16836-2123470" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123470/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-cut-to-quality-perfecting-videos-with-enhancer-22/"><u>[New] 2024 Approved Cut to Quality Perfecting Videos with Enhancer 2.2</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-inspiring-vistas-top-20-scenic-shots-for-social-media-success-for-2024/"><u>[New] Inspiring Vistas Top 20 Scenic Shots for Social Media Success for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-secrets-of-crafting-an-exclusive-identifier-on-tiktok/"><u>[New] Secrets of Crafting an Exclusive Identifier on TikTok</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-conceptualization-to-production-writing-engaging-documentary-stories/"><u>[Updated] From Conceptualization to Production Writing Engaging Documentary Stories</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-from-raw-footage-crafting-engaging-videos-on-windows-11/"><u>2024 Approved From Raw Footage Crafting Engaging Videos on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfectly-preserve-and-profitably-play-your-phones-gifs/"><u>2024 Approved Perfectly Preserve and Profitably Play Your Phone's GIFs</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-polishing-your-figma-creations-expert-backdrop-extraction/"><u>2024 Approved Polishing Your Figma Creations Expert Backdrop Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-overcoming-usb-not-recognized-error-in-virtualbox/"><u>Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-microsoft-store-issue-x80073d26-on-win11/"><u>Correcting Microsoft Store Issue X:80073d26 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-11-directory-exposure/"><u>Customize Your Window's 11 Directory Exposure</u></a></li>
<li><a href="https://win11.techidaily.com/decisive-action-plan-for-banishing-flashing-screens-on-windows/"><u>Decisive Action Plan for Banishing Flashing Screens on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dial-down-dysfunction-restore-your-pcs-essential-esc-keys/"><u>Dial Down Dysfunction: Restore Your PC's Essential Esc Keys</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-fixes-for-call-of-duty-modern-warfare-3-sudden-crash-issues/"><u>Effective Fixes for Call of Duty Modern Warfare 3 Sudden Crash Issues</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-always-on-top-notations-on-windows/"><u>Ensuring Always On-Top Notations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/excellence-in-organizing-top-windows-to-dos-revealed/"><u>Excellence in Organizing: Top Windows To-Dos Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-based-valorant-audio-glitches/"><u>Fixing Windows-Based Valorant Audio Glitches</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-the-counterfeit-chatgpt-chrome-app-could-be-hijacking-your-facebook-login-details/"><u>How the Counterfeit ChatGPT Chrome App Could Be Hijacking Your Facebook Login Details</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1723808107535-identify-and-retrieve-your-internet-ip-address-for-free-today/"><u>Identify and Retrieve Your Internet IP Address for Free Today</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-vivo-x-fold-2-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Vivo X Fold 2 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-realme-12plus-5g-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Realme 12+ 5G Through Google Earth?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-tecno-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Tecno Bootloader Easily</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-efficiency-in-it-support-with-troubleshooters-shortcut-guide/"><u>Maximize Efficiency in IT Support with Troubleshooters Shortcut Guide</u></a></li>
<li><a href="https://win11.techidaily.com/missed-sd-card-display-how-to-locate-it-in-explorer/"><u>Missed SD Card Display: How to Locate It in Explorer</u></a></li>
<li><a href="https://fox-that.techidaily.com/optimize-your-safari-browser-4-effective-ways-for-quicker-iphone-surfing/"><u>Optimize Your Safari Browser - 4 Effective Ways for Quicker iPhone Surfing</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-disabled-cpu-cooling-mechanism-in-os/"><u>Reactivating Disabled CPU Cooling Mechanism in OS</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-no-saving-problem-with-photoapp/"><u>Remedy for 'No Saving' Problem with PhotoApp</u></a></li>
<li><a href="https://win11.techidaily.com/speak-type-win-navigating-text-creation-using-windows-whisper/"><u>Speak, Type, Win: Navigating Text Creation Using Windows Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/synchronizing-qbittorrent-settings-between-multiple-windows-systems/"><u>Synchronizing qBittorrent Settings Between Multiple Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-utorrent-download-interruptions-on-pcs/"><u>Tackling uTorrent Download Interruptions on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-windows-pin-modification/"><u>The Ultimate Guide to Windows PIN Modification</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-trim-windows-overscan-for-flawless-screen-match/"><u>Tips to Trim Windows Overscan for Flawless Screen Match</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-upgrade-top-5-tools-to-supercharge-your-pc/"><u>Turbo Upgrade: Top 5 Tools to Supercharge Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-should-prefer-windows-11-over-macos/"><u>Why You Should Prefer Windows 11 over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-disk-management-a-comprehensive-walkthrough/"><u>Win 10/11 Disk Management: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-inside-the-settings-experience/"><u>Windows 11: Inside the Settings Experience</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-phaseout-strategizing-for-future-android-support/"><u>Windows Subsystem Phaseout: Strategizing for Future Android Support</u></a></li>
</ul></div>


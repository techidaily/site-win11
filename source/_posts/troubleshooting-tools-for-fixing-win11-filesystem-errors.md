---
title: Troubleshooting Tools for Fixing Win11 Filesystem Errors
date: 2024-12-06T03:35:01.285Z
updated: 2024-12-07T04:29:08.766Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Tools for Fixing Win11 Filesystem Errors
excerpt: This Article Describes Troubleshooting Tools for Fixing Win11 Filesystem Errors
keywords: Win11 FS Error Solver,Win11 File System Repair,Win11 Recovery Toolkit,Fix Win11 Filesystem Issues,Win11 Data Integrity Check,Restoring Win11 System Files,Troubleshoot Win11 Disk Errors
thumbnail: https://thmb.techidaily.com/d7456d8b7faa111d0a43957b4a5dc6a2bd7fa022e346daf01ae591cee8bd80cf.jpg
---

## Troubleshooting Tools for Fixing Win11 Filesystem Errors

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

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
<li><a href="https://fox-access.techidaily.com/updated-enhance-real-time-periscope-broadcasting-for-2024/"><u>[Updated] Enhance Real-Time Periscope Broadcasting for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-free-windows-and-mac-screen-saver-software-with-full-control/"><u>[Updated] Free Windows & Mac Screen Saver Software with Full Control</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-a-trifecta-guide-for-extracting-youtube-subtitled-content/"><u>[Updated] In 2024, A Trifecta Guide for Extracting YouTube Subtitled Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-make-a-cool-youtube-video-intro-in-imovie-step-by-step/"><u>[Updated] In 2024, How to Make a Cool YouTube Video Intro in iMovie (Step-by-Step)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-off-switch-for-instagrams-igtv/"><u>[Updated] Off Switch for Instagram's IGTV</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-guide-to-iphone-composition-choosing-right-angles/"><u>[Updated] The Ultimate Guide to iPhone Composition Choosing Right Angles</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-samsung-galaxy-a54-5g-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Samsung Galaxy A54 5G? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-0x80040610-a-tactical-approach-to-outlook-repair/"><u>Eliminating Error 0X80040610: A Tactical Approach to Outlook Repair</u></a></li>
<li><a href="https://extra-information.techidaily.com/exploring-new-realms-of-thought-30plus-vr-metaphysical-messages/"><u>Exploring New Realms of Thought 30+ VR Metaphysical Messages</u></a></li>
<li><a href="https://win11.techidaily.com/hack-the-store-glitch-defeating-error-code-x80072f30-on-pc/"><u>Hack the Store Glitch: Defeating Error Code X80072F30 on PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-realme-gt-3-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Realme GT 3 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-c0000005-errors-in-windows/"><u>Mastering the Art of Fixing C0000005 Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-eliminating-minecraft-win-error-1/"><u>Quick Remedies for Eliminating Minecraft Win Error: 1</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-reset-softwaredistribution-on-windows-11/"><u>Simplified Steps to Reset SoftwareDistribution on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unique-windows-11-workarounds-for-inaccessible-folder-names/"><u>Unique Windows 11 Workarounds for Inaccessible Folder Names</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-threats-exposed-manual-checks-for-windows-pc-security/"><u>Unseen Threats Exposed: Manual Checks for Windows PC Security</u></a></li>
</ul></div>


---
title: Mastering File System Recovery in Windows 10 & 11
date: 2024-08-16T00:45:44.460Z
updated: 2024-08-17T00:45:44.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering File System Recovery in Windows 10 & 11
excerpt: This Article Describes Mastering File System Recovery in Windows 10 & 11
keywords: WinFileRecoveryBasics,1011OSFileSystem,DataRestoreW1011,RecoverDiskWin10,WindowsDataRepair,OSDataBackupSolutions,FileErrorWindows1011
thumbnail: https://thmb.techidaily.com/da3a565149456b725f254b5d80c3b1f1c06d74a5fc993d32dbb395957f6fba49.jpg
---

## Mastering File System Recovery in Windows 10 & 11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-resources.techidaily.com/new-boost-your-bank-account-quickly-with-these-13-ways-to-profit-on-reddit/"><u>[New] Boost Your Bank Account Quickly With These 13 Ways to Profit on Reddit</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-comprehensive-3d-lut-development-course/"><u>[New] Comprehensive 3D LUT Development Course</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-expert-tips-on-ipad-screen-casts-for-2024/"><u>[New] Expert Tips on iPad Screen Casts for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-snapedit-essentials-for-beginners-a-visual-journey/"><u>[New] Snapedit Essentials for Beginners  A Visual Journey</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-secret-to-capturing-seamless-google-classesmeets-for-2024/"><u>[New] The Secret to Capturing Seamless Google Classes/Meets for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-merging-worlds-youtube-in-instagram-narrative-art/"><u>[Updated] 2024 Approved  Merging Worlds  YouTube in Instagram Narrative Art</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-pixelpilot-screen-recorder-critique-plus-backups/"><u>[Updated] 2024 Approved  PixelPilot Screen Recorder Critique + Backups</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-direct-conversion-convert-and-upload-mp3-songs-on-youtube/"><u>[Updated] Direct Conversion  Convert & Upload MP3 Songs on YouTube</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-enhance-visual-magnification-without-quality-loss/"><u>[Updated] Enhance Visual Magnification without Quality Loss</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-influential-interaction-incentives-for-video-makers/"><u>[Updated] Influential Interaction Incentives for Video Makers</u></a></li>
<li><a href="https://win11.techidaily.com/13-enhanced-functions-for-windows-11-in-the-newest-update/"><u>13 Enhanced Functions for Windows 11 in the Newest Update</u></a></li>
<li><a href="https://win11.techidaily.com/5-fun-tricks-you-can-do-in-command-prompt/"><u>5 Fun Tricks You Can Do in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-to-rethink-your-email-client-the-modern-outlook/"><u>9 Reasons to Rethink Your Email Client - The Modern Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-celestial-mastery-windows-11s-divine-control/"><u>A Journey Into Celestial Mastery: Windows 11'S Divine Control</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-rectify-a-wrongly-setup-temp-folder-in-win11/"><u>A Step-by-Step Guide to Rectify a Wrongly Setup Temp Folder in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-tri-method-approach-to-understanding-and-applying-windows-policies/"><u>A Tri-Method Approach to Understanding and Applying Windows Policies</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-success-reinstalling-microsofts-pc-manager-in-winxp/"><u>Achieve Success: Reinstalling Microsoft's PC Manager in WinXP</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-synchronized-data-across-your-multiple-windows-desktops-with-aoemi/"><u>Achieve Synchronized Data Across Your Multiple Windows Desktops With AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/ad-free-experience-just-for-you-with-win-11/"><u>Ad-Free Experience, Just for You with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/address-windows-missing-camera-mystery-in-device-manager/"><u>Address Windows' Missing Camera Mystery in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-downloads-in-windows-environments/"><u>Addressing Failed Downloads in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-fault-finders-in-windows/"><u>Addressing Inoperative Fault Finders in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clock-display-window-10-and-11-guide/"><u>Adjusting Clock Display: Window 10 & 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-removing-restrictions-in-windows/"><u>Advanced Techniques: Removing Restrictions in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>All You Need To Know About Mega Greninja For Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-new-windows-editions-which-fits-you-best-home-or-pro/"><u>Assessing New Windows Editions: Which Fits You Best, Home or Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/automating-windows-11-app-installation-a-guide-to-winstall/"><u>Automating Windows 11 App Installation: A Guide to Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disk-read-failures-on-your-pc/"><u>Avoiding Disk Read Failures on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/backup-basics-protecting-your-digital-adventures-in-epic-games/"><u>Backup Basics: Protecting Your Digital Adventures in Epic Games</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-windows-journey-with-a-voice-guide/"><u>Begin Your Windows Journey with a Voice Guide</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breach-are-windows-fingerprint-scanners-safe/"><u>Biometric Breach: Are Windows Fingerprint Scanners Safe?</u></a></li>
<li><a href="https://win11.techidaily.com/1719289257399-black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime!</u></a></li>
<li><a href="https://win11.techidaily.com/boost-keyboard-efficiency-top-strategies-for-speed-on-windows-devices/"><u>Boost Keyboard Efficiency: Top Strategies for Speed on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/boost-playnites-capabilities-with-windows-compatible-emulators/"><u>Boost Playnite's Capabilities with Windows-Compatible Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-using-keyboard-shortcuts-for-windows-taskbar-management/"><u>Boosting Efficiency: Using Keyboard Shortcuts for Windows Taskbar Management</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-email-readability-pinning-gmail-bar-on-pc/"><u>Boosting Email Readability: Pinning Gmail Bar on PC</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-fixing-steam-problems-on-windows-11-os/"><u>Breaking Down Barriers: Fixing Steam Problems on Windows 11 OS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-walkthrough-to-update-your-epson-xp-400-driver-software-step-by-step/"><u>Easy Walkthrough to Update Your Epson XP 400 Driver Software: Step by Step</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/firecapture-pro-for-ff-for-2024/"><u>FireCapture Pro for FF for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/free-money-tips-for-reddit-novices-13-best-ways-for-2024/"><u>Free Money Tips for Reddit Novices (13 Best Ways!) For 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-nokia-c110-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Nokia C110?</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-or-malfunctioning-your-hardware-drivers-with-windows-device-manager-in-windows-10-and-7-by-drivereasy-guide/"><u>Identify missing or malfunctioning your hardware drivers with Windows Device Manager in Windows 10 & 7</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-techniques-for-smoothly-fading-audio-within-lumafusion/"><u>In 2024, Techniques for Smoothly Fading Audio Within Lumafusion</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-transforming-tweets-into-audio-based-archives/"><u>In 2024, Transforming Tweets Into Audio-Based Archives</u></a></li>
<li><a href="https://win11.techidaily.com/1719319611800-overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing.</u></a></li>
<li><a href="https://facebook.techidaily.com/patterns-in-internet-account-compromises/"><u>Patterns in Internet Account Compromises</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-realme-gt-5-pro-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Realme GT 5 Pro and Browser | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolve-search-is-unavailable-error-on-windows-10/"><u>Resolve 'Search Is Unavailable' Error on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719347016533-unlock-your-computers-print-command-solutions-for-faulty-wwinplusp-operations/"><u>Unlock Your Computer's Print Command: Solutions for Faulty WWin+P Operations.</u></a></li>
</ul></div>

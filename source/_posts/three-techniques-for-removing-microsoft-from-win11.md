---
title: Three Techniques for Removing Microsoft From Win11
date: 2024-10-24T08:19:54.704Z
updated: 2024-10-26T18:11:32.241Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Techniques for Removing Microsoft From Win11
excerpt: This Article Describes Three Techniques for Removing Microsoft From Win11
keywords: Removing MSFT in Windows 11,Win11 Cleanup,Remove Microsoft OS,Win11 Reset Guide,Expert Win11 De-Microsoft,Uninstalling MSFT Win11,Free Win11 From MSFT
thumbnail: https://thmb.techidaily.com/b8a6614e5e46e83c73c99e937a620940173ecb3e527c0b15c86864ff7f2cf4ce.png
---

## Three Techniques for Removing Microsoft From Win11

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.

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
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-cam-clash-sj6-legend-versus-yi-4k-visionary/"><u>[Updated] 2024 Approved Cam Clash SJ6 Legend Versus Yi 4K Visionary</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-the-metaverse-vs-omniverse-showdown-a-comprehensive-overview/"><u>[Updated] The Metaverse Vs. Omniverse Showdown A Comprehensive Overview</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-editing-images-erasing-unwanted-backdrops/"><u>2024 Approved Editing Images Erasing Unwanted Backdrops</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-tips-troubleshooting-a-non-functional-mic-on-windows-10/"><u>Fixes & Tips: Troubleshooting a Non-Functional Mic on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-event-viewer-errors-in-windows-11/"><u>Fixing Windows Event Viewer Errors in Windows 11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-3-ways-to-track-apple-iphone-7-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Ways to Track Apple iPhone 7 Plus without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-on-iphone-se-2020-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud on iPhone SE (2020) Safe and Legal</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-tasks-at-the-forefront-a-guide-to-sticky-notes-elevation-on-win-11/"><u>Keep Your Tasks at the Forefront: A Guide to Sticky Notes Elevation on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/next-gen-notion-how-windows-11-differs-from-its-predecessor/"><u>Next-Gen Notion: How Windows 11 Differs From Its Predecessor</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-oppo-reno-10-5g-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Oppo Reno 10 5G Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ight-websites-offering-youtube-branding-collaborations/"><u>Spotlight Websites Offering YouTube Branding Collaborations</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-16-avi-video-cutters-trimcut-avi-videos-windows-mac-android-for-2024/"><u>Top 16 AVI Video Cutters Trim/Cut AVI Videos Windows, MAC, Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-cab-its-purpose-and-installation-guide/"><u>Unveiling Windows CAB: Its Purpose & Installation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-resolving-no-more-files-message/"><u>Win 10/11: Resolving 'No More Files' Message</u></a></li>
</ul></div>


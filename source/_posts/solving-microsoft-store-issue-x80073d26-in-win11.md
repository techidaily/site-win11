---
title: "Solving Microsoft Store Issue X:80073d26 in Win11"
date: 2024-10-02T00:36:43.303Z
updated: 2024-10-03T17:55:22.610Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solving Microsoft Store Issue X:80073d26 in Win11"
excerpt: "This Article Describes Solving Microsoft Store Issue X:80073d26 in Win11"
keywords: Win11 Error Fix,MSStore Troubleshoot,Win11 Update Solution,Solve Store XError,Windows Store Issue,XP80073D26 Remedy,Win11 Store Hack
thumbnail: https://thmb.techidaily.com/9dc3437ed1a0c4e12ecf0fe73c74b8d72b51654a1b0d3ea6af6735c5a10c75f4.jpg
---

## Solving Microsoft Store Issue X:80073d26 in Win11

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.

6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925570/19272" target="_top" id="1925570">
  <img src="//a.impactradius-go.com/display-ad/19272-1925570" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925570/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagram-savvy-top-5-methods-for-building-a-thriving-influencer-profile/"><u>[New] 2024 Approved Instagram Savvy Top 5 Methods for Building a Thriving Influencer Profile</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ow-to-extract-youtube-content-easily-for-2024/"><u>[New] How to Extract YouTube Content Easily for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-video-size-adjustments-imovies-mysterious-trimming/"><u>[New] In 2024, Video Size Adjustments IMovie's Mysterious Trimming</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-discover-your-favorite-6-premier-youtube-short-downloaders/"><u>[Updated] 2024 Approved Discover Your Favorite 6 Premier YouTube Short Downloaders</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-in-depth-insights-on-creating-captivating-instagram-stories/"><u>[Updated] 2024 Approved In-Depth Insights on Creating Captivating Instagram Stories</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-copilot-key-in-windows-11-enhance-your-experience/"><u>Decoding Copilot Key in Windows 11 - Enhance Your Experience</u></a></li>
<li><a href="https://win11.techidaily.com/enable-missing-sd-card-view-on-file-explorer-platform/"><u>Enable Missing SD Card View on File Explorer Platform</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-in-depth-investigating-windows-memory-integrity-breach/"><u>Ftdibus.sys in Depth: Investigating Windows Memory Integrity Breach</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-nubia-z50-ultra-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Nubia Z50 Ultra</u></a></li>
<li><a href="https://win11.techidaily.com/kickstart-windows-11-help-and-support-mechanism/"><u>Kickstart Windows 11 Help & Support Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-explorer-top-errors-and-how-to-evade-them/"><u>Mastering File Explorer: Top Errors & How to Evade Them</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-game-potential-with-these-pro-gamers-top-tips-for-win-11/"><u>Maximize Game Potential with These Pro-Gamers' Top Tips for Win 11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mending-mp4-audio-sync/"><u>Mending MP4 Audio Sync</u></a></li>
<li><a href="https://screen-recording.techidaily.com/optimizing-your-workflow-with-bandicams-screen-recorder-features-for-2024/"><u>Optimizing Your Workflow with Bandicam’s Screen Recorder Features for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/precision-tactics-for-perfect-window-updates/"><u>Precision Tactics for Perfect Window Updates</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/snag-your-dream-ipad-at-unmatched-deals-right-now/"><u>Snag Your Dream iPad at Unmatched Deals Right Now</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-geforce-nows-error-code-0xc0f1103f-in-windows/"><u>Steps to Fix GeForce Now's Error Code 0Xc0f1103f in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-error-e8024002e/"><u>Steps to Overcome Windows Error E:8024002E</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-6-ways-to-transfer-text-messages-from-samsung-galaxy-m14-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 6 Ways to Transfer Text Messages from Samsung Galaxy M14 5G to Other Android Devices | Dr.fone</u></a></li>
</ul></div>


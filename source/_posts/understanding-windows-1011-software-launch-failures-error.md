---
title: Understanding Windows 10/11 Software Launch Failures (Error)
date: 2024-10-15T21:04:10.393Z
updated: 2024-10-21T04:13:35.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding Windows 10/11 Software Launch Failures (Error)
excerpt: This Article Describes Understanding Windows 10/11 Software Launch Failures (Error)
keywords: Win10LaunchFailures,Win11ErrorSys,OSUpdateIssues,UpdateFailureWin,LaunchErrorWin10,SystemUpdateFail,WindowsSoftwareFail
thumbnail: https://thmb.techidaily.com/bc6e0c08f36b012f885710643ac64bca838b2cd03d9601b077f3603bbf1a3a0e.jpg
---

## Understanding Windows 10/11 Software Launch Failures (Error)

 Error 0xc000003e is among the more widely reported startup issues for Windows software packages. That error displays this message when users select to run recently installed software, “The application was unable to start correctly (0xc000003e).” As a result, users can’t open and utilize programs for which that error message pops up.

 The 0xc000003e error has been mostly reported for the Zoom and Discord apps, but it can arise for other software. It’s an issue that can occur on Windows 11, 10, and 8 platforms. Here are some probable resolutions for fixing the 0xc000003e error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set the Affected Software to Run With Admin Rights

 Firstly, try opening affected software with administrative rights. Some apps the 0xc000003e error occurs for might need more elevated permissions to operate. You can set the software to run as an administrator like this:

1. Open Windows Explorer and open the installation directly that includes the affected software.
2. Right-click the EXE (application) file for the software error 0xc000003e occurs and select**Properties** .
3. Then click**Compatibility** to access the settings below.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/compatibility-tab.jpg)
4. Select**Run this program as administrator** to set the program to run with elevated permissions.
5. Click**Apply** to save the selected options.
6. Press the**OK** button to exit the window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the Compatibility Troubleshooter

 Error 0xc000003e can sometimes occur because of software compatibility issues. Windows has a Compatibility Troubleshooter that applies recommended compatibility settings for programs, which might help some users fix the 0xc000003e error. This is how you run that compatibility troubleshooter in Windows:

1. First, open the**Compatibility** tab for an affected program as instructed in steps one to three of this guide’s first potential resolution.
2. Click the**Run compatibility troubleshooter** button.
3. Select the**Try recommended settings** option.  
![The Try recommended settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/try-recommended-settings-option.jpg)
4. Press the**Test the program** button to see if the software works with recommended settings.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Test the program button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/test-the-program-button.jpg)
5. Select**Next** on the Program Compatibility Troubleshooter window.
6. Click**Yes, save these settings** if the**Test Program** option opened the software.  
![The Yes, save these settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/yes-option.jpg)
7. Close out of the troubleshooter, and restart your PC.

## 3\. Repair System Files

 System file corruption is one of the more regular causes of software startup errors in Windows. It’s recommended to run both Deployment Image Servicing and Management and System File Checker scans for repairing system files. A DISM scan can repair image component store corruption. These are the steps for running those scans in the Command Prompt:

1. Click the Windows taskbar’s search box or button (magnifying glass icon).
2. Type the search phrase**cmd** inside the text box.
3. Click**Command Prompt** with your mouse’s right button to select a**Run as administrator** option (see[how to run the Command Prompt as administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for more methods).
4. Then input this Prompt command and press**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Enter and execute the following SFC command:  
`sfc /scannow`  
![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-sfc-command.jpg)
6. Wait for the scan to reach a 100 percent mark and show a Windows Resource Protection outcome message.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Run a Check Disk Scan

 You might need to fix error 0xc000003e because of a drive issue. There could be bad disk sectors on your PC’s hard drive that store data for affected software packages. Running a Check Disk (Chkdsk) scan could resolve such an issue. You can run such as scan with Windows’ Chkdsk utility as follows:

1. Bring up Command Prompt with administrative rights, as covered in resolution three.
2. Type in and execute this Chkdsk command:  
`chkdsk c: /f /r`
3. Press**Y** and**Enter** when prompted to schedule the scan for a restart.  
![A Chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/chkdsk-scan.jpg)
4. Next, select to restart Windows 11 or 10\. The Chkdsk utility will start its scanning after the restart.

## 5\. Run an Antivirus Scan

 Malware is another possible cause for the error 0xc000003e. So, it’s recommended users manually run an antivirus scan in Windows. This is how you can run an antivirus scan with the built-in Windows Security utility:

1. Open Windows Security by double-clicking the system tray (shield) icon for that app.
2. Select the**Virus & threat protection** tab.  
![The Home tab in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-virus-threat-protection-tab.jpg)
3. Click**Scan options** to view all settings for scanning.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-scan-options-link.jpg)
4. Select the radio button for the**Full scan** option.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/full-scan-option.jpg)
5. Click**Scan now** to start the antivirus scanning.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068433/7443" target="_top" id="2068433">
  <img src="//a.impactradius-go.com/display-ad/7443-2068433" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068433/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Temporarily Turn Off Antivirus Protection

 It’s not uncommon for some third-party antivirus software to sound false positive alarms for legitimate software processes. Such incorrect detection can generate all kinds of startup errors for flagged programs. If you have installed a third-party antivirus utility, turn its shield off and then try launching any software for which error 0xc000003e occurs.

 How exactly you disable third-party antivirus utilities varies between apps. However, you can usually select to turn off antivirus tools from their context menus. Right-click a system tray icon for your antivirus package to see if its context menu includes an option for disabling its shield. If it does, select to turn off the shield for an hour or so.

## 7\. Reinstall the Program Affected With Error 0xc000003e

 The 0xc000003e error can also arise because of corrupted software installations. You can fix a corrupted software installation by reinstalling the app. Reinstalling will also ensure you have the latest app version, which can address compatibility issues.

 Uninstall the affected app with one of the methods in our guide on[how to uninstall software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . The Control Panel’s**Program and Features** applet or**Apps & Features** within Settings will be sufficient for uninstalling most software.

 When you’ve uninstalled the software, download its latest version from the publisher’s website. Then you can reinstall the program by opening the downloaded setup wizard.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/programs-and-features-applet.jpg)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943648/22993" target="_top" id="1943648">
  <img src="//a.impactradius-go.com/display-ad/22993-1943648" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Roll Back Windows With the System Restore Tool

 If you have System Restore enabled on your PC, that utility may provide a potential fix for 0xc000003e. System Restore enables you to roll Windows back to saved restoration points, which can fix corrupted system files. Selecting a restore point that predates the 0xc000003e error on your PC could fix the issue.

 Our guide on[how to create restore points on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) includes full instructions about how to roll back Windows with System Restore. Note that any software you installed after a selected restore point will not be available after rolling back Windows. You’ll need to reinstall the software packages removed for a chosen restoration point.

![The System Restore point tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-system-restore-point.jpg)

## Get Error 0xc000003e Sorted on Your PC

 So, that’s how you can get the 0xc000003e error sorted out in Windows 11 and 10\. We don’t promise those possible solutions will work for everybody. However, they’re some of the most likely ways to fix error 0xc000003e. Beyond those resolutions, clean booting and updating Windows might also help some users resolve error 0xc000003e.

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
<li><a href="https://fox-info.techidaily.com/new-in-2024-embellish-slides-with-sonic-elements/"><u>[New] In 2024, Embellish Slides with Sonic Elements</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-loom-downloader-how-to-loom-screen-record/"><u>[Updated] 2024 Approved Loom Downloader - How to Loom Screen Record</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-streaming-sounds-into-your-social-story-arcs/"><u>[Updated] Streaming Sounds Into Your Social Story Arcs</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-dive-into-windows-10-new-apps-and-games-galore/"><u>2024 Approved Dive Into Windows 10 - New Apps & Games Galore</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-ultimate-sound-design-editing-your-podcasts-in-garageband/"><u>2024 Approved The Ultimate Sound Design Editing Your Podcasts in GarageBand</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-blank-display-of-startup-items/"><u>Eradicating Blank Display of Startup Items</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-onedrive-error-def5-woes/"><u>Navigating Through Windows 11'S Onedrive Error DEF5 Woes</u></a></li>
<li><a href="https://win11.techidaily.com/outsmart-windows-delete-temp-files-without-fuss/"><u>Outsmart Windows: Delete Temp Files Without Fuss</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/repair-corrupted-mp4-videos-without-cost-a-comprehensive-guide-for-windows-and-macos-users/"><u>Repair Corrupted MP4 Videos Without Cost: A Comprehensive Guide for Windows and macOS Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-skyrocketing-your-workflow-with-windows-apps/"><u>The Ultimate Guide to Skyrocketing Your Workflow with Windows Apps</u></a></li>
<li><a href="https://techidaily.com/will-galaxy-a25-5g-play-avchd-mts-files-by-aiseesoft-video-converter-play-mts-on-android/"><u>Will Galaxy A25 5G play AVCHD mts files?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-energy-requirement-monitoring-machine-might/"><u>Windows Energy Requirement: Monitoring Machine Might</u></a></li>
</ul></div>


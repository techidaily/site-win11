---
title: Navigating and Fixing Windows 10/11 Filesystem Issues
date: 2024-09-05T08:26:25.164Z
updated: 2024-09-06T08:26:25.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating and Fixing Windows 10/11 Filesystem Issues
excerpt: This Article Describes Navigating and Fixing Windows 10/11 Filesystem Issues
keywords: Win10FsTroubleshooting,Win11FilesystemRepair,Win10FileSystemIssues,FixWin10FSErrors,WindowsFilesystemDiagnostics,ResolveWindowsFSProblems,CorruptWinFilesCleanup
thumbnail: https://thmb.techidaily.com/68fb059a648e909d234d3bab20298ad1bdfcbd57c7ecdd3b24dbb573f2037e37.jpg
---

## Navigating and Fixing Windows 10/11 Filesystem Issues

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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118321/7443" target="_top" id="2118321">
  <img src="//a.impactradius-go.com/display-ad/7443-2118321" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118321/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-first-time-filmmaker-guide-setting-up-logitech-cam/"><u>[New] 2024 Approved  First-Time Filmmaker Guide  Setting up Logitech Cam</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-ending-automatic-video-captures-in-qt-player/"><u>[New] In 2024, Ending Automatic Video Captures in QT Player</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-leveraging-audacity-for-unparalleled-professional-recording/"><u>[New] Leveraging Audacity for Unparalleled Professional Recording</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/rofitability-probe-dailymovement-versus-youtubes-financial-edge-for-2024/"><u>[New] Profitability Probe  DailyMovement Versus YouTube's Financial Edge for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/augmented-reality-and-vr-navigating-2023s-content-on-android-for-2024/"><u>Augmented Reality & VR  Navigating 2023'S Content on Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-code-0xa00f4289-webcam-glitches-on-win1011/"><u>Correcting Code 0xA00F4289: Webcam Glitches on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-enhancing-non-working-windows-batch-files/"><u>Deciphering and Enhancing Non-Working Windows Batch Files</u></a></li>
<li><a href="https://win11.techidaily.com/does-your-system-qualify-for-next-gen-windows-11/"><u>Does Your System Qualify for Next-Gen Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-disk-capacity-in-windows-7-best-no-cost-techniques/"><u>Elevate Disk Capacity in Windows - 7 Best No-Cost Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-rectify-missing-windows-component/"><u>Essential Steps to Rectify Missing Windows Component</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-31-for-your-pcs-internet-connection/"><u>Fixing Error Code 31 for Your PC's Internet Connection</u></a></li>
<li><a href="https://win11.techidaily.com/granting-admin-access-to-win11s-task-manager/"><u>Granting Admin Access to Win11's Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-users-to-restore-window-11-search-functions/"><u>Guiding Users to Restore Window 11 Search Functions</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-the-admin-access-passway/"><u>Guiding You Through the Admin Access Passway</u></a></li>
<li><a href="https://win11.techidaily.com/hacking-the-lock-screen-windows-11-edition/"><u>Hacking the Lock Screen: Windows 11 Edition</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-htc-u23-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On HTC U23 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-erroneous-cpu-usage-displayed-by-windows-pc/"><u>How to Rectify Erroneous CPU Usage Displayed by Windows PC</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-lenovo-thinkphone-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Lenovo ThinkPhone to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-rca-video-doorbell-an-efficient-home-security-solution/"><u>In-Depth Analysis of RCA Video Doorbell: An Efficient Home Security Solution</u></a></li>
<li><a href="https://win11.techidaily.com/intuitive-setup-techniques-for-desktop-icons-in-windows-11/"><u>Intuitive Setup Techniques for Desktop Icons in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-tech-legacy-for-windows-11-22h2-compatibility/"><u>Jumpstart Tech Legacy for Windows 11 22H2 Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winsminecrafts-lan-play-functionality/"><u>Mastering WinsMinecraft's LAN Play Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-free-powerhouse-utilities-guide/"><u>Maximizing Windows 11: Free Powerhouse Utilities Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mending-display-problem-w11-error-code-x0001/"><u>Mending Display Problem: W11 Error Code X0001</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-deletable-keys-on-microsoft-platforms/"><u>Repairing Non-Deletable Keys on Microsoft Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-explorer-classics-effortlessly/"><u>Restoring Windows Explorer Classics Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/risk-averse-approach-foregoing-bots-for-win-11-authentication/"><u>Risk-Averse Approach: Foregoing Bots for Win 11 Authentication</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-ideas-on-screens-essential-notes-apps-for-windows-users/"><u>Sticky Ideas on Screens: Essential Notes Apps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-print-server-communication-failures/"><u>Strategies to Avoid Print Server Communication Failures</u></a></li>
<li><a href="https://win11.techidaily.com/stripping-decorative-elements-from-window-search-ui/"><u>Stripping Decorative Elements From Window Search UI</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-errors-forbidden-explained/"><u>Tackling Windows Errors: Forbidden Explained</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-apps-to-skyrocket-your-productivity-on-windows-11-or-11/"><u>The 5 Best Apps to Skyrocket Your Productivity on Windows 11 or 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-windows-display-duration-manual/"><u>The Complete Windows Display Duration Manual</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-blueprint-for-addressing-directdraw-errors-on-windows-1011/"><u>The Comprehensive Blueprint for Addressing DirectDraw Errors on Windows 10/11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/transformative-tips-making-an-indelible-mark-in-the-digital-world/"><u>Transformative Tips  Making an Indelible Mark in the Digital World</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-key-using-these-tips/"><u>Unlock Full Control of Windows Key Using These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-disks-easy-steps-in-w10w11/"><u>Unlocking Your Disks: Easy Steps in W10/W11</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-device-checkup-the-essential-five-ways-to-monitor-availability/"><u>Windows 11 Device Checkup: The Essential Five Ways to Monitor Availability</u></a></li>
<li><a href="https://win11.techidaily.com/zoning-out-realign-your-mouse-wheel-now-7-steps/"><u>Zoning Out? Realign Your Mouse Wheel Now! (7 Steps)</u></a></li>
</ul></div>

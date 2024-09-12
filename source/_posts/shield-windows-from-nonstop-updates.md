---
title: Shield Windows From Nonstop Updates
date: 2024-09-11T09:31:36.214Z
updated: 2024-09-12T09:31:36.214Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shield Windows From Nonstop Updates
excerpt: This Article Describes Shield Windows From Nonstop Updates
keywords: Update Shielding Windows,Prevent Window Changes,Stop Window Updates,Secure Windows Stable,Protect From Constant Updates,Nonstop Updates Halted,Guard Windows Unchanged
thumbnail: https://thmb.techidaily.com/170a02146718886a24f76eaa0c0aba6ab58e23eceef32078422970e554d48bd8.jpg
---

## Shield Windows From Nonstop Updates

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart the Computer From Settings

 If restarting your computer with the power button does not work, do it via the Settings Menu. This trick has worked for many users who encountered the same issue. Try it and see if that helps.

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click **Windows Update** in the left sidebar.
3. Under Windows Update, you will find the **Restart now** option.
4. Select this option to restart your computer and install the pending updates.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Install Pending Updates

 If your computer keeps reminding you to update and shuts down, check for pending updates. It is possible that the updates were not installed properly and Windows is now asking you to complete them.

 To check for pending updates, follow these steps.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. From the left sidebar, click on the **Windows Update** tab.
3. Select the **Check for updates** option from the right pane.

 This will search for available updates and install them if there are any. If you see no updates, continue to the next solution.

## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123468/16836" target="_top" id="2123468">
  <img src="//a.impactradius-go.com/display-ad/16836-2123468" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123468/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Follow the instructions on the screen to let Windows Update Troubleshooter detect and fix problems. After running the troubleshooter, restart your computer and check if it solves the issue.

## 4\. Clear the Software Distribution Folder

 The Software Distribution folder contains downloaded updates and installation files. If these files become corrupted, it could lead to this issue. To fix it, clear the Software Distribution directory and check if that solves the problem.

1. Open the Start menu and type CMD in the search bar.
2. Press **Ctrl + Shift + Enter** on your keyboard. This will open the Command Prompt as an administrator.
3. If a User Account Control window appears, click **Yes** to grant administrative privileges.
4. In the command prompt window, type the following commands in the order given and press Enter after each command:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After that, open File Explorer and navigate to this path:  
`C:\Windows\SoftwareDistribution`
6. In the SoftwareDistribution folder, select all the files and delete them permanently.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
7. When a permissions pop-up appears, select the checkbox and click **Continue**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset the Windows Update Components

 If none of the solutions above work, reset Windows Update components. It deletes all the temporary download files and resets the registry keys containing information about Windows Update. This process also clears any corrupted files associated with updates and allows Windows to download the updates again.

 To reset the Windows Update components, follow these steps:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy the following commands and paste them into the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Click **File** and select **Save as** from the menu list.
4. In the dialog box, select **All Files** from the **Save as type** drop-down menu.
5. Save the file as **ResetWindowsUpdate.bat** and close Notepad.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-top-live-streams-global-and-local-2024-edition/"><u>[New] Top Live Streams Global & Local, 2024 Edition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-crafting-engaging-youtube-channel-names-for-vlogger-success-no-more-than-156-for-2024/"><u>[Updated] Crafting Engaging YouTube Channel Names for Vlogger Success (No More Than 156) for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-elevate-engagement-posting-video-content-from-twitter-on-snapchat/"><u>[Updated] In 2024, Elevate Engagement Posting Video Content From Twitter on Snapchat</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-opening-doors-to-collective-listening-on-youtube/"><u>[Updated] In 2024, Opening Doors to Collective Listening on YouTube</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-reel-in-attention-by-emulating-tiktok-stardom-on-instagram/"><u>[Updated] Reel In Attention by Emulating TikTok Stardom on Instagram</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-auditory-ambiance-elevating-your-instagram-creations/"><u>2024 Approved Auditory Ambiance Elevating Your Instagram Creations</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-techniques-for-unlinking-youtube-videos-from-devices/"><u>2024 Approved Techniques for Unlinking YouTube Videos From Devices</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-nubia-red-magic-9-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-oppo-a59-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Oppo A59 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1721802080511-bringing-advanced-search-to-your-fingers-bings-ai-for-smartphones/"><u>Bringing Advanced Search to Your Fingers: Bing’s AI for Smartphones.</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-overcoming-usb-not-recognized-error-in-virtualbox/"><u>Comprehensive Guide: Overcoming 'USB Not Recognized' Error in VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-microsoft-store-issue-x80073d26-on-win11/"><u>Correcting Microsoft Store Issue X:80073d26 on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decisive-action-plan-for-banishing-flashing-screens-on-windows/"><u>Decisive Action Plan for Banishing Flashing Screens on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/discovering-windows-10-release-information-a-guide-to-finding-your-systems-build-number/"><u>Discovering Windows 10 Release Information: A Guide to Finding Your System's Build Number</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/elevating-your-webinar-footage-with-best-practices/"><u>Elevating Your Webinar Footage with Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-always-on-top-notations-on-windows/"><u>Ensuring Always On-Top Notations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/file-resurrection-made-simple-8-methods-for-windows-users/"><u>File Resurrection Made Simple: 8 Methods for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fixing-ralink-rt3290-wi-fi-drivers-on-windows-11-8-and-7-a-complete-guide/"><u>Fixing Ralink RT3290 Wi-Fi Drivers on Windows 11, 8 & 7: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-windows-index-adjustment-steps/"><u>Guide: Windows Index Adjustment Steps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-no-drivers-error-during-installation/"><u>How to Resolve Windows No Drivers Error During Installation</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-efficiency-in-it-support-with-troubleshooters-shortcut-guide/"><u>Maximize Efficiency in IT Support with Troubleshooters Shortcut Guide</u></a></li>
<li><a href="https://win11.techidaily.com/missed-sd-card-display-how-to-locate-it-in-explorer/"><u>Missed SD Card Display: How to Locate It in Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-a-fresh-approach-to-admin-rights-on-windows-os/"><u>Pioneering a Fresh Approach to Admin Rights on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-pc-name-error-in-win11/"><u>Steps to Resolve PC Name Error in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/synchronizing-qbittorrent-settings-between-multiple-windows-systems/"><u>Synchronizing qBittorrent Settings Between Multiple Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-utorrent-download-interruptions-on-pcs/"><u>Tackling uTorrent Download Interruptions on PCs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-complete-roadmap-downloading-editing-and-customizing-whatsapp-tones/"><u>The Complete Roadmap Downloading, Editing & Customizing WhatsApp Tones</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-trim-windows-overscan-for-flawless-screen-match/"><u>Tips to Trim Windows Overscan for Flawless Screen Match</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-recent-activities-on-windows-os/"><u>Uncovering Recent Activities on Windows OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/understanding-instagrams-tunes-and-their-legal-boundaries/"><u>Understanding Instagram’s Tunes and Their Legal Boundaries</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-best-mpa-to-mp3-converter-convert-mpa-audio-files-to-mp3-for-free/"><u>Updated 2024 Approved Best MPA to MP3 Converter Convert MPA Audio Files to MP3 for Free</u></a></li>
<li><a href="https://extra-resources.techidaily.com/visual-extremes-enhancer-top-video-quality/"><u>Visual Extremes Enhancer Top Video Quality</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-should-prefer-windows-11-over-macos/"><u>Why You Should Prefer Windows 11 over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-disk-management-a-comprehensive-walkthrough/"><u>Win 10/11 Disk Management: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-inside-the-settings-experience/"><u>Windows 11: Inside the Settings Experience</u></a></li>
<li><a href="https://win11.techidaily.com/workaround-strategies-overcoming-banned-app-error-in-os/"><u>Workaround Strategies: Overcoming Banned App Error in OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
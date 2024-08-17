---
title: Troubleshooting Blocked App Notification in Windows
date: 2024-08-16T00:48:33.374Z
updated: 2024-08-17T00:48:33.374Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Blocked App Notification in Windows
excerpt: This Article Describes Troubleshooting Blocked App Notification in Windows
keywords: Fix Blocked Notify Issue,Unblock App Alerts WIN,Resolve Notification Error,Clear App Notification Halt,Stop Blocked App Alert,Restore Windows Alert,Disable Blocked App Msg
thumbnail: https://thmb.techidaily.com/6d8730f2a77f7bacc79151a55ebc1a6b3c6364485074d0b800543a32a08c9abf.jpg
---

## Troubleshooting Blocked App Notification in Windows

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## 3\. Run the Program as an Administrator

 Some programs require administrator privileges to function properly. If you try to launch them without elevated access, Windows will block their execution and display the error message. In such a case, you can right-click on the app’s shortcut or the executable file and select **Run as administrator**.

 If it runs successfully, you can adjust the app properties to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). Don't forget to save the changes.

## 4\. Disable the SmartScreen Filter

 SmartScreen is a security feature that protects your computer from unknown and potentially malicious applications. If it’s enabled, SmartScreen may block an application from running. To disable the feature, follow these steps.

1. Open the **Start** menu and search for _Windows Security_.
2. Click on **Windows Security** in the search results.
3. In the Windows Security app, select **App & browser control**.
4. On the right side of the window, click **Reputation-based protection settings**.  
![Disable the SmartScreen Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-smartscreen-filter.jpg)
5. Toggle off **Potentially unwanted app blocking** and **SmartScreen for Microsoft Store apps**.

 This will stop the system from blocking apps, but you should be careful with any programs you download. Once you do it, close the Windows Security app and try running the application again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Once you're in the Local Group Policy Editor window, navigate to the following:  
`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

 After making the changes, close the Registry Editor and restart your computer.

## 7\. Reset Windows Update Components

 If the issue persists, you can reset the Windows Update components, which means restarting certain services that manage the update process and enable you to launch the application.

 To reset Windows Update components, do the following:

1. Click on Start and search for **Notepad**.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. Copy and paste the following code into Notepad:  
`<code>net stop bits  
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
4. Now click **File** in the top left corner.
5. Then select **Save as** from the options list.
6. In the Save as window, name your script **Reset.bat** and set the Save as type to **All Files**.
7. Select **Desktop** from the left menu and click **Save**.
8. Double-click on the **Reset.bat** file to run it as an administrator.
9. If the UAC window pops up on the screen, click **Yes** to continue.

 Wait for the process to finish and restart your computer. After the reboot, try running the blocked app again. It should now work without issues.

## Get Access to Your Apps and Files on Windows

 Windows is known for its tight security which prevents malicious applications from launching and infecting your PC. However, sometimes even legitimate programs are blocked by the operating system and leave an error message saying “This app has been blocked for your protection.”

 There are several reasons why this error occurs. It includes outdated security software, the firewall interfering with the program, or the application not trusted by Windows. Read this guide to learn more about this error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-is-there-a-superior-cameras-marketplace-in-2024/"><u>[New] Is There a Superior Cameras Marketplace, In 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transform-your-snaps-into-art-with-snapseed-basics/"><u>[New] Transform Your Snaps Into Art with Snapseed Basics</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-effortlessly-record-audio-on-your-mac-using-audacity/"><u>[Updated] Effortlessly Record Audio on Your Mac Using Audacity</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exclusive-drone-visuals-free-luts-for-dji-drones/"><u>[Updated] Exclusive Drone Visuals  Free LUTS for DJI Drones</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-capturing-the-web-in-full-color-the-best-screen-recorders-reviewed/"><u>[Updated] In 2024, Capturing the Web in Full Color  The Best Screen Recorders Reviewed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-navigating-legalities-of-instagram-harmonies/"><u>[Updated] Navigating Legalities of Instagram Harmonies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-perfect-your-streamline-setup-unleashing-the-full-potential-of-floating-window-feature/"><u>[Updated] Perfect Your Streamline Setup  Unleashing the Full Potential of Floating Window Feature</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-sharpening-digital-images-through-strategic-zooming/"><u>[Updated] Sharpening Digital Images Through Strategic Zooming</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-tune-up-your-social-media-videos-for-maximum-impact/"><u>[Updated] Tune Up Your Social Media Videos for Maximum Impact</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-enhancing-video-discoverability-with-effective-titles-and-tags/"><u>2024 Approved  Enhancing Video Discoverability with Effective Titles & Tags</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-simplifying-textual-enhancement-for-ae-professionals/"><u>2024 Approved  Simplifying Textual Enhancement for AE Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-victory-in-original-diablo/"><u>Beginner’s Blueprint to Victory in Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/boost-safety-measures-include-trusted-sites-on-windows-11/"><u>Boost Safety Measures: Include Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-performance-with-smart-use-of-windows-11s-bar/"><u>Boosted Performance with Smart Use of Windows 11'S Bar</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-security-account-manager-failures/"><u>Combatting Security Account Manager Failures</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-error-4294967295-a-comprehensive-guide/"><u>Eliminating WSL Error 4294967295: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-linking-win-prefixes-and-ms-logins/"><u>Enhancing User Experience: Linking Win Prefixes & MS Logins</u></a></li>
<li><a href="https://win11.techidaily.com/explore-versatility-the-best-10-uses-for-windows-powertoys-tools/"><u>Explore Versatility: The Best 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fix-cluttered-desktop-with-removal-of-win11s-focus-icons/"><u>Fix Cluttered Desktop with Removal of Win11's Focus Icons</u></a></li>
<li><a href="https://win11.techidaily.com/1719265267578-fixing-winsplit-display-issues-now/"><u>Fixing WinSplit Display Issues Now</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/get-bitraser-securedrive-purge-suite-ultimate-disk-sanitization-software/"><u>Get BitRaser SecureDrive Purge Suite: Ultimate Disk Sanitization Software</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-embedding-google-play-into-windows-11/"><u>Guide to Embedding Google Play Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/holiday-harmony-delightful-wrapped-apps-through-ms-store/"><u>Holiday Harmony: Delightful Wrapped Apps Through MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-monitor-1-and-2-in-windows/"><u>How to Change Monitor 1 and 2 in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-f15-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy F15 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-10-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 10 & 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-oppo-a18-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Oppo A18 Activity | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-unveiling-premium-screen-recorders-in-tech/"><u>In 2024, Unveiling Premium Screen Recorders in Tech</u></a></li>
<li><a href="https://win11.techidaily.com/making-vintage-windows-computers-more-elderly-friendly/"><u>Making Vintage Windows Computers More Elderly Friendly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-y56-5g-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo Y56 5G</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-key-features-and-uses/"><u>Microsoft Family Safety: Key Features and Uses</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-in-2024-top-10-robotic-voice-generators/"><u>New In 2024, Top 10 Robotic Voice Generators</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/overcoming-obs-blank-screens-in-gaming-recording/"><u>Overcoming OBS Blank Screens in Gaming Recording</u></a></li>
<li><a href="https://techtrends.techidaily.com/resolving-kernel32dll-issues-on-your-pc-step-by-step-guide/"><u>Resolving Kernel32.dll Issues on Your PC - Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-photo-viewer-a-step-by-step-guide-for-11-users/"><u>Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-high-cpu-usage-in-setups/"><u>Taming the Beast: High CPU Usage in Setups</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-avoiding-mistakes-in-windows-11/"><u>The Beginner's Guide to Avoiding Mistakes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-version-numbering-in-windows/"><u>The Essence of Version Numbering in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-digital-gateway-easy-desktop-connectivity-with-win-11/"><u>Unlocking the Digital Gateway: Easy Desktop Connectivity with Win 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
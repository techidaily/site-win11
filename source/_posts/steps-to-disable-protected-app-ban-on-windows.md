---
title: Steps to Disable Protected App Ban on Windows
date: 2024-07-13T10:23:04.974Z
updated: 2024-07-14T10:23:04.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Disable Protected App Ban on Windows
excerpt: This Article Describes Steps to Disable Protected App Ban on Windows
keywords: Unblock Windows Apps,Bypass App Ban,Remove App Restrictions,Disable Windows Ban,Lift App Block,Eliminate App Lockdown,Ease App Ban Removal
thumbnail: https://thmb.techidaily.com/fa8cb6ca311af8694c1fd2b592b0789e69f6337924778efc705315343e4f909c.jpg
---

## Steps to Disable Protected App Ban on Windows

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

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

## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
3. Once you're in the Local Group Policy Editor window, navigate to the following:  
`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/quickening-boot-process-windows-11-timeout-reduction-guide/"><u>Quickening Boot Process: Windows 11 Timeout Reduction Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-affordable-art-of-youtube-introsends/"><u>In 2024, The Affordable Art of YouTube Intros/Ends</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-resolving-iomap64-bsod-on-windows-108-devices/"><u>Quick Tips: Resolving IOMap64 BSOD on Windows 10/8 Devices</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-best-10-battle-royale-games/"><u>[Updated] 2024 Approved  Best 10 Battle Royale Games</u></a></li>
<li><a href="https://screen-recording.techidaily.com/aggregated-insights-on-10-superior-video-call-apps-for-2024/"><u>Aggregated Insights on 10 Superior Video Call Apps for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-outsmarting-online-advertising-on-social-network-sites/"><u>[Updated] In 2024, Outsmarting Online Advertising on Social Network Sites</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-window-preview-failures-in-win-810/"><u>Addressing Window Preview Failures in Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-editing-engine-room/"><u>[New] Editing Engine Room</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-enable-startup-diagnostics/"><u>A Step-by-Step Guide to Enable Startup Diagnostics</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-context-menu-choices-with-automatic-patch-information/"><u>Enriching Context Menu Choices with Automatic Patch Information</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-no-support-errors-5-effective-steps/"><u>Navigating Windows No-Support Errors: 5 Effective Steps</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-the-art-of-srt-files-an-all-inclusive-guide-to-subtitles/"><u>In 2024, Mastering the Art of SRT Files  An All-Inclusive Guide to Subtitles</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-new-world-of-windows-11-avoidance-guide-top-8/"><u>Navigating the New World of Windows 11: Avoidance Guide (Top 8)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/easy-peasy-screen-transitions-for-filmmakers/"><u>Easy-Peasy Screen Transitions for Filmmakers</u></a></li>
<li><a href="https://win11.techidaily.com/uninstall-simplified-top-methods-for-windows-11-users-111-chars/"><u>Uninstall Simplified: Top Methods for Windows 11 Users (111 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-read-only-barrier-errors-in-windows-11/"><u>Eliminating Steam Read-Only Barrier Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smoothly-switching-programs-for-your-first-win-11-experience/"><u>Smoothly Switching Programs for Your First Win 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-common-errors-in-windows-update-xc004f050/"><u>Bypassing Common Errors in Windows Update Xc004f050</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-precision-crafting-win11-self-extractables/"><u>The Path to Precision: Crafting Win11 Self-Extractables</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-tpm-deactivation-for-modern-windows-users/"><u>Triumph in TPM Deactivation for Modern Windows Users</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-video-speed-controllers-best-options-for-pc-and-mac/"><u>New 2024 Approved Video Speed Controllers Best Options for PC and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/1719368082467-switch-off-windows-11-defender-firewall-now/"><u>Switch Off Windows 11 Defender Firewall Now</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-download-custom-mcb-banner-packs-for-2024/"><u>[Updated] Download Custom MCB Banner Packs for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/innovative-techniques-for-maximum-zoom-utility-on-chromebook/"><u>Innovative Techniques for Maximum Zoom Utility on Chromebook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/unmatched-budget-friendly-camera-challenges/"><u>Unmatched Budget-Friendly Camera Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-recovering-lost-run-data/"><u>Tips for Recovering Lost Run Data</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-for-managing-users-in-command-prompt/"><u>Essential Tools for Managing Users in Command Prompt</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-digital-dialogue-preservation-guide/"><u>[Updated] Digital Dialogue Preservation Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-comprehensive-guide-to-nvidia-screener-use/"><u>2024 Approved  Comprehensive Guide to NVIDIA Screener Use</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-from-iphone-xs-max-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account From iPhone XS Max?</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-3-ways-to-export-contacts-from-apple-iphone-6s-to-excel-csv-and-vcard-easily-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 3 Ways to Export Contacts from Apple iPhone 6s to Excel CSV & vCard Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-removing-windows-defender-error-0x80004004/"><u>Understanding & Removing Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-optimize-for-popularity-top-youtube-seo-devices-unveiled/"><u>[New] 2024 Approved  Optimize for Popularity  Top YouTube SEO Devices Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-to-the-authorization-interface-in-windows-11/"><u>Pathways to the Authorization Interface in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-high-ranking-mac-tools-to-replace-standard-bandicam/"><u>[New] In 2024, High-Ranking Mac Tools to Replace Standard Bandicam</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-no-one-watching-to-huge-engagement-10-proven-ways-to-increase-video-popularity/"><u>In 2024, From No One Watching to Huge Engagement  10 Proven Ways to Increase Video Popularity</u></a></li>
<li><a href="https://win11.techidaily.com/add-on-troubleshooters-for-improved-software-functionality/"><u>Add-On Troubleshooters for Improved Software Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/managing-your-digital-life-restarting-apps-in-windows-11/"><u>Managing Your Digital Life: Restarting Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pc-potential-by-clearing-windows-temp-files/"><u>Unlock Your PC Potential by Clearing Windows Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/top-quick-strategies-for-black-screen-in-wins-1011/"><u>Top Quick Strategies for Black Screen in Wins 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-turn-off-unsolicited-game-suggestions-for-w11/"><u>Learn to Turn Off Unsolicited Game Suggestions for W11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-free-to-edit-10-android-video-apps-with-no-watermark-restrictions-for-2024/"><u>Updated Free to Edit 10 Android Video Apps with No Watermark Restrictions for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-ultimate-guide-to-photo-and-video-collage-software/"><u>New 2024 Approved The Ultimate Guide to Photo and Video Collage Software</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-way-to-clean-clear-notes/"><u>The Obsidian Way to Clean, Clear Notes</u></a></li>
<li><a href="https://win11.techidaily.com/five-methods-for-protecting-your-pc-avoiding-bitlocker/"><u>Five Methods for Protecting Your PC: Avoiding BitLocker</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-asmr-recommendations-for-android-users-for-2024/"><u>[Updated] ASMR Recommendations for Android Users for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/early-release-decision-making-for-game-lovers/"><u>Early Release Decision Making for Game Lovers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-overlay-effects-in-nvidia-graphics/"><u>How to Turn Off Overlay Effects in NVIDIA Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-writable-registry-for-hidden-themes/"><u>Mastering Windows 11' Writable Registry for Hidden Themes</u></a></li>
<li><a href="https://techidaily.com/some-mp4-wont-play-on-my-razr-40-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Razr 40</u></a></li>
</ul></div>

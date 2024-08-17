---
title: "Optimize Disk Space: Clear Temporary Windows Files Now!"
date: 2024-08-15T23:27:41.751Z
updated: 2024-08-16T23:27:41.751Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Disk Space: Clear Temporary Windows Files Now!"
excerpt: "This Article Describes Optimize Disk Space: Clear Temporary Windows Files Now!"
keywords: Optimize Disk Usage,Delete Temp Files,Free Up Storage,Clear Cache Data,Speedup Computer,Unclutter System,Reduce RAM Use
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## Optimize Disk Space: Clear Temporary Windows Files Now

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-deciphering-digital-dominance-youtube-content-strategy-comparison/"><u>[New] 2024 Approved  Deciphering Digital Dominance  YouTube Content Strategy Comparison</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-ultimate-converter-mp4-videos-to-facebook/"><u>[New] In 2024, Ultimate Converter  MP4 Videos to Facebook</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-5-best-monitors-to-complement-your-ps5-xbox-series-x/"><u>[New] The 5 Best Monitors to Complement Your PS5, Xbox Series X</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-comical-voyage-analyzing-the-goofy-escapade/"><u>[Updated] A Comical Voyage  Analyzing 'The Goofy Escapade'</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-dslr-mastery-broadcasting-with-facebook-live-via-computer-for-2024/"><u>[Updated] DSLR Mastery  Broadcasting with Facebook Live via Computer for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-how-to-ensure-your-virtual-meetings-are-documented-for-2024/"><u>[Updated] How to Ensure Your Virtual Meetings Are Documented for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-leverage-these-10-devices-for-crystal-clear-zooms/"><u>[Updated] In 2024, Leverage These 10 Devices for Crystal Clear Zooms</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-top-5-video-tweaking-apps-for-social-networking/"><u>[Updated] Top 5 Video Tweaking Apps for Social Networking</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovative-srt-conversion-tactics-for-pc-and-mac/"><u>2024 Approved  Innovative SRT Conversion Tactics for PC and Mac</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-the-ultimate-30plus-list-of-expertly-curated-cost-free-vfx-tools-for-creatives/"><u>2024 Approved  The Ultimate 30+ List of Expertly Curated, Cost-Free VFX Tools for Creatives</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-view-the-applied-group-policies-on-windows/"><u>3 Ways to View the Applied Group Policies on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-pivotal-points-for-reconnecting-your-obs-studio-link-win-compatible/"><u>7 Pivotal Points for Reconnecting Your OBS Studio Link (Win-Compatible)</u></a></li>
<li><a href="https://win11.techidaily.com/8-handy-windows-11-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 11 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-sign-in-method-youre-trying-to-use-isnt-allowed-error-on-windows/"><u>8 Ways to Fix The Sign-In Method You're Trying to Use Isn't Allowed Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-developers-journey-github-desktop-in-the-era-of-win-11/"><u>A Developer's Journey: GitHub Desktop in the Era of Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-keeping-your-tasks-visible-and-high-priority/"><u>A Guide to Keeping Your Tasks Visible and High-Priority</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-activatedeactivate-windows-low-power-mode/"><u>A Quick Guide: Activate/Deactivate Windows' Low-Power Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-to-creativity-best-drawing-apps-for-win10/"><u>A Window to Creativity: Best Drawing Apps for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-productivity-with-essential-windows-11-methods/"><u>Accelerate Productivity with Essential Windows 11 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-steam-download-rates-overcoming-sluggish-pace/"><u>Accelerate Steam Download Rates: Overcoming Sluggish Pace</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-3d-paint-process-with-these-tips/"><u>Accelerate Your 3D Paint Process with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-top-scores-fixing-lags-in-valorant/"><u>Achieving Top Scores: Fixing Lags in Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/activatedeactivate-window-11-search-lights/"><u>Activate/Deactivate Window 11 Search Lights</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-forbidden-page-in-windows-environment/"><u>Addressing Forbidden Page in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msvcr110dll-disappearance/"><u>Addressing msvcr110.dll Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-nvidia-cp-in-w11-environments/"><u>Addressing Non-Operational NVidia CP in W11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-systemsettings-issue-on-windows-11/"><u>Addressing SystemSettings Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-lockout-interval-after-multiple-login-failures/"><u>Adjusting Lockout Interval After Multiple Login Failures</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-account-lockout-counter-following-unsuccessful-logins-in-w10w11/"><u>Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-partition-management-tactics/"><u>Advanced Windows Partition Management Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-alchemy-how-to-seamlessly-change-windows-11-themes-and-enrich-your-workspace/"><u>Aesthetic Alchemy: How to Seamlessly Change Windows 11 Themes and Enrich Your Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/alert-essential-windows-processes-to-watch-for-malware/"><u>Alert: Essential Windows Processes to Watch for Malware</u></a></li>
<li><a href="https://win11.techidaily.com/an-overview-of-cab-files-in-windows-and-how-to-install-them/"><u>An Overview of CAB Files in Windows and How to Install Them</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-folder-empty-warning-on-windows-pcs/"><u>Avoiding Folder Empty Warning on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overuse-steps-for-efficient-wlanextexe/"><u>Avoiding Overuse: Steps for Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-power-and-performance-in-windows-systems/"><u>Balancing Power and Performance in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-renaming-administrators-in-windows-11-pro/"><u>Best Practices for Renaming Administrators in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/best-vmms-aligned-with-windows-11-system-requirements/"><u>Best VMMs Aligned with Windows 11 System Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-10-and-11-climate-choices/"><u>Best Windows 10 & 11 Climate Choices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/beyond-basic-editing-innovative-use-of-luts-for-photography/"><u>Beyond Basic Editing  Innovative Use of LUTs for Photography</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-bonanza-lifelong-windows-10-priced-low-612/"><u>Black Friday Bonanza: Lifelong Windows 10 Priced Low ($6.12)</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-capabilities-upgrading-to-virtualbox-70-in-win11/"><u>Boost Your VM Capabilities: Upgrading to VirtualBox 7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-oppo-a78-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-samsung-galaxy-s23plus-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Samsung Galaxy S23+ Phone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-from-iphone-xs-max-or-ipad-by-drfone-ios/"><u>In 2024, How to Bypass Activation Lock from iPhone XS Max or iPad?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-legally-convert-youtube-videos-to-mp4-format/"><u>In 2024, How to Legally Convert YouTube Videos to MP4 Format</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-snipers-manual-to-capturing-live-online-music/"><u>In 2024, The Sniper’s Manual to Capturing Live Online Music</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-samsung-galaxy-s24plus-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Samsung Galaxy S24+</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-ultimate-pathway-for-high-quality-video-production-in-adobe-connect/"><u>In 2024, The Ultimate Pathway for High-Quality Video Production in Adobe Connect</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-zte-nubia-z60-ultra-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On ZTE Nubia Z60 Ultra? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/social-media-forecasting-through-data-visualization-for-2024/"><u>Social Media Forecasting Through Data Visualization for 2024</u></a></li>
<li><a href="https://techidaily.com/tecno-data-retrieval-tool-restore-lost-data-from-tecno-spark-20-proplus-by-fonelab-android-recover-data/"><u>Tecno Data Retrieval tool – restore lost data from Tecno Spark 20 Pro+</u></a></li>
<li><a href="https://win11.techidaily.com/1719298121554-troubleshoot-windows-update-hurdles-quick-solutions/"><u>Troubleshoot: Windows Update Hurdles - Quick Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-overcoming-unable-to-connect-errors-with-remote-servers/"><u>Troubleshooting Steps for Overcoming 'Unable to Connect' Errors with Remote Servers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/updated-drivers-install-guide-for-hp-officejet-pro-8720-compatible-with-windows/"><u>Updated Drivers Install Guide for HP OfficeJet Pro 8720 - Compatible with Windows</u></a></li>
</ul></div>

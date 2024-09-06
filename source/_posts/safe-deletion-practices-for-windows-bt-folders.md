---
title: Safe Deletion Practices for Windows ~BT Folders
date: 2024-09-05T08:36:34.337Z
updated: 2024-09-06T08:36:34.337Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Safe Deletion Practices for Windows ~BT Folders
excerpt: This Article Describes Safe Deletion Practices for Windows ~BT Folders
keywords: Safe BT Delete,Secure Windows Erase,BT Files Cleanup,Safe File Removal,Windows Security Purge,Deletion Safety Tips,Protecting Batch Data
thumbnail: https://thmb.techidaily.com/3940086541c823408b7e3893cd4adcfe04714cf8a1d0ceb2c3d06364d867bc68.png
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115931/19272" target="_top" id="2115931">
  <img src="//a.impactradius-go.com/display-ad/19272-2115931" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Safe Deletion Practices for Windows ~BT Folders

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-megadron-mastery-industrys-top-heavy-loaders/"><u>[New] 2024 Approved  Megadron Mastery  Industry's Top Heavy Loaders</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-the-dynamic-edge-technique-adding-motion-blur-to-portraits-using-picsart/"><u>[New] In 2024, The Dynamic Edge Technique  Adding Motion Blur to Portraits Using Picsart</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-smart-way-to-extract-specific-segments-from-youtube-for-2024/"><u>[New] The Smart Way to Extract Specific Segments From YouTube for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-elevate-your-creations-the-7-most-innovative-nft-generators/"><u>[Updated] 2024 Approved  Elevate Your Creations - The 7 Most Innovative NFT Generators</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-free-software-leaders-in-chromebook-screen-recording/"><u>[Updated] In 2024, Free Software Leaders in Chromebook Screen Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-pure-joy-of-gratuitous-screen-mingle-games/"><u>[Updated] Pure Joy of Gratuitous Screen Mingle Games</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-terminology-trek-through-the-virtual-landscape/"><u>[Updated] Terminology Trek Through the Virtual Landscape</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>10 Best Fake GPS Location Spoofers for Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-manage-app-packages-with-winget-on-win11/"><u>Comprehensively Manage App Packages with Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-display-not-responding-on-windows-11/"><u>Correcting 'Display Not Responding' On Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-techniques-for-restoring-compromised-system-data-on-latest-windows-versions/"><u>Effective Techniques for Restoring Compromised System Data on Latest Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-multi-monitor-use-with-these-windows-11-tips/"><u>Effortless Multi-Monitor Use with These Windows 11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-system-speed-through-virtual-memory-management/"><u>Elevating System Speed Through Virtual Memory Management</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-utilizing-condensed-explorer-settings/"><u>Enhance Visibility: Utilizing Condensed Explorer Settings</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixes-for-faded-colors-and-twisted-graphics-on-computer-screens-an-easy-diy-approach/"><u>Fixes for Faded Colors and Twisted Graphics on Computer Screens: An Easy DIY Approach</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-the-out-of-video-memory-glitch-in-black-myth-wukong-game-crashes-on-windows/"><u>Fixing the 'Out of Video Memory' Glitch in Black Myth: Wukong Game Crashes on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-hyper-v-error-0x8009030e-in-windows/"><u>How to Fix the Hyper-V Error 0X8009030E in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-error-0x800700e1-in-windows-11-os/"><u>How to Overcome Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-sleep-on-win11/"><u>How to Reactivate Sleep on Win11?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-show-or-hide-folders-in-this-pc-on-windows-11/"><u>How to Show or Hide Folders in This PC on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-htc-u23-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On HTC U23? | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-mastering-the-craft-top-7-techniques-for-captivating-meme-creation/"><u>In 2024, Mastering the Craft  Top 7 Techniques for Captivating Meme Creation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insight-computing-through-time-with-windows/"><u>Insight: Computing Through Time with Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-the-mechanics-of-successful-startups-resolving-atomic-heart-launch-failures/"><u>Master the Mechanics of Successful Startups: Resolving 'Atomic Heart' Launch Failures</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-auto-updates-and-change-amd-gpu-drives-in-win10/"><u>Navigate Auto-Updates & Change AMD GPU Drives in Win10</u></a></li>
<li><a href="https://win11.techidaily.com/reinforcing-operational-capabilities-of-windows-problem-solvers/"><u>Reinforcing Operational Capabilities of Windows Problem Solvers</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-the-clear-edge-tips-to-rectify-blurry-win11-displays/"><u>Reveal the Clear Edge: Tips to Rectify Blurry Win11 Displays</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-clear-vac-failed-windows-error/"><u>Solutions to Clear VAC Failed Windows Error</u></a></li>
<li><a href="https://win11.techidaily.com/solving-x80780119-error-windows-system-restore/"><u>Solving X80780119 Error: Windows System Restore</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-rectify-windows-error-code-30005-create-failure/"><u>Strategies to Rectify Windows Error Code: 30005 Create Failure</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-operations-with-process-insight-and-elegant-theming-in-windows-11/"><u>Streamline Operations with Process Insight and Elegant Theming in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-group-policies-in-windows-environments/"><u>Streamlining Group Policies in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/stuck-xbox-on-windows-heres-how-to-unlock-it/"><u>Stuck Xbox on Windows? Here's How to Unlock It</u></a></li>
<li><a href="https://win11.techidaily.com/taming-technology-turmoil-essential-techniques-for-windows-application-resets/"><u>Taming Technology Turmoil: Essential Techniques for Windows Application Resets</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-approach-to-unlock-your-start-menu-potential-in-windows-11/"><u>The Ultimate Approach to Unlock Your Start Menu Potential in Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-payment-decline-on-apple-platforms-the-ultimate-guide-with-6-fixes/"><u>Troubleshooting Payment Decline on Apple Platforms: The Ultimate Guide with 6 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unreachable-ms-sql-server-for-malwarebytes-on-win-1011/"><u>Troubleshooting Unreachable MS SQL Server for Malwarebytes on Win 10/11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/understanding-the-edge-of-av1-in-video-encoding/"><u>Understanding the Edge of AV1 in Video Encoding</u></a></li>
<li><a href="https://win11.techidaily.com/unifying-computing-windows-adapts-to-iphones-ipads-macs-and-desktops/"><u>Unifying Computing: Windows Adapts to iPhones, iPads, Macs, and Desktops</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlock-your-videos-hidden-potential-with-these-top-20-shortcuts-for-2024/"><u>Unlock Your Video's Hidden Potential with These Top 20 Shortcuts for 2024</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-new-essential-details-of-making-perfect-talking-face/"><u>Updated New Essential Details of Making Perfect Talking Face</u></a></li>
<li><a href="https://win11.techidaily.com/where-windows-keeps-your-image-snaps/"><u>Where Windows Keeps Your Image Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/winrar-file-integrity-6-strategies-for-checksum-precision/"><u>WinRAR File Integrity: 6 Strategies for Checksum Precision</u></a></li>
<li><a href="https://win11.techidaily.com/worldwide-unity-windows-encompasses-iphoneipad-macpc-communities/"><u>Worldwide Unity: Windows Encompasses iPhone/iPad, Mac/PC Communities</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
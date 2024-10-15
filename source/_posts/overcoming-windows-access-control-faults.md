---
title: Overcoming Windows' Access Control Faults
date: 2024-10-14T20:07:50.448Z
updated: 2024-10-15T17:02:04.679Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows' Access Control Faults
excerpt: This Article Describes Overcoming Windows' Access Control Faults
keywords: Fixing AC Errors,WinAC Resolution,Windows Security Glitches,Access Control Corrections,Windows Permissions Faults,UAC Fix Strategies,Secure WinAC Settings
thumbnail: https://thmb.techidaily.com/0fde8be80e602ff65625842ff908df27188b320349e0a53c08ea2eca9a5b67ed.jpg
---

## Overcoming Windows' Access Control Faults

 Your computer has what's known as an Access Control List (ACL). Its job is to tell Windows the resources, such as files and folders, users can access on your computer. If something corrupts the ACL, you can run into the “access control entry is corrupt” error when trying to access certain resources on Windows.

 We're going to show you how to get rid of the “access control entry is corrupt” error on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Perform an SFC or CHKDSK Scan

 Running an SFC scan can fix the error by fixing any corrupt system files associated with the proper functioning of the ACL. If the files are missing, a DISM scan will replace them using a cached Windows system image file. If these two scans don't work, the problem could be related to hard disk errors, which you can fix with a CHKDSK scan.

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The above-mentioned tools are [built into Windows to help repair corrupt or damaged files](https://www.makeuseof.com/windows-built-in-repair-tools), and you should familiarize yourself with how and when to use them.

## 2\. Close All Universal Windows Platform (UWP) Apps

 Sometimes, UWP apps can lock resources when they're running in their sand-boxed environment. They're not supposed to, but when they do, you can get the “access control entry is corrupt” error message. To fix this, close the UWP app you suspect is the culprit and then update or reinstall it.

## 3\. Change Ownership of the Affected File or Folder

 Taking ownership of a file or folder can sometimes resolve the “access control entry is corrupt” error. To do that, follow the steps below:

1. Right-click the file or folder and select **Properties**.  
![the context menu in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-context-menu-in-windows-11.jpg)
2. Select the **Security** tab and then click on **Advanced** at the bottom to open the **Advanced Securities** window for the file.  
![the Security tab of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-security-tab-of-a-file-on-windows.jpg)
3. Next to the **Owner**, check to see if your username is listed as the owner of the file or folder. If it isn't, that may be the problem. So, click on the **Change** link next to it to open the Select User or Group window.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the Advanced Settings window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-settings-window-of-a-file-on-windows.jpg)
4. Click **Advanced** to open the **Select User or Group (Advanced)** window.  
![the Select User or Group window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-select-user-or-group-window-of-a-file-on-windows.jpg)
5. Click **Find Now** to search for the available users on your Windows computer.  
![the advanced Select User or Group window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-select-user-or-group-window-of-a-file-on-windows.jpg)
6. In the search results at the bottom, select your username and click **OK**.  
![the advanced Select User or Group window of a file on Windows with a list user on the PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-select-user-or-group-window-of-a-file-with-a-list-of-users-on-windows.jpg)
7. Back in the **Select User or Group** window, click **OK**.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. In the **Advanced Securities** window, click **Apply** and then **OK**.

 Now that you've changed ownership, try accessing the file or folder again and see if the error still shows up.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Try Accessing the File or Folder From a Different User Account

 Sometimes, the error pops up because your user account is corrupt, meaning that all the fixes above will most likely fail. What you can do is [create another user account on Windows for troubleshooting purposes](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

 Try to access the file or folder (provided it is in a publicly available directory), and if the error doesn't pop up, you can migrate the necessary files from the old account to the new one.

## 5\. Restore the Access Control List

 If none of the solutions above have worked, then it might be time to restore the ACL itself. To do that, first, [back up your Windows 10 computer](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) or [back up your Windows 11 computer](https://www.makeuseof.com/windows-11-create-complete-backup/).

 Then, [factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/), and that should get rid of the “access control entry is corrupt” error.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915805/19272" target="_top" id="1915805">
  <img src="//a.impactradius-go.com/display-ad/19272-1915805" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915805/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Access Every Resource on Your Windows Computer

 The “access control entry is corrupt” error is frustrating since it locks you out of the resources you need at the time on your Windows computer. Hopefully, the first four fixes will help before you have to do something drastic like resetting your PC. Either way, it's good to know you're not stuck with the error indefinitely.

 We're going to show you how to get rid of the “access control entry is corrupt” error on your Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-maximize-game-time-top-10-ps5-external-hddssd/"><u>[New] In 2024, Maximize Game Time Top 10 PS5 External HDD/SSD</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-unleash-timeliness-iphone-slow-motion-filming/"><u>[Updated] Unleash Timeliness IPhone Slow Motion Filming</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-ripple-producer-guide/"><u>2024 Approved Ripple Producer Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-component-services-in-windows-11/"><u>How to Open the Component Services in Windows 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-ideal-places-to-step-into-new-realities/"><u>In 2024, Ideal Places to Step Into New Realities</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-compreenasional-path-to-post-perfection-instagram-video-upload-from-pcmac/"><u>In 2024, The Compreenasional Path to Post-Perfection Instagram Video Upload From PC/Mac</u></a></li>
<li><a href="https://win-best.techidaily.com/master-the-art-of-data-preservation-on-pcs-create-secure-backups-using-cmd-in-windows-versions/"><u>Master the Art of Data Preservation on PCs: Create Secure Backups Using CMD in Windows Versions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-business-efficiency-top-uses-for-chatgpt/"><u>Maximizing Business Efficiency: Top Uses for ChatGPT</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/neo-theater-narratives-virtual-realms/"><u>Neo-Theater Narratives Virtual Realms</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-custom-power-plans-in-windows/"><u>Overhauling Custom Power Plans in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-app-malfunctions-on-devices/"><u>Strategies to Address Windows App Malfunctions on Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-distribution-the-ultimate-sefx-guide-for-win11/"><u>Streamlining File Distribution: The Ultimate SEFx Guide for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-practices-for-getting-most-from-windows-11s-launchpad/"><u>The Best Practices for Getting Most From Windows 11'S Launchpad</u></a></li>
<li><a href="https://win11.techidaily.com/the-components-configuration-console-in-windows-explored/"><u>The Components Configuration Console in Windows Explored</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-for-altering-windows-pin/"><u>The Essential Guide for Altering Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-managing-printers-in-windows-1011/"><u>The Essentials of Managing Printers in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/top-tier-software-selecting-the-most-effective-fps-counters-for-windows-11/"><u>Top-Tier Software: Selecting The Most Effective FPS Counters For Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
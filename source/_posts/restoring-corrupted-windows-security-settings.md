---
title: Restoring Corrupted Windows Security Settings
date: 2024-09-27T00:01:40.800Z
updated: 2024-10-04T02:34:51.835Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Corrupted Windows Security Settings
excerpt: This Article Describes Restoring Corrupted Windows Security Settings
keywords: Fixing Windows Secure Issues,Resetting Windows Safety,Recovering System Security,Reviving PC Protection,Restore Windows Lockdown,Repairing OS Security,Reinstating Security Settings
thumbnail: https://thmb.techidaily.com/22dc377b14c8750c75c360ab6d9b7d702e69a18c8a5a08c607e9cd26432f995f.jpg
---

## Restoring Corrupted Windows Security Settings

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
![the Advanced Settings window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-settings-window-of-a-file-on-windows.jpg)
4. Click **Advanced** to open the **Select User or Group (Advanced)** window.  
![the Select User or Group window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-select-user-or-group-window-of-a-file-on-windows.jpg)
5. Click **Find Now** to search for the available users on your Windows computer.  
![the advanced Select User or Group window of a file on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-select-user-or-group-window-of-a-file-on-windows.jpg)
6. In the search results at the bottom, select your username and click **OK**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080347/19272" target="_top" id="2080347">
  <img src="//a.impactradius-go.com/display-ad/19272-2080347" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080347/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![the advanced Select User or Group window of a file on Windows with a list user on the PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-advanced-select-user-or-group-window-of-a-file-with-a-list-of-users-on-windows.jpg)
7. Back in the **Select User or Group** window, click **OK**.
8. In the **Advanced Securities** window, click **Apply** and then **OK**.

 Now that you've changed ownership, try accessing the file or folder again and see if the error still shows up.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Try Accessing the File or Folder From a Different User Account

 Sometimes, the error pops up because your user account is corrupt, meaning that all the fixes above will most likely fail. What you can do is [create another user account on Windows for troubleshooting purposes](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

 Try to access the file or folder (provided it is in a publicly available directory), and if the error doesn't pop up, you can migrate the necessary files from the old account to the new one.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Restore the Access Control List

 If none of the solutions above have worked, then it might be time to restore the ACL itself. To do that, first, [back up your Windows 10 computer](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) or [back up your Windows 11 computer](https://www.makeuseof.com/windows-11-create-complete-backup/).

 Then, [factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/), and that should get rid of the “access control entry is corrupt” error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Access Every Resource on Your Windows Computer

 The “access control entry is corrupt” error is frustrating since it locks you out of the resources you need at the time on your Windows computer. Hopefully, the first four fixes will help before you have to do something drastic like resetting your PC. Either way, it's good to know you're not stuck with the error indefinitely.

 We're going to show you how to get rid of the “access control entry is corrupt” error on your Windows computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-quick-guide-to-rearranging-your-youtube-collection/"><u>[Updated] 2024 Approved Quick Guide to Rearranging Your YouTube Collection</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-uniting-communication-and-visuals-a-detailed-plan-for-slack-plus-filmora-meetings/"><u>2024 Approved Uniting Communication & Visuals A Detailed Plan for Slack + Filmora Meetings</u></a></li>
<li><a href="https://tech-revival.techidaily.com/analysis-alert-5-key-factors-preventing-chatgpt-from-reliable-crypto-insights/"><u>Analysis Alert: 5 Key Factors Preventing ChatGPT From Reliable Crypto Insights</u></a></li>
<li><a href="https://article-helps.techidaily.com/b-roll-wisdom-enhancing-your-cinematic-quality/"><u>B-Roll Wisdom Enhancing Your Cinematic Quality</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-up-the-grayed-extend-volume-buttons/"><u>Brighten Up the Grayed Extend Volume Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/bring-life-to-monitors-with-custom-spotlight-backdrops/"><u>Bring Life to Monitors with Custom Spotlight Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/bring-slack-notifications-back-from-the-dead-in-windows-11/"><u>Bring Slack Notifications Back From the Dead in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forth-hidden-windows-drive/"><u>Bringing Forth Hidden Windows Drive</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-stranded-status-a-quick-guide-for-xbox-users/"><u>Bypassing ‘Stranded’ Status: A Quick Guide for Xbox Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-store-crash-code-x800704cf/"><u>Bypassing Microsoft's Store Crash Code X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-windows-restrictions-quickly/"><u>Circumventing Windows Restrictions Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/combat-code-confusion-skyrim-sse-troubleshoot/"><u>Combat Code Confusion: Skyrim SSE Troubleshoot</u></a></li>
<li><a href="https://hardware-help.techidaily.com/guide-to-obtain-your-canon-mg3620s-official-drivers-safely/"><u>Guide to Obtain Your Canon MG3620's Official Drivers Safely</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-eliminate-delay-in-valorant-gameplay-for-pc-users-updated-2n-2024/"><u>How to Eliminate Delay in Valorant Gameplay for PC Users (Updated 2N 2024)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-laugh-ledger-top-10-tweets-for-a-smile/"><u>In 2024, Laugh Ledger Top 10 Tweets for a Smile</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-pop-8frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Pop 8FRP Lock</u></a></li>
<li><a href="https://fox-zero.techidaily.com/seamless-integration-top-3-methods-for-connecting-your-iphone-with-microsoft-outlook/"><u>Seamless Integration: Top 3 Methods for Connecting Your iPhone with Microsoft Outlook</u></a></li>
</ul></div>


---
title: Reinstating Backup Settings to Default in Windows
date: 2024-09-28T23:14:21.792Z
updated: 2024-10-03T18:50:51.628Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Backup Settings to Default in Windows
excerpt: This Article Describes Reinstating Backup Settings to Default in Windows
keywords: Default Backup Restore,WinXP Backup Default,Windows Safety Default,Save System Backups,Default Data Recovery,Restore Win Settings,XP Security Reboot
thumbnail: https://thmb.techidaily.com/0ad1f89069cff4b2779ade10913206262c7bed58531552359326ac17834a5d8d.jpg
---

## Reinstating Backup Settings to Default in Windows

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-highly-effective-ways-to-stream-and-record-sports-games/"><u>[New] 2024 Approved Highly Effective Ways to Stream and Record Sports Games</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-essential-strategies-for-iosandroid-streamers-on-facebook/"><u>[New] In 2024, Essential Strategies for iOS/Android Streamers on Facebook</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-key-to-effective-instagram-chats-a-comprehensive-guide-for-2024/"><u>[New] The Key to Effective Instagram Chats A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-apex-chart-analyst-master-video-popularity/"><u>[Updated] In 2024, Apex Chart Analyst Master Video Popularity</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-m1-explored-apples-leap-in-computational-innovation/"><u>[Updated] In 2024, M1 Explored Apple's Leap in Computational Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-hardware-reserved-memory-on-windows-platforms/"><u>Dissecting Hardware Reserved Memory on Windows Platforms</u></a></li>
<li><a href="https://extra-information.techidaily.com/easier-than-ever-accessing-ifunnys-memetic-delights/"><u>Easier Than Ever Accessing iFunny’s Memetic Delights</u></a></li>
<li><a href="https://win11.techidaily.com/examining-energy-demand-in-your-windows-based-computer/"><u>Examining Energy Demand in Your Windows-Based Computer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-merge-emulated-games-into-playnite-windows-edition/"><u>How to Merge Emulated Games Into Playnite Windows Edition</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-instant-images-guide-easy-recording-tips-dell/"><u>In 2024, Instant Images Guide Easy Recording Tips (Dell)</u></a></li>
<li><a href="https://buynow-help.techidaily.com/oculus-quest-2-vr-headset-overview-superior-immersive-experience-for-a-great-deal-our-expert-review/"><u>Oculus Quest 2 VR Headset Overview: Superior Immersive Experience for a Great Deal - Our Expert Review</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-the-mysterious-c0000005-issue-on-pcs/"><u>Quick Fixes for the Mysterious C0000005 Issue on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-quality-control-overcoming-common-freezes-in-wwe/"><u>Quick Quality Control: Overcoming Common Freezes in WWE</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-hidden-windows-tips-for-10-and-11-pcs/"><u>Reclaim Your Hidden Windows: Tips for 10 & 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-active-workflows-for-office-365outlook-mail/"><u>Reinstating Active Workflows for Office 365/Outlook Mail</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/see-it-all-your-free-selection-of-50-youtube-banners-for-2024/"><u>See It All - Your Free Selection of 50 YouTube Banners for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-teammers-screens-not-showing/"><u>Tackle Teammers' Screens Not Showing</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-worst-js-error-on-discord-specifically-for-windows-users/"><u>Tackling the Worst JS Error on Discord, Specifically for Windows Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-implications-of-the-european-unions-ai-regulation-on-tools-like-chatgpt/"><u>Understanding the Implications of the European Union's AI Regulation on Tools Like ChatGPT</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
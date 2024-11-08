---
title: How to Reset Windows Backup to Its Defaults
date: 2024-11-04T21:34:14.784Z
updated: 2024-11-07T23:49:45.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset Windows Backup to Its Defaults
excerpt: This Article Describes How to Reset Windows Backup to Its Defaults
keywords: Reset Windows Backup,Backup Settings Restore,Windows Default Backup,Default Windows Backup,Reset Backup Procedure,Change Backup Options,Windows Backup Recovery
thumbnail: https://thmb.techidaily.com/9dde14122d86332e2939d12b71c8c112849e5b475313180be25192ee619462eb.jpg
---

## How to Reset Windows Backup to Its Defaults

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135395/19272" target="_top" id="2135395">
  <img src="//a.impactradius-go.com/display-ad/19272-2135395" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135395/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-the-importance-of-non-primary-footage-in-editing/"><u>[New] 2024 Approved The Importance of Non-Primary Footage in Editing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unseen-snaps-and-hushed-user-signal-to-check-for-blocks/"><u>[New] Unseen Snaps and Hushed User Signal to Check for Blocks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-explore-8plus-places-for-gratis-hdr-environments-and-clips/"><u>[Updated] 2024 Approved Explore 8+ Places for Gratis HDR Environments & Clips</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/cutting-edge-cost-effective-risc-v-laptop-by-chinese-startup-for-developer-professionals-only-300/"><u>Cutting-Edge, Cost-Effective RISC-V Laptop by Chinese Startup for Developer Professionals – Only $300</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-seamless-dolby-atmos-setup-in-your-pc/"><u>Expert Tips for Seamless Dolby Atmos Setup in Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-wallpaper-image-storage-on-windows-11/"><u>Exploring Wallpaper Image Storage on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/free-online-conversion-changing-aac-audio-files-into-flac-format-movavi/"><u>Free Online Conversion: Changing AAC Audio Files Into FLAC Format - Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>How to Address Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-tecno-spark-10-5g-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Tecno Spark 10 5G</u></a></li>
<li><a href="https://win11.techidaily.com/increase-productivity-hotkey-hacks-on-your-mouse/"><u>Increase Productivity: Hotkey Hacks on Your Mouse</u></a></li>
<li><a href="https://win11.techidaily.com/master-github-desktop-usage-for-effective-windows-devops/"><u>Master GitHub Desktop Usage for Effective Windows DevOps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-use-of-microsofts-security-tool-canary/"><u>Mastering the Use of Microsoft's Security Tool Canary</u></a></li>
<li><a href="https://win11.techidaily.com/new-to-windows-learn-basic-accessibility-tools/"><u>New to Windows? Learn Basic Accessibility Tools</u></a></li>
<li><a href="https://facebook.techidaily.com/preserving-page-harmony-the-art-of-excluding-profiles/"><u>Preserving Page Harmony: The Art of Excluding Profiles</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-guide-to-finding-exceptional-pexels-visuals-for-2024/"><u>Quick Guide to Finding Exceptional Pexels Visuals for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/role-of-coast-guards-in-monitoring-vmsais-discuss-how-coast-guard-authorities-use-this-information-to-monitor-maritime-traffic-ensure-compliance-with-intern201/"><u>Role of Coast Guards in Monitoring VMS/AIS: Discuss How Coast Guard Authorities Use This Information to Monitor Maritime Traffic, Ensure Compliance with International Regulations, Detect Anomalies, and Respond Effectively to Emergencies or Threats</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-excel-opening-issue-with-notepad-windows/"><u>Troubleshoot: Excel Opening Issue with Notepad Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-fixing-microphone-issues-on-razer-barracuda-x-laptop-windows-11-and-10-solutions/"><u>Troubleshooting Steps: Fixing Microphone Issues on Razer Barracuda X Laptop – Windows 11 & 10 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-mastering-the-removal-of-error-3-from-nvidia-opengl/"><u>Win10/11: Mastering the Removal of Error 3 From Nvidia OpenGL</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
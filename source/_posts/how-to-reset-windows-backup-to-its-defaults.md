---
title: How to Reset Windows Backup to Its Defaults
date: 2024-11-15T23:50:01.214Z
updated: 2024-11-18T08:18:25.415Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
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

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-in-2024-core-principles-for-online-storytelling-craftsmanship/"><u>[New] In 2024, Core Principles for Online Storytelling Craftsmanship</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-finding-voice-changers-for-vtubers-two-best-app-recommended/"><u>[Updated] Finding Voice Changers for Vtubers Two Best App Recommended</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ge-gain-for-youtubers-per-ad-exposure/"><u>Average Gain for YouTubers per Ad Exposure?</u></a></li>
<li><a href="https://win11.techidaily.com/essential-strategies-to-replace-windows-ls-with-file-explorer/"><u>Essential Strategies to Replace Windows' LS with File Explorer</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-ai-limitations-with-gpt-3/"><u>Exploring AI Limitations with GPT-3</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-gateway-to-managing-printers-in-windows/"><u>Exploring the Gateway to Managing Printers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-empty-folder-problems-in-win11-and-11-error-0x80070091/"><u>How to Fix Empty Folder Problems in Win11 & 11 Error #0X80070091</u></a></li>
<li><a href="https://tech-haven.techidaily.com/language-logic-loops-le-chat-ai-meets-chatgpt/"><u>Language Logic Loops: Le Chat AI Meets ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-taskbar-time-displays-in-win-11/"><u>Personalizing Taskbar Time Displays in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalized-lock-patterns-in-windows-11-devices/"><u>Step-by-Step Guide to Personalized Lock Patterns in Windows 11 Devices</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/athway-to-smart-youtube-frames-free-methods-inside/"><u>The Pathway to Smart YouTube Frames (Free Methods Inside!)</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-upgrades-fast-start-up-of-rdc-version-11/"><u>Top Windows Upgrades: Fast Start-Up of RDC, Version 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-narrative-expertise-a-guide-on-leveraging-chatgpt-for-superior-story-craft/"><u>Unlocking Narrative Expertise: A Guide on Leveraging ChatGPT for Superior Story Craft</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-flip-spin-and-rotate-top-10-free-video-editing-software/"><u>Updated Flip, Spin, and Rotate Top 10 Free Video Editing Software</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-the-comprehensive-tools-of-microsoft-store-themes/"><u>Utilizing the Comprehensive Tools of Microsoft Store Themes</u></a></li>
</ul></div>


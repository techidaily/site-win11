---
title: Regaining the Basics of Windows Backup Configurations
date: 2025-01-27T19:07:06.112Z
updated: 2025-02-04T03:08:47.921Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining the Basics of Windows Backup Configurations
excerpt: This Article Describes Regaining the Basics of Windows Backup Configurations
keywords: Windows Backup Guide,Basic Backup Steps,Restore System Files,Backup Settings Overview,Save Data Safely,Windows Recovery Options,Configuring File Protection
thumbnail: https://thmb.techidaily.com/9416939e5407a18ea81200cd7e119e61ff04e31fb3c5cd004cd4601ad28e3eb8.jpg
---

## Regaining the Basics of Windows Backup Configurations

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-a-framework-for-employing-videos-in-educational-settings-for-2024/"><u>[New] A Framework for Employing Videos in Educational Settings for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-smooth-video-viewing-experience-enabledisable-pip-for-iphone-youtube/"><u>[New] In 2024, Smooth Video Viewing Experience Enable/Disable PIP for iPhone YouTube</u></a></li>
<li><a href="https://article-files.techidaily.com/new-unlocking-mp3-from-pinterest-video-files-with-these-steps/"><u>[New] Unlocking MP3 From Pinterest Video Files with These Steps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-perfecting-profile-playlists-on-facebook-through-mobile/"><u>[Updated] 2024 Approved Perfecting Profile Playlists on Facebook Through Mobile</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-explore-popular-youtube-comment-sections-for-2024/"><u>[Updated] Explore Popular YouTube Comment Sections for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-easy-way-to-spruce-up-your-youtube-feedback-with-emojis/"><u>[Updated] The Easy Way to Spruce Up Your YouTube Feedback with Emojis</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-the-ultimate-guide-to-productive-online-team-sessions/"><u>2024 Approved The Ultimate Guide to Productive Online Team Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/disentangling-steam-timeout-problems-on-windows-with-rust-techniques/"><u>Disentangling Steam Timeout Problems on Windows with Rust Techniques</u></a></li>
<li><a href="https://article-tips.techidaily.com/echoes-of-music-in-video-landscapes/"><u>Echoes of Music in Video Landscapes</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-security-posture-adding-passwords-to-text-files/"><u>Elevating Your Security Posture: Adding Passwords to Text Files</u></a></li>
<li><a href="https://win11.techidaily.com/making-win1011-recycle-bin-error-free-quick-solutions/"><u>Making Win10/11 Recycle Bin Error-Free: Quick Solutions</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-stability-for-age-of-ashes-how-to-prevent-unwanted-pc-crashes/"><u>Mastering Stability for 'Age of Ashes': How to Prevent Unwanted PC Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/sleek-software-not-so-slick-the-throttling-of-your-pcs-speed/"><u>Sleek Software, Not So Slick: The Throttling of Your PC's Speed</u></a></li>
<li><a href="https://win11.techidaily.com/synergizing-technology-the-role-of-ai-in-windows-11-dynamics/"><u>Synergizing Technology: The Role of AI in Windows 11 Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-fixing-screen-alignment-in-windows-os/"><u>Tips for Fixing Screen Alignment in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-future-on-windows-empower-your-pc-with-vivetool/"><u>Unlocking the Future on Windows: Empower Your PC with ViVeTool</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-personalized-audio-settings-key-combinations-explained/"><u>Win11's Personalized Audio Settings: Key Combinations Explained</u></a></li>
</ul></div>


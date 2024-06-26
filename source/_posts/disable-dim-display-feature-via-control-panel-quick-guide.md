---
title: Disable Dim Display Feature via Control Panel Quick Guide
date: 2024-06-25T11:41:29.784Z
updated: 2024-06-26T11:41:29.784Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Dim Display Feature via Control Panel Quick Guide
excerpt: This Article Describes Disable Dim Display Feature via Control Panel Quick Guide
keywords: Disable Screen Low Brightness,Control Panel Light Adjustment,Reduce Display Intensity,Simple Dark Mode Turn-Off,Quick Control Panel Guide,Dim Settings Deactivation,High Contrast Display Options
thumbnail: https://thmb.techidaily.com/481d06bf1b3256f57ab62815340fcc460dfe18ec5f4531d4ca28b88dc8e90d86.jpg
---

## Disable Dim Display Feature via Control Panel Quick Guide

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/troubleshooting-error-malwarebytes-cant-properly-called-proc/"><u>Troubleshooting Error: Malwarebytes Can't Properly Called Proc</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/make-ms-word-defaultly-use-reading-pane-for-email-attachments-no-editing/"><u>Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-hurdles-4-tips-for-better-windows-ram/"><u>Overcoming Memory Hurdles: 4 Tips for Better Windows RAM</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-uncover-hidden-system-startups/"><u>Tips to Uncover Hidden System Startups</u></a></li>
<li><a href="https://win11.techidaily.com/how-are-c-and-d-drive-identities-unique/"><u>How Are C: And D: Drive Identities Unique?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ideo-venture-a-vloggers-journey-to-judicious-gains-for-2024/"><u>The Video Venture  A Vlogger's Journey to Judicious Gains for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-ultimate-list-of-free-avi-video-rotators-for-all-devices/"><u>Updated The Ultimate List of Free AVI Video Rotators for All Devices</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-ultimate-list-10-video-editing-apps-for-kids-both-free-and-paid/"><u>Updated 2024 Approved The Ultimate List 10 Video Editing Apps for Kids, Both Free and Paid</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-how-to-recognize-songs-on-iphone/"><u>Updated How to Recognize Songs on iPhone?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-video-repair-tool-to-fix-and-repair-corrupt-mp4movavi-video-files-of-c22-by-stellar-video-repair-mobile-video-repair/"><u>Best Video Repair tool to Fix and Repair Corrupt MP4,MOV,AVI video files of C22</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-unlocking-perfect-proportions-picture-ratio-calculator-explained/"><u>Updated 2024 Approved Unlocking Perfect Proportions Picture Ratio Calculator Explained</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-learn-to-capture-videos-from-webcam-in-vlc/"><u>[Updated] Learn to Capture Videos From Webcam in VLC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-essential-guide-to-posting-vimeo-on-instagram-for-2024/"><u>[Updated] The Essential Guide to Posting Vimeo on Instagram for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-mastering-the-social-media-puzzle-decoding-ig-data-for-enhanced-campaigns/"><u>[New] 2024 Approved  Mastering the Social Media Puzzle  Decoding IG Data for Enhanced Campaigns</u></a></li>
</ul></div>

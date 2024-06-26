---
title: Changing Windows Read-Only Settings Easily
date: 2024-06-25T10:17:03.709Z
updated: 2024-06-26T10:17:03.709Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Windows Read-Only Settings Easily
excerpt: This Article Describes Changing Windows Read-Only Settings Easily
keywords: Change ReRead Only WinSettings,Simplify WinReadModify,EasyWinRWControlToggle,AlterWindowsReadLock,UnlockReadOnlyFileWin,TweakWindowsLockedFiles,EnableEditReadFilesWin
thumbnail: https://thmb.techidaily.com/bf32c159170edbc355c721b22ee8ee6c67dda36feed408fdb0ec7f3ca8b4ddc2.jpg
---

## Changing Windows Read-Only Settings Easily

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://win11.techidaily.com/key-considerations-when-shopping-for-a-windows-device/"><u>Key Considerations When Shopping for a Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience/"><u>7 Proven Methods to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/shrouded-functionality-unveiling-hidden-context-menus-in-win11/"><u>Shrouded Functionality: Unveiling Hidden Context Menus in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-windows-11s-8-confusing-features/"><u>A Deep Dive Into Windows 11’S 8 Confusing Features</u></a></li>
<li><a href="https://win11.techidaily.com/windows-pathways-three-keys-to-gaming-files/"><u>Windows Pathways: Three Keys to Gaming Files</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-pick-prime-photo-organizers-for-windows/"><u>Excellent Pick: Prime Photo Organizers For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unlinked-files-and-absence-of-assigned-apps-win/"><u>Resolving Unlinked Files and Absence of Assigned Apps (Win)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-10-ubuntu-screen-recorders/"><u>[Updated] Top 10 Ubuntu Screen Recorders</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-expert-guide-to-pixlr-edits-top-15-tricks-for-perfection/"><u>[New] Expert Guide to Pixlr Edits  Top 15 Tricks for Perfection</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-quick-guide-to-purging-watched-youtube-videos/"><u>[New] In 2024, A Quick Guide to Purging Watched YouTube Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-smart-strategies-for-buying-economical-gopros/"><u>In 2024, Smart Strategies for Buying Economical GoPros</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-your-videos-with-these-proven-seo-tools-for-more-clicks/"><u>Elevate Your Videos with These Proven SEO Tools for More Clicks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unidentified-user-strategies-for-accessing-instagram-stories-on-desktopmobile/"><u>Unidentified User Strategies for Accessing Instagram Stories on Desktop/Mobile</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-engaging-video-teasers-for-youtube-success-for-2024/"><u>[New] Crafting Engaging Video Teasers for YouTube Success for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-decision-time-choose-your-dream-video-editor-filmora-or-democracy-creator/"><u>[New] 2024 Approved  Decision Time! Choose Your Dream Video Editor (Filmora or Democracy Creator)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/your-ultimate-guide-to-unmissable-gaming-worlds/"><u>Your Ultimate Guide to Unmissable Gaming Worlds</u></a></li>
</ul></div>

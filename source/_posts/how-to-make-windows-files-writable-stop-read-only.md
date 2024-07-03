---
title: "How to Make Windows Files Writable: Stop Read-Only"
date: 2024-06-25T11:28:26.608Z
updated: 2024-06-26T11:28:26.608Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Make Windows Files Writable: Stop Read-Only"
excerpt: "This Article Describes How to Make Windows Files Writable: Stop Read-Only"
keywords: Windows File Changes,Disable RWY Mode,Stop Read-Only,File Permissions Update,Editing Files Access,Override Read-Only,Write Protect Remove
thumbnail: https://thmb.techidaily.com/be8ed6a4e78ad75b0aa927e5deab19fb5e1ff02b9f258c0a63e3b6ef48739db7.jpg
---

## How to Make Windows Files Writable: Stop Read-Only

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
<li><a href="https://win11.techidaily.com/determining-optimal-nvidia-driver-gamingstudio-edition/"><u>Determining Optimal Nvidia Driver: Gaming/Studio Edition</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unresponsive-task-issues-in-windows-os/"><u>Addressing 'Unresponsive Task' Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-connectivity-windows-plus-playstation-3-pad/"><u>Effortless Connectivity: Windows + PlayStation 3 Pad</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-windows-activation-error-0x8007251d-and-how-do-you-fix-it/"><u>What Is the Windows Activation Error 0X8007251D and How Do You Fix It?</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-read-only-mode-on-windows-folders/"><u>Preventing Read-Only Mode on Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-pc-performance-installing-easy-to-use-enhancement-tool-for-windows/"><u>Maximizing PC Performance: Installing Easy-to-Use Enhancement Tool for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-not-writable-file-problems-in-windows-11/"><u>Solutions for Not Writable File Problems in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-layer-audio-onto-video-clips-in-premiere-pro/"><u>2024 Approved  Layer Audio Onto Video Clips in Premiere Pro</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-vivo-y100i-power-5g-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Vivo Y100i Power 5G Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-to-video-dimensions-on-the-yt-platform/"><u>[Updated] The Ultimate Guide to Video Dimensions on the YT Platform</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-guide-20-incredible-no-cost-storage-platforms-1tbplus/"><u>Ultimate Guide  20 Incredible No-Cost Storage Platforms (1TB+)</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-add-green-screen-effects-in-phhotoshop-for-2024/"><u>How to Add Green Screen Effects In Phhotoshop for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-instant-access-extract-and-save-fb-videos-as-mp4s/"><u>[Updated] Instant Access  Extract and Save FB Videos as MP4s</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-this-article-introduces-how-sheila-become-a-youtuber-and-how-she-started-video-editing/"><u>Updated In 2024, This Article Introduces How Sheila Become a Youtuber and How She Started Video Editing</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-screen-record-with-ease-top-10-webcam-software-for-windows-10/"><u>Updated 2024 Approved Screen Record with Ease Top 10 Webcam Software for Windows 10</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-oneplus-11-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-honor-x50-gt-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Honor X50 GT Quickly | Dr.fone</u></a></li>
</ul></div>

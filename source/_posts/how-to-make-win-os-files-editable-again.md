---
title: How to Make Win OS Files Editable Again
date: 2024-06-25T10:08:09.291Z
updated: 2024-06-26T10:08:09.291Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make Win OS Files Editable Again
excerpt: This Article Describes How to Make Win OS Files Editable Again
keywords: Restore Win File Permissions,Editing Windows Files,Regain File Accessibility,Overcoming Read-Only Errors,Modify WinOS Documents,Unlock OS File Lock,Change Read-Only Windows Files
thumbnail: https://thmb.techidaily.com/b43da9b8fec14dde01c0becd6729005fd0db59f099a461c4a5b1f228776ffdea.jpg
---

## How to Make Win OS Files Editable Again

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
<li><a href="https://win11.techidaily.com/resolving-windows-11-error-code-0x0000011b/"><u>Resolving Windows 11 Error Code: 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-captures-snip-tool-versus-prtsc/"><u>Mastering Windows Captures: Snip Tool versus PrtSc</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-down-your-laptop-keyboard-with-simple-steps-in-win10win11/"><u>Quiet Down Your Laptop Keyboard with Simple Steps in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pcs-safety-with-these-7-password-generators/"><u>Boost Your PC's Safety with These 7 Password Generators</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-desktop-menus-in-win-1011/"><u>Troubleshooting Non-Responsive Desktop Menus in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/merging-windows-credentials-with-microsoft-identity-hub/"><u>Merging Windows Credentials with Microsoft Identity Hub</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-11s-security-and-credentials-panel/"><u>Guide to Windows 11'S Security & Credentials Panel</u></a></li>
<li><a href="https://win11.techidaily.com/unrestricted-windows-dialogue-embrace-freedomgpt/"><u>Unrestricted Windows Dialogue: Embrace FreedomGPT</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-c53-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from C53.</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-metaverse-unraveled-explore-these-6-vivid-models/"><u>In 2024, The Metaverse Unraveled  Explore These 6 Vivid Models</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-cheerful-footage-extractor-analysis/"><u>In 2024, Cheerful Footage Extractor Analysis</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-video-editing-on-windows-11-for-professionals/"><u>[New] Unlocking Video Editing on Windows 11 for Professionals</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-tailoring-your-viewing-experience-with-youtube-tv/"><u>[New] Tailoring Your Viewing Experience with YouTube TV</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-vivo-x100-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Vivo X100 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-integrating-social-features-for-playlist-dissemination/"><u>2024 Approved  Integrating Social Features for Playlist Dissemination</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-ultimate-nintendo-switch-fighter-showcase-max-156-for-2024/"><u>[Updated] Ultimate Nintendo Switch Fighter Showcase (Max 156) for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-gallery-archive-websites/"><u>In 2024, Best Gallery Archive Websites</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-fresh-alternative-films-to-dive-into-7-favorites/"><u>[Updated] 2024 Approved  Fresh Alternative Films to Dive Into, #7 Favorites</u></a></li>
</ul></div>

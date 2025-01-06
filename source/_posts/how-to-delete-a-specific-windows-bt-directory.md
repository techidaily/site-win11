---
title: How to Delete a Specific Windows ~BT Directory
date: 2025-01-03T17:51:16.993Z
updated: 2025-01-06T19:33:39.150Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Delete a Specific Windows ~BT Directory
excerpt: This Article Describes How to Delete a Specific Windows ~BT Directory
keywords: Delete WinDirs,Remove BT Folder,Uninstall BT Directories,Clear BT Settings,Delete Bing Toolbar,Erase Windows BT Path,Remove Microsoft BT
thumbnail: https://thmb.techidaily.com/04715cc01635128f130003aeefa217d9440724157165604a4668d27f41792057.jpeg
---

## How to Delete a Specific Windows ~BT Directory

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-skype-groups-setting-up-windowsmac-conversations/"><u>[New] Skype Groups Setting Up Windows/Mac Conversations</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-stop-screen-blackouts-with-obs-game-recordings/"><u>[New] Stop Screen Blackouts with OBS Game Recordings</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/apowersofts-technology-insightfully-analyzed-with-comparisons/"><u>Apowersoft's Technology Insightfully Analyzed with Comparisons</u></a></li>
<li><a href="https://win-howtos.techidaily.com/defeating-the-notorious-0x80070490-error-in-windows-updates-with-ease/"><u>Defeating the Notorious 0X80070490 Error in Windows Updates with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-windows-canary-vulnerability-alerts/"><u>Demystifying the Windows Canary Vulnerability Alerts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/guia-eficaz-para-realizar-copias-de-seguridad-en-formato-dvd-y-iso-con-winx-dvd-copy/"><u>Guía Eficaz Para Realizar Copias De Seguridad en Formato DVD Y ISO Con WinX DVD Copy</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-6-plus-passcode-without-computer-by-drfone-ios/"><u>How to Unlock Apple iPhone 6 Plus Passcode without Computer?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-your-gamer-goals-intact-a-guide-to-epic-saves/"><u>Keeping Your Gamer Goals Intact: A Guide to Epic Saves</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-seamless-file-downloads-in-windows-11/"><u>Re-Establishing Seamless File Downloads in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-camera-not-found-on-win11-a-step-by-step-guide/"><u>Resolving Camera Not Found on Win11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-able.techidaily.com/reviving-audio-in-your-fallout-adventure-steps-to-restore-sounds-in-pc-version/"><u>Reviving Audio in Your Fallout Adventure: Steps to Restore Sounds in PC Version</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-infinix-smart-7-hd-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Infinix Smart 7 HD</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-read-only-reverting-in-file-systems/"><u>Troubleshooting Read-Only Reverting in File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-policies-on-windows-discover-3-vital-approaches/"><u>Unlock Policies on Windows: Discover 3 Vital Approaches</u></a></li>
</ul></div>


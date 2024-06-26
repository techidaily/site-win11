---
title: Understanding Windows ~BT Folder Functionality
date: 2024-06-25T11:40:36.797Z
updated: 2024-06-26T11:40:36.797Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding Windows ~BT Folder Functionality
excerpt: This Article Describes Understanding Windows ~BT Folder Functionality
keywords: BT Folder Use,Windows BT Features,BT Connectivity,BT File Sharing,Windows BT Integration,BT Signal Support,WinBT Functionality
thumbnail: https://thmb.techidaily.com/f49bc8cad6beb9dab5f0418b9b2ef89c1f57811a05de89bd7149842bbd8e67a6.jpg
---

## Understanding Windows ~BT Folder Functionality

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

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

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigate-and-fine-tune-windows-with-ease-using-alomware-suite/"><u>Navigate & Fine-Tune Windows with Ease Using AlomWare Suite</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-the-speedy-support-function-of-w11/"><u>Beginning the Speedy Support Function of W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-clarity-manage-all-open-windows-win1110/"><u>From Chaos to Clarity: Manage All Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-freeze-in-epic-games-launcher-on-pcs/"><u>Preventing Freeze in Epic Games Launcher on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-ntoskrnlexe-process/"><u>Tackling Excessive Ntoskrnl.exe Process</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-measures-to-mend-ms-store-malfunctions-in-windows-os/"><u>Masterful Measures to Mend MS Store Malfunctions in Windows OS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unveiling-youtubes-monthly-monetization-rules/"><u>In 2024, Unveiling YouTube’s Monthly Monetization Rules</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-vocalizing-text-pioneering-audio-to-written-content-conversion-for-2024/"><u>Updated Vocalizing Text Pioneering Audio to Written Content Conversion for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Poco X6 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hidden-echoes-to-silence-audacitys-technique-guide/"><u>In 2024, Hidden Echoes to Silence  Audacity's Technique Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-mastering-your-content-on-vimeo-free-plus-or-pro/"><u>[Updated] Mastering Your Content on Vimeo  Free, Plus or Pro?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-create-a-powerpoint-looping-slideshow-for-2024/"><u>Updated How to Create a PowerPoint Looping Slideshow for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-tech-gadgets-for-effortless-virtual-meetings-capture/"><u>[Updated] Top Tech Gadgets for Effortless Virtual Meetings Capture</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-oneplus-ace-2v-unlock-without-password-by-drfone-android/"><u>5 Solutions For OnePlus Ace 2V Unlock Without Password</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
---
title: Exploring the Role of Windows ~BT Directories in OS
date: 2024-09-15T03:14:10.803Z
updated: 2024-09-16T20:43:20.507Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring the Role of Windows ~BT Directories in OS
excerpt: This Article Describes Exploring the Role of Windows ~BT Directories in OS
keywords: Windows BT Folder Guide,Operating System Windows,BT Directory Functions,OS Window Integration,Windows BT File Paths,BT Directories in OS,Windows OS Configuration
thumbnail: https://thmb.techidaily.com/14ec62870ba2076f7e8c9687f751c49a66df2b130718dc75492a59a5c4cfcb22.jpg
---

## Exploring the Role of Windows ~BT Directories in OS

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-vlc-screen-recorder-review-and-using-guide/"><u>[New] 2024 Approved VLC Screen Recorder Review and Using Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-effective-techniques-for-screen-display-on-google-meet/"><u>[Updated] In 2024, Effective Techniques for Screen Display on Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/playstation/"><u>「PlayStationのロイロゲームレコーダー使い方：詳細ガイド」</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cost-effective-sky-gadgets-frugal-flight-devices-ranking-for-2024/"><u>Cost-Effective Sky Gadgets Frugal Flight Devices Ranking for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/ideal-display-options-for-an-enhanced-experience-on-ps5-and-xbox-series-sx/"><u>Ideal Display Options for an Enhanced Experience on PS5 and Xbox Series S/X</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-vivo-y78plus-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Vivo Y78+? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-asf-compatibility-issues-in-windows-media-player-comprehensive-guide-and-fixes-inside/"><u>Overcoming ASF Compatibility Issues in Windows Media Player – Comprehensive Guide & Fixes Inside!</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-ways-disabling-closed-captions-in-vlc-player-top-3-methods/"><u>Quick & Easy Ways: Disabling Closed Captions in VLC Player - Top 3 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-audio-extraction-from-dvds-speedy-software-solutions/"><u>Quick Guide to Audio Extraction From DVDs - Speedy Software Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/record-voice-clips-using-windows-snipping-tool-a-complete-explanation/"><u>Record Voice Clips Using Windows' Snipping Tool - A Complete Explanation!</u></a></li>
<li><a href="https://win11.techidaily.com/simple-tricks-effective-methods-to-reduce-email-attachments-by-compressing-videos/"><u>Simple Tricks: Effective Methods to Reduce Email Attachments by Compressing Videos</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-miracast-connection-issues-on-windows-11-setup-and-fixes-explored/"><u>Solving Miracast Connection Issues on Windows 11 - Setup & Fixes Explored</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/yts-game-changers-the-elite-ladies-in-gaming-for-2024/"><u>YT's Game Changers The Elite Ladies in Gaming for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


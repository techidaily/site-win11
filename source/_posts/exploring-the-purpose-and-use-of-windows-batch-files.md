---
title: Exploring the Purpose & Use of Windows Batch Files
date: 2024-10-02T19:38:38.923Z
updated: 2024-10-04T00:50:19.051Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring the Purpose & Use of Windows Batch Files
excerpt: This Article Describes Exploring the Purpose & Use of Windows Batch Files
keywords: Batch File Basics,Scripting in Windows,Batch Command Utility,Windows Automation Scripts,Executing Commands Task-Wise,Batch Files Purpose Explored,Windows Batch Script Functions
thumbnail: https://thmb.techidaily.com/e0d972d2fcbdfdcba3e132e48f8036c4f80fa7e20c32444994977f3585d2732d.jpeg
---

## Exploring the Purpose & Use of Windows Batch Files

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-guiding-you-to-enable-auto-video-feature-on-facebook/"><u>[New] Guiding You to Enable Auto-Video Feature on Facebook</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-ideal-free-webcam-video-grabber-solution/"><u>[New] Ideal Free Webcam Video Grabber Solution</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-troubleshoot-facebook-live-pause-strategies-for-smooth-broadcasts/"><u>2024 Approved Troubleshoot Facebook Live Pause Strategies for Smooth Broadcasts</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/discover-the-top-trending-iphone-apps-in-depth-reviews-and-analysis/"><u>Discover the Top-Trending iPhone Apps In-Depth Reviews and Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/discover-windows-11s-data-extraction-tactics/"><u>Discover Windows 11'S Data Extraction Tactics</u></a></li>
<li><a href="https://games-able.techidaily.com/efficient-screen-capturing-for-gaming-enthusiasts/"><u>Efficient Screen Capturing for Gaming Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-license-termination-alert-in-windows-1011/"><u>Eliminating License Termination Alert in Windows 10/11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-nokia-c12-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Nokia C12 Pattern Lock Screen</u></a></li>
<li><a href="https://facebook.techidaily.com/highlighting-googles-influential-2022-news/"><u>Highlighting Google's Influential 2022 News</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-poco-x5-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Poco X5 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unknown-disk-troubles-in-windows-xpvista78/"><u>Overcoming Unknown Disk Troubles in Windows XP/Vista/7/8</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-admin-restricted-security-error/"><u>Overcoming Windows: Admin-Restricted Security Error</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-seamless-icons-on-pcs/"><u>The Key to Seamless Icons on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-activate-audio-during-powerpoint-video-captures/"><u>Tips to Activate Audio During PowerPoint Video Captures</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-windows-compatible-bittorrent-apps/"><u>Top 5 Windows-Compatible BitTorrent Apps</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-pagefilesys-role-in-windows-os/"><u>Understanding Pagefile.sys Role in Windows OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
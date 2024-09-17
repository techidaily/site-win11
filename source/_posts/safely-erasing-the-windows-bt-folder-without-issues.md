---
title: Safely Erasing the Windows ~BT Folder Without Issues
date: 2024-09-15T21:04:18.778Z
updated: 2024-09-17T10:04:08.335Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Safely Erasing the Windows ~BT Folder Without Issues
excerpt: This Article Describes Safely Erasing the Windows ~BT Folder Without Issues
keywords: Secure BT File Removal,Safe Windows BT Deletion,Erase BT Files Safely,Clean BT Folder Windows,Untroubled BT File Erase,Safe BT Deletion Guide,Trusted BT Folder Remove
thumbnail: https://thmb.techidaily.com/4bc09bf00dd16476adc7181e127ad6390edb7499dd05b4708d5bc6f8d46016ec.png
---

## Safely Erasing the Windows ~BT Folder Without Issues

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-add-background-scores-via-premiere-pro-for-2024/"><u>[New] Add Background Scores via Premiere Pro for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-leverage-both-platforms-youtube-and-facebook-integration-for-2024/"><u>[Updated] Leverage Both Platforms YouTube and Facebook Integration for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-proscreencapture-ultimate-edition-for-2024/"><u>[Updated] ProScreenCapture Ultimate Edition for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-the-ultimate-io-scanner-insiders-handbook-for-2024/"><u>[Updated] The Ultimate IO Scanner Insider's Handbook for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-realme-10t-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/get-direct-access-to-your-assistive-tools-in-windows/"><u>Get Direct Access to Your Assistive Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-conjure-imagination-in-ai-art-forms-using-paint-cocreator-and-windows-11/"><u>How to Conjure Imagination in AI Art Forms Using Paint Cocreator and Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transforming-ideas-into-impactful-scenes-through-dialogue/"><u>In 2024, Transforming Ideas Into Impactful Scenes Through Dialogue</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-virtualization-hyper-v-setup-for-win11/"><u>Mastering Virtualization: Hyper-V Setup for Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-steam-refund-policy-tips-for-getting-your-money-back-on-video-games/"><u>Navigating the Steam Refund Policy - Tips for Getting Your Money Back on Video Games</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-typical-anomalies-in-anydesk-for-windows/"><u>Navigating Through Typical Anomalies in AnyDesk for Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-avoiding-audible-distractions-silencing-audio-in-current-avi-updates/"><u>New Avoiding Audible Distractions Silencing Audio in Current AVI Updates</u></a></li>
<li><a href="https://win11.techidaily.com/shattering-the-scripts-off-glass-ceiling-in-powershell-execution/"><u>Shattering the 'Scripts Off' Glass Ceiling in PowerShell Execution</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/m-away-the-leading-online-video-havens-for-2024/"><u>Stream Away The Leading Online Video Havens for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-windows-11-search-with-these-top-tips/"><u>Supercharge Your Windows 11 Search with These Top Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11-navigating-mac-retrieval-methods/"><u>Unveiling Windows 11: Navigating MAC Retrieval Methods</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


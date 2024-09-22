---
title: Safely Erasing the Windows ~BT Folder Without Issues
date: 2024-09-14T20:28:22.785Z
updated: 2024-09-22T09:34:58.513Z
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-professional-filmmakers-choices-17-best-lights/"><u>[New] 2024 Approved Professional Filmmakers' Choices #17 Best Lights</u></a></li>
<li><a href="https://win11.techidaily.com/1726028042871-pc/"><u>「動画へ簡単な音楽適用手引き - PC編集者のための完全マニュアル」</u></a></li>
<li><a href="https://win11.techidaily.com/1726027584681-2024/"><u>2024年のウィンドウズ環境における音声ファイルカットの一般的な手順</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-honor-play-7t-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Honor Play 7T Phone</u></a></li>
<li><a href="https://win11.techidaily.com/1726028053556-dvdmp3/"><u>生動画DVDからMP3ファイルへの変換技術</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionary-artificial-intelligence-transforming-diy-sector-the-arrival-of-gpt-4/"><u>Revolutionary Artificial Intelligence Transforming DIY Sector: The Arrival of GPT-4</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-ebook-purchasing-features-for-iphone-and-ipad-tips-using-the-books-app-by-apple/"><u>Unlocking eBook Purchasing Features for iPhone and iPad: Tips Using the Books App by Apple</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


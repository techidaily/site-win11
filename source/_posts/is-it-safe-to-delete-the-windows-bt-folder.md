---
title: Is It Safe to Delete the Windows ~BT Folder?
date: 2024-10-23T04:52:05.985Z
updated: 2024-10-26T17:48:17.259Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Is It Safe to Delete the Windows ~BT Folder?
excerpt: This Article Describes Is It Safe to Delete the Windows ~BT Folder?
keywords: BT Windows Safety Guide,Deleting Windows BT Risks,BT Data Security Windows,Windows BT Safe Removal,Safe Delete Windows BT Folder,Windows BT Protection,Eliminating BT
thumbnail: https://thmb.techidaily.com/4914ba55ffacf89f7eecf219812b0360d597ec64675cc9c86f982f27e5ed1c09.jpg
---

## Is It Safe to Delete the Windows ~BT Folder?

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
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-gaming-evolved-streaming-xbox-content-on-facebook/"><u>[Updated] 2024 Approved Gaming Evolved Streaming Xbox Content on Facebook</u></a></li>
<li><a href="https://tech-revival.techidaily.com/conversion-facile-et-sans-frais-de-dts-vers-mp3-en-ligne-via-la-solution-de-movavi/"><u>Conversion Facile Et Sans Frais De DTS Vers MP3 en Ligne via La Solution De Movavi</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/decoding-sound-quality-the-battle-of-flac-and-wav-formats-with-movavis-insightful-analysis/"><u>Decoding Sound Quality: The Battle of FLAC and WAV Formats with Movavi's Insightful Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-banish-windows-temp-files-for-good/"><u>Discover How to Banish Windows Temp Files for Good</u></a></li>
<li><a href="https://win11.techidaily.com/excellence-in-design-best-windows-laptops-for-24/"><u>Excellence in Design: Best Windows Laptops for '24</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-1-choice-easy-online-video-text-conversion/"><u>In 2024, 1 Choice Easy Online Video Text Conversion</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-samsung-galaxy-m14-4g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Samsung Galaxy M14 4G to Another | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-pro-level-mac-photo-tips-unveiling-five-expert-techniques/"><u>In 2024, Pro-Level Mac Photo Tips Unveiling Five Expert Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-mp3-conversion-transforming-digital-music-into-physical-form-using-windows-and-imgburn/"><u>Mastering MP3 Conversion: Transforming Digital Music Into Physical Form Using Windows & ImgBurn</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-nddrive-mapping-in-win11/"><u>Mastering NDDrive Mapping in Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-honor-play-7t-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Honor Play 7T</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-systems-task-handling-on-windows/"><u>Supercharge Your System's Task Handling on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-saver-duration-on-windows/"><u>Tailoring Screen Saver Duration on Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/tout-pour-transformer-vos-images-jpeg-en-tiff-gratuitement-en-ligne-movavi/"><u>Tout Pour Transformer Vos Images JPEG en TIFF Gratuitement en Ligne - Movavi</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
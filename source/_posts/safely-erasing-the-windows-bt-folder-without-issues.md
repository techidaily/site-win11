---
title: Safely Erasing the Windows ~BT Folder Without Issues
date: 2024-10-05T11:30:53.198Z
updated: 2024-10-09T10:04:32.160Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-2024-approved-exploring-the-best-free-and-paid-videomosaic-apps-for-android-enthusiasts/"><u>[New] 2024 Approved Exploring the Best Free & Paid Videomosaic Apps for Android Enthusiasts</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-ideal-screener-tech-elevating-your-youtube-presence/"><u>[New] 2024 Approved Ideal Screener Tech Elevating Your YouTube Presence</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-strategic-tips-to-enhance-your-gmeet-ppt-presentations-on-mobilelaptop/"><u>[New] 2024 Approved Strategic Tips to Enhance Your GMeet PPT Presentations on Mobile/Laptop</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-rapid-routines-saving-presentations-ppt-wise/"><u>[Updated] In 2024, Rapid Routines Saving Presentations PPT-Wise</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-top-15-cameras-excelling-in-live-streaming/"><u>[Updated] In 2024, Top 15 Cameras Excelling in Live Streaming</u></a></li>
<li><a href="https://screen-recording.techidaily.com/effective-ways-to-archive-webcam-discussions-for-2024/"><u>Effective Ways to Archive Webcam Discussions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-an-account-password-in-windows-11/"><u>How to Change an Account Password in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-failed-steam-ui-module-on-pc/"><u>How To Reset Failed Steam UI Module on PC</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-safety-and-security-extending-your-pin-length-on-win1111/"><u>Maximize Safety & Security: Extending Your PIN Length on Win11/11</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-xsb-fail-solutions-for-windows-woes/"><u>Skyrim XSB Fail: Solutions for Windows Woes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-tutorial-disabling-windows-10s-auto-updating-feature/"><u>Step-by-Step Tutorial: Disabling Windows 10'S Auto-Updating Feature</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-end-of-hacks-discovering-why-advanced-language-models-arent-easily-circumvented-anymore/"><u>The End of Hacks: Discovering Why Advanced Language Models Aren't Easily Circumvented Anymore</u></a></li>
<li><a href="https://win11.techidaily.com/winning-method-for-converting-your-mp3-library-into-audible-cds-via-imgburn/"><u>Winning Method for Converting Your Mp3 Library Into Audible CDs via ImgBurn</u></a></li>
</ul></div>


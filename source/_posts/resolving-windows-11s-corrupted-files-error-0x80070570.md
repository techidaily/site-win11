---
title: Resolving Windows 11'S Corrupted Files Error 0X80070570
date: 2024-12-12T11:26:35.028Z
updated: 2024-12-12T20:58:50.361Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Windows 11'S Corrupted Files Error 0X80070570
excerpt: This Article Describes Resolving Windows 11'S Corrupted Files Error 0X80070570
keywords: Windows 11 Corruption Fix,0X80070570 File Error,Win11 Error Repair,XT700 Error Resolution,0X700 Files Fixing Guide,0X8070570 Windows Troubleshooting,Corrupted Files in Win11
thumbnail: https://thmb.techidaily.com/63eaa39ba6f901f19dd5d6107e02d0bfc04195c0f440f8e4bb186694932a1b6e.jpg
---

## Resolving Windows 11'S Corrupted Files Error 0X80070570

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-peek-at-sonys-high-end-smartphone-the-xperia-xz-4k-reveal/"><u>[Updated] 2024 Approved Peek at Sony's High-End Smartphone - The Xperia XZ 4K Reveal</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fiscal-flyers-top-5-low-cost-aerial-vehicles/"><u>2024 Approved Fiscal Flyers Top 5 Low-Cost Aerial Vehicles</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1715859590309-2024-approved-premier-12-video-capture-goes-on-forever/"><u>2024 Approved Premier 12 Video Capture - Goes On Forever!</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-os-fixing-chkdsk-sfc-dism-explained/"><u>Demystifying OS Fixing: CHKDSK, SFC, DISM Explained</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-vanishing-windows-1011-search-results/"><u>Eliminating Vanishing Windows 10/11 Search Results</u></a></li>
<li><a href="https://fox-place.techidaily.com/exploring-windows-security-features-a-guide-to-control-panel-settings-by-yl-computing/"><u>Exploring Windows Security Features: A Guide to Control Panel Settings by YL Computing</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/guide-to-consolidating-your-youtube-video-collection/"><u>Guide to Consolidating Your YouTube Video Collection</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-ccleaner-not-working-on-windows-11-and-11/"><u>How to Fix CCleaner Not Working on Windows 11 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-htc-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from HTC .</u></a></li>
<li><a href="https://win11.techidaily.com/mend-your-dotnet-secure-your-system-max-156/"><u>Mend Your DotNet, Secure Your System (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-systems-a-detailed-look-at-13-recovery-steps/"><u>Reviving Systems: A Detailed Look at 13 Recovery Steps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/save-youtube-content-instantly-use-clickdownloader-for-a-hassle-free-experience-on-mac-computers/"><u>Save YouTube Content Instantly: Use ClickDownloader for a Hassle-Free Experience on Mac Computers</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-guide-to-stop-win-11s-mobility-hub/"><u>Simplified Guide to Stop Win 11'S Mobility Hub</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-nubia-z50s-pro-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Nubia Z50S Pro FRP</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-imaginary-hardware-name-error-in-windows-11/"><u>Tackling Imaginary Hardware Name Error in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-essentials-how-to-efficiently-renew-your-hyperx-headsets-drivers/"><u>Update Essentials: How to Efficiently Renew Your HyperX Headset's Drivers</u></a></li>
</ul></div>


---
title: Correcting Faulty Windows Update Error
date: 2024-06-25T11:35:41.236Z
updated: 2024-06-26T11:35:41.236Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Faulty Windows Update Error
excerpt: This Article Describes Correcting Faulty Windows Update Error
keywords: Fix Windows Update Issue,Resolve Updater Errors,Stop Window Update Failures,End System Update Problems,Eliminate Update Crashes,Correct Windows Update Glitch,Solve Update Faults Effectively
thumbnail: https://thmb.techidaily.com/d108669ab03559524bb77121c4032c30df350e077c8698244c3203b72aed2547.jpg
---

## Correcting Faulty Windows Update Error

 BriWindows Update is a critical component of the Windows operating system that keeps your system up to date with the latest security patches and bug fixes. Although these updates are generally helpful, they can result in Windows malfunctioning or displaying error messages.

 Windows Update Error Code 0x80190001 is one such error that appears when you try to install a system update. In this article, we'll look at what causes Windows Update Error 0x80190001 and how to fix it.

## What Causes Windows Update Error 0x80190001?

 Windows Update Error 0x80190001 occurs most often when trying to download and install Windows Updates. It can make your computer feel outdated, slow, and unresponsive since it won't receive important security updates.

 Common causes of this error may include incorrect time and date settings, corrupted or faulty system files, and incompatible third-party security software. In this article, we'll discuss each of these issues in more detail so that you can get your Windows Updates running again.

Here are a few things you can try if you encounter this error.

## 1\. Restart Your Computer

 A corrupted system file is often the cause of the Windows Update Error. To fix the issue and get your system running again, restarting your computer is always a good start.

 It’s important to note that simply clicking “Restart” in Windows will not reset all the memory caches and processes. Instead, you may need to perform a hard reboot. For this, you will need to hold down the power button on your device for 3-4 seconds until it completely shuts off.

 After that, you should wait for 30 seconds and then hit the power button again to turn on the computer. Upon restarting, check to see if Windows Update has now started working correctly.

## 2\. Run Windows Update Troubleshooter

 The Windows Update Troubleshooter is an important tool to have. This program works to detect, diagnose and resolve any potential system update issues, ensuring that your computer runs smoothly and securely.

To try it, follow these steps:

1. Press**Win + I** on your keyboard to[open System Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**System** from the left side of the screen.
3. Then go to**Troubleshoot > Other troubleshooters** .  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Run-Windows-Update-Troubleshooter.jpg)
4. Click the**Run** option next to Windows Update.

 It may take some time for troubleshooting to be completed, so don't worry if it takes longer than expected. After completing the above steps, try installing updates on Windows.

## 3\. Check Your Date & Time

 Incorrect dates and times can interfere with Windows Update, so make sure your system's time and date are accurate. Here's how to do this:

1. Right-click on**Start** and select**Settings** from the menu list.
2. From the left pane, select the**Time & language** option.
3. Click**Date & time** on the right.
4. Turn on the toggle next to "Set the time automatically".

 You should also double-check your time zone so that Windows knows when the updates should be installed - otherwise, it may ignore them.

## 4\. Run an SFC and DISM Scan

 If you’re still having trouble installing a Windows update, chances are you have corrupted or missing system files. To resolve this, you must first run SFC and DISM.

 An SFC (System File Checker) scan will detect any corrupted system files and attempt to repair them, while a DISM (Deployment Image Servicing and Management) scan will check for any broken Windows components that need repairing.

 Both scans are relatively quick and straightforward processes that don’t require any advanced technical knowledge. All you need to do is open Command Prompt as an administrator and follow these steps:

1. Run Command Prompt as an administrator (see[how to run Command Prompt as an administrator](<http://How> to Run the Command Prompt as an Administrator in Windows) ).
2. If UAC appears, click**Yes** to grant privileges.
3. Type the command in the Command Prompt window:**sfc /scannow** .
4. Then press**Enter** on your keyboard.  
![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

 The process will take a few minutes to complete. If you wish, you can do other things while the system scans the data. Once the process is completed, try updating Windows again.

 If the problem persists, you should run the Deployment Image Servicing and Management command line tool to restore system files and repair any corrupted system images. Here are the steps to follow:

1. Open Command Prompt with admin access as above.
2. Type the following command and press**Enter** to execute:  
DISM /Online /Cleanup-Image /ScanHealthDism.exe /online /cleanup-image /restorehealth

 You may have to wait for a while for the process to complete. After you run the DISM command, restart your computer to see if the issue has been resolved.

## 5\. Clear the SoftwareDistribution Folder

 Clearing the SoftwareDistribution folder will delete all temporary files created when Windows updates are downloaded and installed. This will free up space on your computer and potentially resolve any errors you are experiencing. Here's how to do this:

1. Press**Win + R** to open the Run dialog box.
2. Type "cmd" in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When UAC appears on the screen, click**Yes** to continue. This will open Command Prompt with admin access
4. In the Command Prompt, type these commands then press**Enter** each time:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After executing those commands, open Windows File Explorer.
6. Browse to the following path:**C:\\Windows\\SoftwareDistribution** .
7. Delete all content inside the SoftwareDistribution folder. Now you need to restart any services that were previously stopped.
8. In order to do this, run the following commands from an elevated Command Prompt.  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Restart your computer after you have completed the above steps. You should now be able to update Windows.

​​​​

## 6\. Perform a Clean Boot

 Performing a clean boot helps eliminate software conflicts and can be an effective way of resolving Windows Update errors like 0x80190001\. So, try this out if none of the above solutions work.

1. Click on Start and search for**System Configuration** .
2. Select the**Best match** from the search results.
3. In the System Configuration window, go to the**General** tab.
4. Check for**Selective startup** .  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
5. Remove the check mark from**Load startup items** .

1. On the Services tab, select**Hide all Microsoft services** .  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
2. Then click**Disable all** .
3. Click**Apply** to save your changes.
4. Now switch to the Startup tab and click the**Open Task Manager** link.  
![Open Task Manager Via Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Open-Task-Manager-Via-Startup-tab.jpg)
5. On the**Startup** tab, right-click each service and disable it.
6. To save your changes, click**OK** in the System Configuration window,

 Once you have finished the steps above, restart your computer and try updating Windows again. If you find this method helpful, it means the problem lies with one of the services you disabled. As such, enable each service one by one and identify the one causing the problem.

## Fixing Windows Update Error 0x80190001

 Windows Update Error 0x80190001 can be a frustrating issue to deal with, causing your system to become insecure and out of date. Fortunately, this article contains several strategies to help you identify and resolve this issue.

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
<li><a href="https://win11.techidaily.com/bypassing-disabling-directives-essential-4-fixes-to-windows-ps-load-issue/"><u>Bypassing Disabling Directives: Essential 4 Fixes to Windows PS Load Issue</u></a></li>
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-tailoring-the-visual-experience/"><u>Windows Terminal: Tailoring the Visual Experience</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-windows-lockscreen-for-user-preferences/"><u>Adapting Windows Lockscreen for User Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-working-state-for-ccleaner-in-windows-1011-systems/"><u>Enabling Working State for CCleaner in Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-windows-11-boots-a-triad-of-tips/"><u>Mastering Faster Windows 11 Boots: A Triad of Tips</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-compatibility-of-brightness-controls-via-fn-key-win-11/"><u>Restoring Compatibility of Brightness Controls via Fn Key Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-search-tracing-programs-settlement-in-windows/"><u>Streamlining Your Search: Tracing Programs' Settlement in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oneplus-11r-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from OnePlus 11R to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-a70-by-fonelab-android-recover-music/"><u>How to retrieve erased music from A70</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-enhancing-visual-impact-a-guide-to-jump-cut-techniques/"><u>[New] In 2024, Enhancing Visual Impact  A Guide to Jump Cut Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-seamless-techniques-for-effective-iphone-screen-captures/"><u>[Updated] 2024 Approved  Seamless Techniques for Effective Iphone Screen Captures</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-from-iphone-12-pro-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Unlock iCloud Account Without Password From iPhone 12 Pro</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-the-canine-chorus-a-library-of-realistic-dog-sounds/"><u>In 2024, The Canine Chorus A Library of Realistic Dog Sounds</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-scripted-sign-offs-for-the-savvy-viewer/"><u>2024 Approved  Scripted Sign-Offs for the Savvy Viewer</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-free-green-screen-fun-top-10-mobile-apps-for-creative-video-editing/"><u>New Free Green Screen Fun Top 10 Mobile Apps for Creative Video Editing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-characters-the-art-of-3d-text-design/"><u>[Updated] Crafting Characters  The Art of 3D Text Design</u></a></li>
</ul></div>

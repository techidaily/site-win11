---
title: What's Next for Failed Updates - Code 0X800f0845?
date: 2024-06-25T11:28:01.911Z
updated: 2024-06-26T11:28:01.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What's Next for Failed Updates - Code 0X800f0845?
excerpt: This Article Describes What's Next for Failed Updates - Code 0X800f0845?
keywords: Update Failure XF845,Faulty Windows Update,XF800 Error Fixing,Updating Troubleshoot,Code 0X800FIX,Windows Error Resolution,Failed Update Solutions
thumbnail: https://thmb.techidaily.com/04f98c03565f60c0b0ad3b1ba3f80966cc746c43e46cf7809dfb5c690e2c4abe.jpg
---

## What's Next for Failed Updates - Code 0X800f0845?

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the[many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on[CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the[Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.
8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-crashes/"><u>Navigating Through Windows 10/11'S Recycle Bin Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-computer-doesnt-meet-minimum-requirements-intel-hd-graphics-error/"><u>How to Fix the This Computer Doesn’t Meet Minimum Requirements Intel HD Graphics Error</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-the-reserve-memory-concept/"><u>Unveiling Windows: The Reserve Memory Concept</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-more-disk-room-with-this-roundup-of-cheap-volume-enhancers/"><u>Unlock More Disk Room with This Roundup of Cheap Volume Enhancers</u></a></li>
<li><a href="https://win11.techidaily.com/enable-system-sounds-despite-muted-status/"><u>Enable System Sounds Despite Muted Status</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-productivity-with-top-6-windows-apps/"><u>Elevate Your Productivity with Top 6 Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-transition-dance-mastering-enterexit-rituals-of-terminals-focused-state/"><u>Navigating the Transition Dance: Mastering Enter/Exit Rituals of Terminal's Focused State</u></a></li>
<li><a href="https://win11.techidaily.com/winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-snipping-tool-in-windows-11/"><u>How to Open the Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-samsung-galaxy-a05-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Samsung Galaxy A05 Phone Forgot Password</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-how-to-make-a-bigger-head-look-on-your-tiktok-video-a-comprehensive-guide-3-steps/"><u>[New] How to Make a Bigger Head Look on Your TikTok Video  A Comprehensive Guide (3 Steps)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-secrets-unveiled-for-documenting-real-time-sports-for-2024/"><u>[Updated] Secrets Unveiled for Documenting Real-Time Sports for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-natural-luminescence-in-home-interiors-simple-steps/"><u>2024 Approved  Natural Luminescence in Home Interiors  Simple Steps</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-y36-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo Y36 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unshackle-your-gaming-experience-with-diverse-capture-tools/"><u>[Updated] Unshackle Your Gaming Experience with Diverse Capture Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/building-a-brand-on-instagram-establishing-a-business-entity-for-2024/"><u>Building a Brand on Instagram  Establishing a Business Entity for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unveiling-frames-5-effective-charge-free-youtube-techniques/"><u>Unveiling Frames  5 Effective, Charge-Free YouTube Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-screen-capture-clarified-a-fraps-breakdown-for-2024/"><u>[New] Screen Capture Clarified  A Fraps Breakdown for 2024</u></a></li>
</ul></div>

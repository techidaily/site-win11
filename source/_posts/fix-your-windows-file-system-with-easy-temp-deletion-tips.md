---
title: Fix Your Windows File System with Easy Temp Deletion Tips
date: 2024-09-30T03:30:02.627Z
updated: 2024-10-03T21:08:25.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Your Windows File System with Easy Temp Deletion Tips
excerpt: This Article Describes Fix Your Windows File System with Easy Temp Deletion Tips
keywords: Windows File Fix Guide,Temp Deletion Tips,Safe File System Repair,Easy Delete Files,Optimize Windows Drive,Cleanup Temp Files Quickly,Faster Windows Performance
thumbnail: https://thmb.techidaily.com/4e1e135a4b0338f686903eb0c608ba2a349e6fad2f1ea5329a35a6ad22caba43.png
---

## Fix Your Windows File System with Easy Temp Deletion Tips

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151858/7443" target="_top" id="2151858">
  <img src="//a.impactradius-go.com/display-ad/7443-2151858" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151858/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://program-issues.techidaily.com/sifu-how-to-fix-fps-dip-and-smoother-gameplay-experience-for-pc-gamers/"><u>'Sifu': How to Fix FPS Dip and Smoother Gameplay Experience for PC Gamers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-driving-engagement-the-art-of-building-a-buzz/"><u>[New] Driving Engagement The Art of Building a Buzz</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagrams-ultimate-guide-to-the-best-grid-software-of-the-year/"><u>[New] In 2024, Instagram's Ultimate Guide to the Best Grid Software of the Year</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-live-broadcast-tech-for-industry-experts/"><u>[New] Top Live Broadcast Tech for Industry Experts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/be-a-part-of-the-hype-hot-10-tiktok-challenges-to-join-for-2024/"><u>Be a Part of the Hype Hot 10 TikTok Challenges to Join for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/bose-quietcomfort-435-audio-restoration-effective-diagnosis-and-solutions/"><u>Bose QuietComfort 435 Audio Restoration - Effective Diagnosis & Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-disk-access-in-modern-windows-oses-win-1011/"><u>Deciphering Disk Access in Modern Windows OSes (Win 10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-sam-related-issues-on-modern-windows/"><u>Deciphering SAM-Related Issues on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-11-blue-screen-errors-with-microsoft/"><u>Decoding Windows 11 Blue Screen Errors with Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-productivity-leveraging-the-windows-11-bar/"><u>Enhance Productivity: Leveraging the Windows 11 Bar</u></a></li>
<li><a href="https://win11.techidaily.com/from-basic-user-to-hyper-v-guru-setup-on-w11-homes-unlocked/"><u>From Basic User to Hyper-V Guru: Setup on W11 Homes Unlocked</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-11-pros-of-perfect-color-balancing-mastery/"><u>In 2024, 11 Pros of Perfect Color Balancing Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/master-strategies-for-handling-windows-error-0xc00000f/"><u>Master Strategies for Handling Windows Error: 0Xc00000f</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-apperror-with-text-on-w11-os/"><u>Overcoming AppError with Text on W11 OS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-remedies-to-correct-ntfs-boot-files-ntldr-errors/"><u>Step-by-Step Remedies to Correct NTFS Boot Files (NTLDR) Errors</u></a></li>
<li><a href="https://win11.techidaily.com/stylishen-windows-mail-and-calendar-use-preferred-photographs/"><u>Stylishen Windows Mail & Calendar: Use Preferred Photographs</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-evolution-of-excellence-contrasting-features-between-samsung-galaxy-s24-ultra-and-s23-ultra/"><u>The Evolution of Excellence: Contrasting Features Between Samsung Galaxy S24 Ultra and S23 Ultra</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-window-thumbnails-dimensions/"><u>Tweaking Window Thumbnails' Dimensions</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-best-way-to-convert-4k-videos-to-mp4-fast-free-and-easy-for-2024/"><u>Updated Best Way to Convert 4K Videos to MP4 Fast, Free, and Easy for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
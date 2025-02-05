---
title: Combatant Guide for the Windows Updater Error 0X80070003
date: 2025-02-02T21:25:26.337Z
updated: 2025-02-04T00:50:59.766Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatant Guide for the Windows Updater Error 0X80070003
excerpt: This Article Describes Combatant Guide for the Windows Updater Error 0X80070003
keywords: Windows Update Troubleshooting,Error 0X80070003 Fix,Updating Error Resolution,WinUpdate Failure Guide,Handling OS Updater Errors,XP Upgrade Problem Solving,Microsoft Update Issue Help
thumbnail: https://thmb.techidaily.com/dce6bc9a112b3f049356452f785b8eb72027385ba75d849bd9c5cf60929a80d0.png
---

## Combatant Guide for the Windows Updater Error 0X80070003

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-pros-and-tips-building-realistic-3d-text-in-photos/"><u>[New] In 2024, Pros and Tips Building Realistic 3D Text in PHOTOS</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/he-youtube-inversion-creative-tactics-to-watch-videos-backwards-for-2024/"><u>[New] The Youtube Inversion Creative Tactics to Watch Videos Backwards for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-seo-breakthrough-dominating-the-podcast-rankings-landscape/"><u>[Updated] In 2024, SEO Breakthrough Dominating the Podcast Rankings Landscape</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-shorten-videos-for-instagram-a-mac-guide-for-2024/"><u>[Updated] Shorten Videos for Instagram A Mac Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/blu-ray-disc-h264/"><u>「品質保証の下、ハイスピードでBlu-Ray Disc H.264への変換手順」</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-bring-footage-together-ken-burns-technique-for-camtasa-users/"><u>2024 Approved Bring Footage Together Ken Burns Technique for Camtasa Users</u></a></li>
<li><a href="https://win11.techidaily.com/cm-3/"><u>動画素材中のCMパターンを見つけ出せ: 3つのスニファリティ方法</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-understanding-and-evaluating-blackberrys-playbook-tablet/"><u>Comprehensive Guide: Understanding and Evaluating BlackBerry's PlayBook Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/dvd-mp4/"><u>DVDコピーワラジ脱出 MP4への変換手順</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-bulk-downloading-anime-a-step-by-step-guide/"><u>Efficient Techniques for Bulk Downloading Anime: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-guide-finding-and-downloading-your-favorite-disney-films/"><u>Effortless Guide: Finding & Downloading Your Favorite Disney Films</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-analysis-reveals-recurring-crash-problems-with-intel-powered-laptop-computers/"><u>Expert Analysis Reveals Recurring Crash Problems with Intel-Powered Laptop Computers</u></a></li>
<li><a href="https://win11.techidaily.com/free-mp4-to-mpg-conversion-techniques-top-8-solutions-unveiled/"><u>Free MP4-to-MPG Conversion Techniques: Top 8 Solutions Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/get-your-youtube-vids-as-mp4mp3-best-unpaid-video-and-audio-downloader-apps-available-now/"><u>Get Your YouTube Vids as MP4/MP3 - Best Unpaid Video & Audio Downloader Apps Available Now!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-can-we-unlock-our-nubia-red-magic-9-proplus-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Nubia Red Magic 9 Pro+ Phone Screen?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigate-your-next-purchase-with-confidence-using-toms-hardware-insights/"><u>Navigate Your Next Purchase with Confidence Using Tom's Hardware Insights</u></a></li>
<li><a href="https://win-forum.techidaily.com/win11-wont-boot-heres-what-you-need-to-do/"><u>Win11 Wont Boot? Here's What You Need to Do!</u></a></li>
</ul></div>


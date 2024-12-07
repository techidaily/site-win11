---
title: "Overcoming Windows Error: 0X80070003 During System Upgrades"
date: 2024-12-02T01:22:59.713Z
updated: 2024-12-07T06:41:10.745Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows Error: 0X80070003 During System Upgrades"
excerpt: "This Article Describes Overcoming Windows Error: 0X80070003 During System Upgrades"
keywords: Windows Error Fix,Upgrade Failure X80070003,System Upgrade Troubleshoot,Resolve XP Error Update,X80070003 Solution Guide,Fixing Upgrade 0XError,Windows Error 0X80070003 Fix
thumbnail: https://thmb.techidaily.com/36cb4ddf3fc78c71836e11f4a803426f35040ec4e34c37b6c57cca04ad1d4891.jpg
---

## Overcoming Windows Error: 0X80070003 During System Upgrades

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the folder is deleted, open the Settings app and try installing the updates again.

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

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-blog.techidaily.com/n-2024-charting-the-course-to-earnings-with-youtube-videos/"><u>[New] In 2024, Charting the Course to Earnings with YouTube Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-simplified-video-posts-on-twitter-and-tumblr-for-2024/"><u>[New] Simplified Video Posts on Twitter and Tumblr for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-unlock-cartoon-creativity-transforming-selfies-into-stories/"><u>[Updated] In 2024, Unlock Cartoon Creativity Transforming Selfies Into Stories</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-the-height-final-cut-pro-x-techniques-for-instagram-video/"><u>[Updated] Mastering the Height Final Cut Pro X Techniques for Instagram Video</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-unleashing-video-potential-with-effective-tagging-techniques-on-youtube-for-2024/"><u>[Updated] Unleashing Video Potential with Effective Tagging Techniques on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ease-of-virtualbox-installation-hinges-on-prerequisites/"><u>Ease of VirtualBox Installation Hinges on Prerequisites</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-network-issues-in-windows-11-a-step-by-step-guide/"><u>Fixing Common Network Issues in Windows 11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-get-more-views-with-the-best-youtube-thumbnail-ideas/"><u>In 2024, Get More Views with the Best YouTube Thumbnail Ideas</u></a></li>
<li><a href="https://discover-data.techidaily.com/missing-page-alert-unable-to-retrieve-desired-information-online/"><u>Missing Page Alert: Unable to Retrieve Desired Information Online</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-download-roadblocks-and-hiccups/"><u>Overcoming Windows Download Roadblocks & Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-operational-windows-alt-codes-47-characters/"><u>Repairing Non-Operational Windows Alt Codes (47 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-disconnected-printer-in-the-os-domain/"><u>Reviving a Disconnected Printer in the OS Domain</u></a></li>
<li><a href="https://win-answers.techidaily.com/solution-steps-for-when-warzone-skins-wont-appear-correctly/"><u>Solution Steps for When Warzone Skins Won't Appear Correctly</u></a></li>
<li><a href="https://win11.techidaily.com/solving-ownership-challenges-with-configurations-restricted-by-your-org/"><u>Solving Ownership Challenges with Configurations Restricted by Your Org</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-settling-steam-service-disruptions-in-win11/"><u>Strategies for Settling Steam Service Disruptions in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/uncluttering-your-system-locate-and-remove-null-folder-space/"><u>Uncluttering Your System: Locate and Remove Null Folder Space</u></a></li>
</ul></div>


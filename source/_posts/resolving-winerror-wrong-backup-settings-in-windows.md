---
title: "Resolving WinError: Wrong Backup Settings in Windows"
date: 2024-11-26T18:53:52.509Z
updated: 2024-11-27T17:36:24.296Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving WinError: Wrong Backup Settings in Windows"
excerpt: "This Article Describes Resolving WinError: Wrong Backup Settings in Windows"
keywords: Fixing WINError,Backup Issue Resolution,Restoring OS Functionality,Correct Backup Settings,WinError Troubleshooting,Windows Error Correction,Data Backup Problems
thumbnail: https://thmb.techidaily.com/410b1a4d385c6e4b30f8c2bafd9b2a73f332bf6953f02a101819f0b8ffe4d954.jpg
---

## Resolving WinError: Wrong Backup Settings in Windows

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a[problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to[show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.

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
<li><a href="https://twitter-videos.techidaily.com/new-perfecting-high-resolution-views-on-tweet-vids/"><u>[New] Perfecting High-Resolution Views on Tweet Vids</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-unlock-google-meets-potential-on-youtube-with-this-guide/"><u>[Updated] 2024 Approved Unlock Google Meet's Potential on YouTube with This Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevate-views-and-subscribers-a-list-of-proven-youtube-techniques/"><u>[Updated] In 2024, Elevate Views and Subscribers A List of Proven YouTube Techniques</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlock-the-potential-of-hd-videos-on-android-devices/"><u>2024 Approved Unlock the Potential of HD Videos on Android Devices</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-conflicts-causing-print-problems/"><u>Demystifying Conflicts Causing Print Problems</u></a></li>
<li><a href="https://win11.techidaily.com/fix-microsoft-teams-video-glitch/"><u>Fix Microsoft Teams Video Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-windows-reboot-options/"><u>Guiding Through Windows Reboot Options</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-boost-your-classic-game-experience-adding-achievements-with-retroarch/"><u>How to Boost Your Classic Game Experience: Adding Achievements with Retroarch</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-honor-play-7t-by-drfone-android/"><u>How to Bypass FRP on Honor Play 7T?</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-honor-play-40c-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-converting-mobi-e-books-for-a-seamless-kindle-reading-experience-faqs-answered/"><u>How to Converting MOBI E-Books for a Seamless Kindle Reading Experience - FAQs Answered</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-infinix-note-30-vip-racing-edition-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Infinix Note 30 VIP Racing Edition to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win-cloud.techidaily.com/melhores-metodos-de-copia-para-ssd-da-crucial-escolha-a-mais-adequada/"><u>Melhores Métodos De Cópia Para SSD Da Crucial - Escolha a Mais Adequada</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-complexity-of-system-recovery-in-windows-11/"><u>Navigating Through the Complexity of System Recovery in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/scheduling-podcast-drops-with-peak-engagement-times/"><u>Scheduling Podcast Drops with Peak Engagement Times</u></a></li>
<li><a href="https://win11.techidaily.com/synching-your-way-to-digital-unity-android-plus-windows/"><u>Synching Your Way to Digital Unity: Android + Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-failed-windows-update-error-0x80242016/"><u>Troubleshoot Failed Windows Update (Error 0X80242016)</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-token-misreference-issue-in-win11-and-10/"><u>Troubleshooting Token Misreference Issue in Win11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/win10win11-restoring-write-access-to-corrupted-folders/"><u>Win10/Win11: Restoring Write Access to Corrupted Folders</u></a></li>
</ul></div>


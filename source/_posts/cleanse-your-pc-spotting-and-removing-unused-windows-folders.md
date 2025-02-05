---
title: "Cleanse Your PC: Spotting & Removing Unused Windows Folders"
date: 2025-01-29T06:19:00.503Z
updated: 2025-02-03T16:41:08.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cleanse Your PC: Spotting & Removing Unused Windows Folders"
excerpt: "This Article Describes Cleanse Your PC: Spotting & Removing Unused Windows Folders"
keywords: PC Cleanup Guide,Remove Windows Junk,Spot Unwanted Files,Delete Obsolete Folders,Optimize System Space,Eliminate Redundant Data,Clearance for Efficiency
thumbnail: https://thmb.techidaily.com/a4a765e99a54a380752423d8d88b32966a3339aa9293b1bce2b9a95dc690dd25.jpg
---

## Cleanse Your PC: Spotting & Removing Unused Windows Folders

 Despite not consuming any disk space, empty folders can still impede our file management efforts. For this reason, clearing out unnecessary clutter is essential to keep your drives and folders organized. The problem is, having hundreds of folders on various drives makes manually finding and deleting empty ones nearly impossible. This raises the question: is there an efficient way to delete empty folders from your computer?

 In this article, we'll show you how to remove empty folders from your computer with PowerShell, a Windows built-in utility, and third-party software.

## Setting the Foundation to Delete Empty Folders in Windows

 By default, not all users can delete every empty folder on a device; some can only be accessed, edited, and deleted by administrators.

 Since we'll be deleting all empty folders hiding on your device, logging in with an administrator account is best to avoid encountering errors later. Need help? Check out our[g](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/#how-to-enable-or-disable-the-windows-administrator-account) uide that explains[the Windows administrator account](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) in detail, including how to enable (or disable) it.

 Secondly, the methods we'll cover can help delete empty folders quickly, but only those are visible to us, not hidden. Therefore, if you want to delete all empty folders without leaving any hidden ones behind, you should first unhide all hidden folders. Follow these steps to do so:

1. Open Windows File Explorer.
2. In Windows 11, click on**three horizontal dots** at the right end of the File Explorer menu and then click**Options** .  
![Going to the Options Menu by Clicking on the Three Horizontal Dots in the Right End of the File Explorer Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/1-going-to-the-options-menu-by-clicking-on-the-three-horizontal-dots-in-the-right-end-of-the-file-explorer-menu.jpg)  
 When using Windows 10, select the**File** menu and click**Options** .
3. Go to the**View** tab in the**Folder** **Options** window and check the box for**Show hidden files, folders, and drives** .  
![Checking the Circle for Show Hidden Files Folders and Drives in Folder Options Window of File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/2-checking-the-circle-for-show-hidden-files-folders-and-drives-in-folder-options-window-of-file-explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you've signed in as an administrator and revealed the hidden folders, it's time to delete the empty folders.

## How to Find and Delete Empty Folders Using Windows PowerShell

 If you only want to declutter a few folders, such as the ones containing your college data, there is no need to use third-party software. Interestingly, the Windows PowerShell utility can help you wipe out empty folders with just one command. Here's how:

1. Copy the path to the folder or drive you intend to scan for empty subfolders.
2. Type**"Windows PowerShell"** into Windows Search, right-click on the**Windows PowerShell** app, then click**Run as administrator** .  
![Running the Windows PowerShell App as Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/3-running-the-windows-powershell-app-as-administrator.jpg)  
 Find out[how to open the Command Prompt and PowerShell utility in other ways](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the following command in the PowerShell application after adding the path to the target folder and hit**Enter** :  
`(gci "folderpath" -r | ? {$_.PSIsContainer -eq $True}) | ?{$_.GetFileSystemInfos().Count -eq 0} | select FullName | Out-GridView`  
![Locating Empty Folders by Running a Command in Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/4-locating-empty-folders-by-running-a-command-in-windows-powershell-app.jpg)
4. PowerShell will display all empty subfolders within that folder in a few seconds. Be patient if it takes a while.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Successfully Locating All Empty Folders and Subfolders Using Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/5-successfully-locating-all-empty-folders-and-subfolders-using-windows-powershell-app.jpg)
5. Look over the list of empty folders PowerShell displays and determine whether they are safe to delete. When you are sure you want to delete these empty folders, enter the following command after adding the target folder path at its respective location:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`(gci "folderpath" -r | ? {$_.PSIsContainer -eq $True}) | ?{$_.GetFileSystemInfos().Count -eq 0} | remove-item`  
![Deleting the Empty Folders by Running the Command in Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/6-deleting-the-empty-folders-by-running-the-command-in-windows-powershell-app.jpg)
6. Hit**Enter** and the empty subfolders will be automatically deleted.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There's a catch, though. If you delete the empty subfolder in a folder that previously contained only that empty subfolder, the main folder also becomes empty. If you delete that empty folder by executing the command a second time, perhaps another parent folder in the tree may also become empty.

 To prevent this issue, run the above command three to four times until the command that finds the empty folders does not reveal any remaining empty subfolders in PowerShell.

 Similarly, you can use the above method to find empty folders on crowded drives and delete them. However, this method is limited because it doesn't allow you to delete some empty folders, leaving others intact selectively.

 Therefore, if you want more control over finding and deleting empty folders on your Windows device, you will have to use third-party tools. In the next section, we will demonstrate how you can do it.

## How to Find and Delete Empty Folders Using Third-Party Software

 While the method discussed above will work in most cases, it requires more manual input and gives less control over deleting specific empty folders. To keep things more straightforward and less time-consuming, you can use third-party software to clean your device.

 You can use any software that lets you find and delete empty folders, but we recommend 4dots' Empty Folder Cleaner for its ease of use. Let's take a look at how it aids in finding and deleting empty folders on Windows:

1. Visit[4dots' official website](https://www.4dots-software.com/emptyfoldercleaner/#google%5Fvignette) to download Empty Folder Cleaner.
2. Install the software on your device.
3. Let Windows install any .NET Framework it prompts you to install.
4. Once the application has been installed, run it.
5. Check the boxes for all drives or folders you want to scan (except the one where your operating system is installed).  
![Checking the Boxes for Drives or Folders to Scan in the Empty Folder Cleaner Software on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/8-checking-the-boxes-for-drives-or-folders-to-scan-in-the-empty-folder-cleaner-software-on-windows.jpg)

1. When you have selected the drives and folders you want to scan for empty folders, click on the**Scan** button in the top-left corner.  
![Viewing the Empty Files and Folders Found After Scanning the Selected Folders in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/9-viewing-the-empty-files-and-folders-found-after-scanning-the-selected-folders-in-empty-folder-cleaner-software.jpg)
2. Depending on how much data you're scanning, the app may take a while. Wait until the scan is complete.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Upon completion of the scan, you will see a list of empty folders that have been found on your device. You can view them either as a list or as a tree.
4. Check the boxes for empty folders you wish to delete or select all empty folders by clicking**Select All** .  
![Checking the Boxes for All Empty Files and Folders by Clicking on Select All Button in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/10-checking-the-boxes-for-all-empty-files-and-folders-by-clicking-on-select-all-button-in-empty-folder-cleaner-software.jpg)
5. In the top-left corner, right next to**Scan** , click**Delete Empty Folders** .
6. Once the warning pop-up appears, select**Yes** to delete all empty folders successfully.  
![Deleting All Empty Files and Folders by Clicking on the Yes Button in the Warning Pop-up in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/11-deleting-all-empty-files-and-folders-by-clicking-on-the-yes-button-in-the-warning-pop-up-in-empty-folder-cleaner-software.jpg)

 There is no doubt that Empty Folder Cleaner makes deleting empty folders on Windows devices incredibly simple. Despite its ease of use, it remains a third-party software. Even though it has a good reputation, you should still be aware of security risks when using it, especially when allowing it to scan confidential documents.

## Don't Let Empty Folders Clog Up Your Device's Organization

 Even though empty folders don't strain our devices, removing them is a great way to keep your device organized. Hopefully, the instructions in this article will help clear your device of empty folders and unnecessary clutter.

 Besides empty folders you deleted, many other files and folders unnecessarily burden your device, including files in Windows Temp, Recycle Bin, and LiveKernelReports. So, watch out for this extra burden and lower it regularly to keep your machine running smoothly.

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
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-echovid-save-facebook-calls/"><u>[Updated] In 2024, EchoVid - Save Facebook Calls</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-mastering-gradual-audio-silence-with-audacity-for-2024/"><u>[Updated] Mastering Gradual Audio Silence with Audacity for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-viral-video-victory-lap-youtubes-1-10-in-one-day/"><u>[Updated] Viral Video Victory Lap YouTube's #1-#10 in One Day</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722968053394-easy-guide-to-downloading-and-installing-corsair-void-pro-on-your-pc/"><u>Easy Guide to Downloading and Installing Corsair Void Pro on Your PC!</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-nokia-g42-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-vivo-v30-pro-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Vivo V30 Pro to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-vivo-s18e-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Vivo S18e? Fixed | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/review-insights-on-mobvoi-ticwatch-pro-3-enhanced-battery-performance-throughout-with-gps-and-two-screens/"><u>Review Insights on Mobvoi TicWatch Pro 3: Enhanced Battery Performance Throughout with GPS & Two Screens</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-videos-with-wonderfox-premium-copyright-watermarks/"><u>Secure Your Videos with WonderFox: Premium Copyright Watermarks</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-downloading-videos-from-naver-without-paying/"><u>Step-by-Step Guide: Downloading Videos From Naver Without Paying</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-recording-your-tango-calls-across-all-platforms/"><u>Step-by-Step Guide: Recording Your Tango Calls Across All Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-missing-mcuicnt-file-execution-issue-on-windows/"><u>Tackling Missing McUICnt File Execution Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-hunting-game-reversed-in-frozen-ground-dvd-release/"><u>The Hunting Game Reversed in 'Frozen Ground' DVD Release</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-converting-mov-files-into-wav-format-a-comprehensive-guide/"><u>Top 8 Methods for Converting MOV Files Into WAV Format: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-solutions-how-to-resolve-your-pcmac-video-playback-issues/"><u>Top 8 Solutions: How to Resolve Your PC/Mac Video Playback Issues</u></a></li>
<li><a href="https://win11.techidaily.com/top-no-cost-arte-video-downloader-seamless-access-to-high-quality-arte-streams-at-zero-price/"><u>Top No-Cost Arte Video Downloader: Seamless Access to High-Quality Arte Streams at Zero Price</u></a></li>
<li><a href="https://win11.techidaily.com/top-rated-mpeg-2-converter-tools-effortlessly-transforming-files-into-your-desired-format/"><u>Top Rated MPEG-2 Converter Tools: Effortlessly Transforming Files Into Your Desired Format</u></a></li>
</ul></div>


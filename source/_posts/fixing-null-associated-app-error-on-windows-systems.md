---
title: Fixing Null Associated App Error on Windows Systems
date: 2024-06-25T09:41:28.551Z
updated: 2024-06-26T09:41:28.551Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Null Associated App Error on Windows Systems
excerpt: This Article Describes Fixing Null Associated App Error on Windows Systems
keywords: NullAppErrorWindows,FixNullAppWin,ResolveAppNullWin,StopNullWinAppErr,WindowsAppNullFix,RemoveNullAppWinError,NullAppErrorSolverWin
thumbnail: https://thmb.techidaily.com/4a7e35e05dbbab3383219ac491b7159c730c023be090a3ce22bfc91cc23bb5f7.jpg
---

## Fixing Null Associated App Error on Windows Systems

 The error "this file does not have an app associated with it" mainly occurs when Windows can't find a compatible app for opening a specific file type. If you have the relevant app installed, it might not be set as default to open files of that format, or the app or file itself could be corrupted or damaged.

 The error can also occur when opening folders, mainly from Windows Search, and even when running apps and games. Here are some solutions you can apply to resolve this error regardless of where you get it.

## 1\. Ensure You Have an App Installed That Can Open Such Files

 Windows presents this error primarily when it fails to find the appropriate app to open files. Therefore, first, you should check whether you have the right app installed to open files in this particular format. There are several ways to check this, but here is one of the easiest:

1. Navigate to the file that is displaying this error when you open it.
2. Right-click the file and select**Properties** .
3. Navigate to the**General** tab and look for the file format next to**Type of file** .  
![Check the File Format in Properties Window of File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-1.jpg)

 If it's a commonly used file format, such as PDF, JPEG, PNG, Docx, etc., for which you have the appropriate app installed, move on directly to heading #2\. However, if you see an unusual file format here—something you haven't seen before, make sure you have the appropriate app installed.

 To confirm this, right-click the file and navigate to**Open with > Choose another app** .

![Click on Choose Another App by Right-clicking on the File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-1.jpg)

 If you have a relevant app installed, Windows will suggest you select it to open the file. If you don't see any app suggestions here, you probably don't have any apps installed capable of opening this file type.

![Windows Suggesting Some Apps to Open the Image File in PNG Format](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-suggesting-some-apps-to-open-the-image-file-in-png-format.jpg)

 If that's the case, simply go to any of your browsers, search for Windows apps that can run files in that format, and download them. After downloading the appropriate app, make it the default for opening this file type.

## 2\. Set the Default Application for the File Type

 The error message states that if the app is already installed, you need to create an association in the Default Programs. If you already had the compatible app installed or have just downloaded it, your next step should be to set it as default for files having that file type or format. Setting the compatible application as default may solve this problem right away.

 If you haven't changed a default app before, check out our article on[Windows 11 default apps](https://www.makeuseof.com/change-windows-11-default-apps/) . The article discusses various ways to change the default app, but we recommend using the second method, which is using the Settings app. That's because this method lets you search for specific file formats and choose a default app for them.

## 3\. Is the Default App Already Selected? Repair or Change It

 If the app you intend to set as default for a particular file format is already selected as a default application, but Windows still displays this error, the app has likely become corrupt, thus causing the error.

 To rule out this possibility, you should run the App troubleshooter, update the problematic app, reset its cache, or repair and reset it. You can find instructions for performing these steps in our[g](https://www.makeuseof.com/apps-arent-working-properly-windows/) uide for[fixing apps that don't work on Windows](https://www.makeuseof.com/apps-arent-working-properly-windows/) .

 Try these steps to see if they fix the problem. If the issue persists after that, we recommend you reinstall the app or select a different one as the default. If you don't have a different app installed on your device that supports these files, install one that does.

## 4\. Check for Specific File Issues

 If you're opening the file in a compatible app, it's working normally, and you've already set it as default, but you're still encountering the error, verify the file itself isn't corrupt. To confirm that, open any other file having the same file format and see if it returns the same error.

 If other files open without error, but the issue persists with one file, it's likely that the file is corrupt. If that's the case, follow our[guide on using Windows built-in tools to fix corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) . If that doesn't fix the problem, try using one of the[dedicated tools for repairing corrupted files](https://www.makeuseof.com/tag/best-tools-repair-corrupted-damaged-files-windows/) .

 Misconfiguring the Registry settings can result in undesirable outcomes and even render your device unbootable. Before you try the next fix, create a[backup of the Windows Registry so you can restore it](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if something goes wrong.

## 5\. Use the Registry

 If none of the above fixes have been successful, try this registry tweak as a last resort:

1. Type**"regedit"** in Windows Search and open the**Registry Editor** .  
![Open Registry Editor App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-1.jpg)
2. Paste the path below into the address bar of Registry Editor.  
Computer\HKEY_CLASSES_ROOT\lnkfile
3. Select the**Inkfile** key. Then, look in the right pane and see if there is a string value called**"IsShortcut** .**"**  
![Locate the IsShortcut String Value in the Inkfile Key of Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-1.jpg)
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  
![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
5. If the string value is already there, right-click on it and select**Delete** .  
![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.
7. Restart your device once after that.

## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see[how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

## Do You Encounter the Error When Opening Apps or Games? Try These Tips

 If you get the "This file does not have an app associated with it" error when opening an app or game, perform the following checks:

* If you're using a shortcut to open games, especially the ones installed in a gaming client, open them from the gaming client or the installation directory.
* In case the game launcher requires you to log in before playing any of the installed games, ensure you do so.
* If you're experiencing this error in a specific game or app, ensure its files haven't been corrupted.

## Easily Open Your Apps, Files, and Folders Again on Windows

 Seeing the error "this file does not have an app associated with it" when opening a file, folder, or app can be frustrating. If the file or folder isn't corrupt, the above fixes will help you identify and resolve the issue's root cause. If nothing works, you can reinstall the app or restore the older version of the file or folder from your backup.

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
<li><a href="https://win11.techidaily.com/device-agnostic-operating-system-windows-for-iphonesipads-macs-pcs-launched/"><u>Device-Agnostic Operating System: Windows for iPhones/iPads, Macs, PCs Launched</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-windows-camera-app-malfunctions/"><u>Fixing Common Windows Camera App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/override-hardware-acceleration-in-widnos-graphics-ordering/"><u>Override Hardware Acceleration in WIDNO's Graphics Ordering</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stop-microsoft-teams-from-crashing-windows-1110/"><u>Steps to Stop Microsoft Teams From Crashing Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-settings-for-better-device-control/"><u>Navigating Windows 11 Settings for Better Device Control</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-task-management-in-windows-11-via-enhanced-run-functionality/"><u>Optimizing Task Management in Windows 11 via Enhanced Run Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-optional-features-not-installing-on-windows-11-and-11/"><u>7 Ways to Fix Optional Features Not Installing on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-vm-management-hosting-linux-on-a-windows-system-with-hyper-v/"><u>Efficient VM Management: Hosting Linux on a Windows System with Hyper-V</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-quiet-edge-achieving-crystal-clear-video-through-smart-sound-editing-in-premiere-pro-for-2024/"><u>The Quiet Edge Achieving Crystal-Clear Video Through Smart Sound Editing in Premiere Pro for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-one-stop-video-editing-shop-35-best-apps-for-windows-mac-ios-android-and-linux/"><u>New One-Stop Video Editing Shop 35 Best Apps for Windows, Mac, iOS, Android, and Linux</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-5-easy-ways-to-multiply-your-youtube-follower-base/"><u>[New] 5 Easy Ways to Multiply Your YouTube Follower Base</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-exploring-the-finest-free-streaming-services-a-top-10-list-for-iphone-and-android-users-for-2024/"><u>Updated Exploring the Finest Free Streaming Services A Top 10 List for iPhone & Android Users for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expertise-in-action-quick-tips-for-online-photo-trimming-for-2024/"><u>Expertise in Action  Quick Tips for Online Photo Trimming for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-play-40c-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor Play 40C to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-beginning-profits-periscope-income-strategies-for-novices/"><u>In 2024, Beginning Profits  Periscope Income Strategies for Novices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-heritage-on-display-post-copyright-masterpieces/"><u>2024 Approved  Heritage on Display  Post-Copyright Masterpieces</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-iphone-6-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 6 When We Dont Have Apple ID or Password?</u></a></li>
</ul></div>

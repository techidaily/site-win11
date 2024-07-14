---
title: "Fine-Tuning File Properties: A Window'ayer's Manual"
date: 2024-07-13T10:37:10.074Z
updated: 2024-07-14T10:37:10.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fine-Tuning File Properties: A Window'ayer's Manual"
excerpt: "This Article Describes Fine-Tuning File Properties: A Window'ayer's Manual"
keywords: File Property Adjustments,Windows File Settings Guide,Optimize File Attributes,Advanced File Configurations,Enhance File Properties,File Customization Techniques,Mastering File Settings
thumbnail: https://thmb.techidaily.com/950d846f8fcee250021d944b4596b6aafb3f396fb97820df6fae0f8fc53f28aa.jpg
---

## Fine-Tuning File Properties: A Window'ayer's Manual

 Windows keeps a record of when a file was created, who authored it, and when it was last modified. This information is known as file attributes and can be used to sort files by date, author name, and other parameters.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.

## How to Change the Date Created, Date Accessed, and Date Modified Attributes Using PowerShell

 File Explorer doesn't allow changing critical attributes, such as the date a document was created, accessed, or modified. With [PowerShell, a command-line interface utility built into Windows](http://www.makeuseof.com/what-is-windows-powershell/), you can modify them.

 However, the process to change the attributes with PowerShell is a bit complex. If you don't have any experience using PowerShell, you can use a third-party app, Attribute Changer, to change the attributes, as explained in the next section.

 If running a few commands in PowerShell isn't a big deal (for instance, you already know the [best PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/)), follow the steps outlined below to change the created, modified, or accessed dates.

 First, type **"PowerShell"** in Windows Search, right-click on **PowerShell,** and select **Run as administrator**. This gives the utility administrative access to make the desired changes without any restriction.

![Run windows powershell as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-powershell-as-administrator.jpg)

 Then, navigate to the directory where the file or folder you want to change the attributes of is located. Type **cd..** to move back one folder in the given path, and **cd folder\_name** to move to the next folder.

 For example, our desired folder is located at the following location:

`C:\Users\ehtas\Documents\Files`

 However, in PowerShell, we were in the **"System 32"** subfolder of the main folder **"Windows**.**"** Therefore, to return to the main directory **"C**,**"** we've executed **cd..** twice. Then, we used the **cd folder\_name** command three times to get to the directory where we wanted to be.

![changing the directories in PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-directories.jpg)

 Therefore, use both commands to reach the folder you want to modify attributes for. After landing in your desired directory, type the following command after inserting the file name and your preferred date of creation:

`$(Get-Item File-name).creationtime=$(Get-Date "mm/dd/yyyy")`

 If PowerShell doesn't present any errors and takes you to the same directory again, that confirms that the attributes have been successfully changed.

![successfully changing the creation date of a file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/creation-date-has-been-changed.jpg)

 Likewise, you can change the date modified and the date accessed by typing the following two commands:

`$(Get-Item File-Name).lastaccesstime=$(Get-Date "mm/dd/yyyy")  
$(Get-Item File-Name).lastwritetime=$(Get-Date "mm/dd/yyyy")`

![Changing the last modified date in Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/last-modified-date-has-been-changed.jpg)

 Before changing the attributes, here is how a file's created, modified, and accessed dates looked:

![Showing dates of a file we are about to change in the properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dates-of-a-file-we-are-about-to-change.jpg)

 After changing them with PowerShell, here are the updated dates:

![Date created and date modified of a file successfully changed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/date-created-and-date-modified-of-a-file-successfully-changed.jpg)

 Windows makes real-time changes to attributes. Therefore, don't modify or access the file after making changes since it will change the modified and accessed dates again.

## How to Modify the Date Created, Date Accessed, and Date Modified Using Attribute Changer

 The Attribute Changer app is one of the [third-party attribute changer apps](https://www.makeuseof.com/apps-change-created-modified-date-windows/) that lets users change file attributes, including when a file was created, modified, or accessed. If changing the file attributes using PowerShell is challenging for you, here are the steps to modify them using this third-party app:

1. Go to the [official PETGES website](https://www.petges.lu/).
2. Download the full setup of Attribute Changer; do not download the portable version, as it may not function properly.
3. Once the software has been downloaded, run the setup file and follow the onscreen instructions to install it.
4. Restart your device if the software asks you to; otherwise, there's no need.
5. Navigate to the folder containing the file whose attributes you wish to modify.

1. Right-click the file and select **Change Attribute** from the context menu to open the software. If you're using Windows 11, you may need to click **Show more options** to reveal this option in the context menu.  
![opening the attribute changer app from context menu of a file in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/opening-the-attribute-changer-app-from-context-menu-of-a-file-in-windows.jpg)
2. Once the application opens, check the box beside **Modify date and time stamps** to make the date field editable.
3. Change the date and time when a file was first created and the last time you accessed or modified it according to your preference.  
![changing the attributes of a file from the atribute changer app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/changing-the-attributes-of-a-file-from-the-atribute-changer-app.jpg)
4. Once you've made your changes, click **Apply** to make them permanent.
5. Click **Yes** in the confirmation pop-up, and the file attributes will be changed successfully.

 In the same way that we changed the attributes of a file, you can also change the attributes of a folder using Attribute Changer.

 Using third-party tools to modify attributes requires you to grant apps permission to access the file. Therefore, if the documents you want to modify the dates for are confidential, don't use third-party apps to change the attributes; instead, use the official methods offered by Windows.

## How to Remove Other File Attributes Using File Explorer

 While File Explorer does not permit modifying critical attributes such as Date Created, Date Modified, and Date Accessed, it does permit users to remove specific attributes such as the author, copyright information, revision number, etc. To remove attributes that are possibly removable using File Explorer, follow the below steps:

1. Navigate to the folder where you want to change the attributes.
2. Right-click on it and select **Properties** from the context menu.
3. Navigate to the **Details** tab at the top of the window.
4. Click the **Remove Properties and Personal Information** link.  
![Opening the Window to Remove the Personal Information of Text Document in the Details Tab of Document Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/1-Removing-the-Personal-Information-of-Text-Document-in-the-Details-Tab-of-Document-Properties.jpg)
5. To remove all possible properties automatically, check the circle beside **Create a copy with all possible properties removed**. This will create a duplicate of the file at the exact location after deleting all possible attributes.  
![Removing possible file attributes in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/removing-possible-file-attributes-in-file-explorer.jpg)
6. To remove selected properties, check the circle beside **Remove the following properties from this file**, select the attributes you want to remove, and click **OK**.

## Modify Your File's Attributes With Ease

 Modifying file attributes is a great way to hide author information, revision numbers, and other details, such as when a file was created, modified, or accessed. Hopefully, you now better understand the different ways to modify file attributes. Using PowerShell is the easiest and most recommended method to change them.

 If you find it complicated or want more control over how the attributes are changed, you can use the Attribute Changer. If you take this route, be aware of the privacy risks involved.

 The problem is that sharing a file with your teacher or supervisor at work entails sharing all of this information, putting your job or grades at risk. To prevent this, you can modify these attributes.

 If you don't want the receiver to know the actual file attributes, here's how to remove or modify them.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-access-denied-error-on-windows-11/"><u>5 Ways to Fix the “Access Denied” Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-false-virus-detection-issue/"><u>Overcoming Chrome’s False Virus Detection Issue</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pcs-login-trail-a-win-flip-guide/"><u>Securing Your PC's Login Trail: A Win-Flip Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winning-every-game-with-smart-amd-radeon-configurations/"><u>Winning Every Game with Smart AMD Radeon Configurations</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-update-to-sonys-premium-blu-ray-player/"><u>[Updated] Unveiling the Update to Sony’s Premium Blu-Ray Player</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/maximizing-video-visibility-top-strategies-on-fb/"><u>Maximizing Video Visibility  Top Strategies on FB</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-show-more-pins-on-win-11-startscreen/"><u>Techniques to Show More Pins on Win 11 Startscreen</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-elite-cameras-for-windows-11-pro-review-of-the-latest-gear-for-2024/"><u>[Updated] Elite Cameras for Windows 11 - Pro Review of the Latest Gear for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-on-windows-11-easily/"><u>Enabling Hyper-V on Windows 11 Easily</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-top-rated-quicktime-editors-free-and-easy-to-use/"><u>In 2024, Top Rated QuickTime Editors Free and Easy to Use</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-grayed-out-extend-volume-option-in-disk-management-for-windows/"><u>How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-ntoskrnlexe-process/"><u>Tackling Excessive Ntoskrnl.exe Process</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-classic-directx-games-with-dxvk-upgrades/"><u>Refreshing Classic DirectX Games with DXVK Upgrades</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-rock-solid-footage-the-best-free-online-video-stabilizers/"><u>New In 2024, Rock-Solid Footage The Best Free Online Video Stabilizers</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-efficiently-obtain-youtube-srt-files-in-three-methods/"><u>2024 Approved  Efficiently Obtain YouTube SRT Files in Three Methods</u></a></li>
<li><a href="https://win11.techidaily.com/winpc-restoring-lost-connections-with-easy-6-strategies-for-troubleshooting-adapters/"><u>WinPC: Restoring Lost Connections with Easy 6 Strategies for Troubleshooting Adapters</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-take-your-videos-to-the-next-level-with-64-bit-editing-for-2024/"><u>Updated Take Your Videos to the Next Level with 64-Bit Editing for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-vivo-v27-pro-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Vivo V27 Pro Phone that is Locked?</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-cracking-the-code-of-viral-success-with-tiktoks-top-strategies/"><u>In 2024, Cracking the Code of Viral Success with TikTok's Top Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-xbox-mic-use-with-windows-11-app/"><u>Unblocking Xbox Mic Use with Windows 11 App</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-elevate-youtube-rankings-with-optimized-metadata/"><u>In 2024, How to Elevate YouTube Rankings with Optimized Metadata</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-window-11-potential-7-tips/"><u>Unleash Your Window 11 Potential: 7 Tips</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-top-ten-os-agnostic-video-players/"><u>Unveiling Top Ten OS-Agnostic Video Players</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-completely-getting-rid-of-wsl-on-win-11/"><u>Instructions for Completely Getting Rid of WSL on Win 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-a-detailed-list-of-top-free-cross-platform-mobile-video-chats-for-2024/"><u>[Updated] A Detailed List of Top Free, Cross-Platform Mobile Video Chats for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-amazons-social-stardom-liking-and-viewing-leaderships-for-2024/"><u>[New] Amazon's Social Stardom  Liking and Viewing Leaderships for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-creativity-a-detailed-look-at-vsco-features/"><u>[Updated] Unleash Creativity  A Detailed Look at VSCO Features</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-variances-a-comparison-between-microsoft-and-standard-windows-accounts/"><u>Exploring Variances: A Comparison Between Microsoft and Standard Windows Accounts</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-how-to-choose-the-best-mac-mp3-tag-editor-in-2024/"><u>New How To Choose the Best Mac MP3 Tag Editor, In 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-vivo-t2-pro-5g-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Vivo T2 Pro 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-write-failure-in-windows/"><u>Overcoming Memory Write Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-the-missing-search-back-into-win11s-task-manager/"><u>Bringing the Missing Search Back Into Win11's Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-microsoft-store-error-0x80073cf3/"><u>Steps to Resolve Microsoft Store Error 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winupdate-error-x8019/"><u>Troubleshooting WinUpdate Error X8019</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-melody-migration-made-easy-a-guide-to-the-best-free-youtube-downloading-apps/"><u>2024 Approved  Melody Migration Made Easy  A Guide to the Best Free YouTube Downloading Apps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-compression-and-decompression-tactics-in-windows-cli/"><u>Quick Compression & Decompression Tactics in Windows CLI</u></a></li>
<li><a href="https://win11.techidaily.com/solving-uninstall-issues-in-windows-11/"><u>Solving Uninstall Issues in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-premiere-10-warzone-clashes/"><u>2024 Approved  Premiere 10 Warzone Clashes</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/how-to-talk-like-a-pirate-20-pirate-words/"><u>How to Talk Like a Pirate: 20 Pirate Words</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-most-reliable-and-affordable-passport-photo-makers-ranked-for-2024/"><u>The Most Reliable and Affordable Passport Photo Makers Ranked for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-mystery-of-infinite-c-drive-usage/"><u>Combatting the Mystery of Infinite C: Drive Usage</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-effortless-editing-top-8-lightweight-video-software-options/"><u>Updated In 2024, Effortless Editing Top 8 Lightweight Video Software Options</u></a></li>
</ul></div>

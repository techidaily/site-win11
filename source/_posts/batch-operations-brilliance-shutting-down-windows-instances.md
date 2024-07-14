---
title: "Batch Operations Brilliance: Shutting Down Windows Instances"
date: 2024-07-13T11:23:21.467Z
updated: 2024-07-14T11:23:21.467Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Batch Operations Brilliance: Shutting Down Windows Instances"
excerpt: "This Article Describes Batch Operations Brilliance: Shutting Down Windows Instances"
keywords: Batch Op Shutdowns,Instance Termination,Operations Management,Windows Shutdown,Efficient Orchestration,System Downscaling,Instance Optimization
thumbnail: https://thmb.techidaily.com/744014ffd50adb1d07a7a2940727b9c6e249d35c9b35474b3c5a660491ebe0a3.png
---

## Batch Operations Brilliance: Shutting Down Windows Instances

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://win11.techidaily.com/avoiding-glitches-enabling-latest-emojis-on-windows-11/"><u>Avoiding Glitches: Enabling Latest Emojis on Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-realme-v30t-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Realme V30T Devices | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-realme-v30-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Realme V30 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/stealthy-sound-softening-with-garageband-for-2024/"><u>Stealthy Sound Softening with Garageband for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-earning-mastery-in-streams-a-comprehensive-review/"><u>In 2024, Earning Mastery in Streams  A Comprehensive Review</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-save-location-blunders-on-windows-devices/"><u>Avoiding Save Location Blunders on Windows Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-great-video-platform-debate-vimeo-and-youtube/"><u>The Great Video Platform Debate  Vimeo & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-gameplay-seamlessly-adding-achievements-using-retroarch/"><u>Boosting Classic Gameplay - Seamlessly Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-corrupt-files-error-code-0x80070570-solutions-for-windows-11/"><u>Beating Back Corrupt Files Error Code 0X80070570: Solutions for Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-vivo-t2-pro-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Vivo T2 Pro 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-13-pro-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue From Apple iPhone 13 Pro</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-fastest-methods-to-uncover-hidden-reddit-articles/"><u>The Fastest Methods to Uncover Hidden Reddit Articles</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-user-engagement-with-context-menu-update-options/"><u>Bolstering User Engagement with Context Menu Update Options</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-infinix-smart-8-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Infinix Smart 8</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-best-in-class-memetics-engine/"><u>[New] Best-in-Class Memetics Engine</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-display-with-w11s-auto-hdr-feature/"><u>Boost Your Display with W11's Auto HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-powershell-with-admin-privileges-on-windows-11/"><u>Accessing PowerShell with Admin Privileges on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-invisible-time-recording-expertise/"><u>In 2024, Invisible Time Recording Expertise</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-obs-studio-vs-fraps-top-screen-capture-software-showdown/"><u>[Updated] 2024 Approved  OBS Studio Vs Fraps  Top Screen Capture Software Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-10-and-11-climate-choices/"><u>Best Windows 10 & 11 Climate Choices</u></a></li>
<li><a href="https://win11.techidaily.com/black-and-white-brilliance-a-guide-for-the-shadows/"><u>Black & White Brilliance: A Guide for the Shadows</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-app-opening-top-techniques-for-windows-11/"><u>Boosted App Opening: Top Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-key-steps-to-tackle-windows-blue-screen/"><u>Breaking Down Key Steps to Tackle Windows Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-windows-11-on-outdated-devices/"><u>Breaking Barriers: Windows 11 on Outdated Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-10-action-cams-steady-shooting-excellence-for-2024/"><u>Best 10 Action Cams  Steady Shooting Excellence for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-dial-up-beats-easy-audio-posting-to-youtubes/"><u>[New] In 2024, Dial-Up Beats  Easy Audio Posting to YouTubes</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-activation-error-0x8007251d-fixes-and-tips/"><u>Breaking Down Windows Activation Error 0X8007251D: Fixes and Tips</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/re-enable-sound-on-twitter-video-tweets/"><u>Re-Enable Sound on Twitter Video Tweets</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-glitches-a-guide-for-fixing-windows-office-issues/"><u>Addressing Failure Glitches: A Guide for Fixing Windows Office Issues</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-windows-11-installation/"><u>Beginner's Blueprint to Windows 11 Installation</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-customize-your-videos-speed-in-camtasia-a-beginners-guide/"><u>Updated Customize Your Videos Speed in Camtasia A Beginners Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-demystifying-igtv-for-a-comprehensive-social-media-experience-for-2024/"><u>[Updated] Demystifying IGTV  For a Comprehensive Social Media Experience for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-roblox-programming-mistakes/"><u>Addressing Critical Roblox Programming Mistakes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-tiny-tempo-truths-character-beats-exposed/"><u>2024 Approved  Tiny Tempo Truths  Character Beats Exposed</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-immediate-impact-integrating-luts-into-your-ae-workflow/"><u>[New] Immediate Impact  Integrating LUTs Into Your AE Workflow</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/valheim-agronomy-explained-choosing-superior-saplings-for-2024/"><u>Valheim Agronomy Explained  Choosing Superior Saplings for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/professional-approach-to-convert-webp-images-to-jpeg/"><u>Professional Approach to Convert WebP Images to JPEG</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-rapid-clicks-turn-off-mouse-accel-in-win-11/"><u>Avoiding Rapid Clicks: Turn Off Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/airplane-mode-heres-your-guide-for-win11/"><u>Airplane Mode? Here's Your Guide for Win11</u></a></li>
</ul></div>

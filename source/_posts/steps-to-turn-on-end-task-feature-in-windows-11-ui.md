---
title: Steps to Turn On End Task Feature in Windows 11 UI
date: 2024-06-25T11:30:31.372Z
updated: 2024-06-26T11:30:31.372Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Turn On End Task Feature in Windows 11 UI
excerpt: This Article Describes Steps to Turn On End Task Feature in Windows 11 UI
keywords: Win11_EndTaskOn,ActivateWindowsFeature,TaskSwitchingUI,EnableUICommitTasks,Windows11TaskControl,InitiatingUIActivation,UITaskEnablingSteps
thumbnail: https://thmb.techidaily.com/8f0b4518ce0df25393954ab31a3f7f9f5a628c2c9b34d40260095f1057a6321d.jpg
---

## Steps to Turn On End Task Feature in Windows 11 UI

 The "end task" option in Windows 11 is your best friend when a program has stopped responding or has frozen. It allows you to close those unresponsive applications without restarting your PC. However, the "end task" may not be easy to find on Windows 11, especially if you are new to the operating system.

 In this article, we are sharing tricks to bring the End task option to the Windows 11 taskbar by using ViveTool. After enabling it, you will be only a click away from closing all the unresponsive applications.

## What Is ViveTool, And Why Do You Need It to Enable End Task in Taskbar?

 ViveTool is a third-party program designed to enable Windows 11 features that Microsoft is testing internally and are not available for Insiders or general users. Using this app, ViveTool can give you an idea about what the software company plans to introduce to the next Windows 11 updates.

 At the time of writing, the "end task" option on Windows 11 taskbar is currently hidden in Windows 11 Dev Insider build 25300, meaning that even Insiders can't get it just yet. And this is where the ViveTool comes in.

 You can enable feature ID 42592269 to make the end task option appear on the taskbar jump list. However, before we hop into ViveTool and enable this handy feature, you should keep your expectations low regarding the functionality and reliability of the features you're about to enable.

## How to Enable End Task Option in Windows 11 Taskbar

![End task option in Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/end-task-option-in-taskbar.jpg)

 Besides ViveTool, you also need to ensure that your PC is running Windows 11 Dev Channel build 25300 or later. You should see the build number in the bottom right corner of the desktop. Alternatively, you can navigate to**Settings** \>**System** \>**About** to check the OS build number.

 After ensuring your PC is running build 25300 or newer,[download the ViveTool zip file from the GitHub page](https://github.com/thebookisclosed/ViVe/releases) . Now, open File Explorer and find the zipped file. To unzip it, right-click on the file and select**Extract All** . You can also[unzip the file by using Command Prompt and PowerShell](https://www.makeuseof.com/zip-unzip-files-command-prompt-powershell/) . For the sake of simplicity, the extracted content should be in the folder**C:/ViVeTool** .

![Enable End Task option in Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/feature-id-in-command-prompt-edit.jpg)

 Now that you are done with setting up ViveTool on Windows 11, follow the below steps to enable the feature ID responsible for adding the "end task" option on the Windows 11 taskbar:

1. Open Command Prompt as an Administrator (see[how to open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for steps).
2. Type the following command and hit**Enter** :  
cd C:\ViVeTool
3. Copy and paste the following command and press**Enter:**  
vivetool /enable /id:42592269

 Command Prompt will display a message that says "Successfully set feature configuration (s)" after successfully running the command. To make the changes take effect, restart your computer. After the restart, open a program and right-click its icon on the taskbar to display the jump list containing the**End task** option.

## An End Task Button on the Windows 11 Taskbar Is Now at Your Fingertips

 Adding the "end task" option onto the Windows 11 taskbar is currently available only via ViveTool. However, in the coming days, Microsoft will likely introduce it to every Windows 11 Insider, then eventually to the public either via a Moment update or through the Windows Web Experience pack. But before that happens, you are now familiar with the trick to terminate any task or process right from the Windows 11 taskbar.


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
<li><a href="https://win11.techidaily.com/antimalware-resource-hog-turn-it-off-for-better-performance/"><u>Antimalware Resource Hog: Turn It Off for Better Performance</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-between-standby-and-complete-shutdown/"><u>Deciding Between Standby and Complete Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workflow-adding-tasks-to-file-context-menus/"><u>Elevate Your Workflow: Adding Tasks to File Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-java-installer-problems-on-a-windows-pc/"><u>Remedying Java Installer Problems on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-files-vanish-permanently-in-your-desktop-trash-bin-windows-11/"><u>How to Make Files Vanish Permanently in Your Desktop Trash Bin (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-error-windows-security-cut-by-admin-policies/"><u>Deciphering Error: Windows Security Cut by Admin Policies</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-access-the-key-to-your-windows-11-folder/"><u>Conquering Access: The Key to Your Windows 11 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-display-selecting-premium-timers-and-savers/"><u>Upgrade Your Display: Selecting Premium Timers & Savers</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-down-excessive-ntoskrnlexe-utilization/"><u>Trimming Down Excessive Ntoskrnl.exe Utilization</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-s18-pro-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo S18 Pro Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-unboxing-freex-streamer-pro-for-webcams/"><u>2024 Approved  Unboxing FreeX Streamer Pro for Webcams</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-is-this-a-bug-or-intentional-edit-on-instagram/"><u>In 2024, Is This a Bug or Intentional Edit on Instagram?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-meizu-21-pro-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Meizu 21 Pro to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-secure-your-shots-above-all-unlimited-free-options-and-premium-subscription-picks/"><u>[Updated] In 2024, Secure Your Shots Above All  Unlimited Free Options & Premium Subscription Picks</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-record-slow-motion-videos-with-phantom-slow-mo-camera/"><u>New Record Slow Motion Videos With Phantom Slow-Mo Camera</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expert-tips-for-masterminding-memelore-on-9gag-for-2024/"><u>Expert Tips for Masterminding Memelore on 9GAG for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-masterclass-naming-your-podcast-and-top-50plus-name-suggestions-for-inspiration/"><u>In 2024, Masterclass  Naming Your Podcast & Top 50+ Name Suggestions for Inspiration</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-lightning-fast-windowed-image-viewer/"><u>2024 Approved  Lightning-Fast Windowed Image Viewer</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-playback-issues-on-redmi-note-13-proplus-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV playback issues on Redmi Note 13 Pro+ 5G</u></a></li>
</ul></div>

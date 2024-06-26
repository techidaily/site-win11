---
title: Navigating to Silent Tab Disabling in Windows 11
date: 2024-06-25T11:41:51.165Z
updated: 2024-06-26T11:41:51.165Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to Silent Tab Disabling in Windows 11
excerpt: This Article Describes Navigating to Silent Tab Disabling in Windows 11
keywords: Windows 11 Tabs Mute,Tab Silence Mode,11 PC Quiet Switch,Windows 11 No Sound Tabs,Disable Tabs Sound,Windows 11 Silent Tabs,Mute Windows 11 Apps
thumbnail: https://thmb.techidaily.com/5e4f2e08bc06e83ddb45587d928cf61d9245bd50e484b6c6cc6059c7ac856aae.jpg
---

## Navigating to Silent Tab Disabling in Windows 11

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://win11.techidaily.com/unpacking-the-implications-of-removing-windows-11s-taskbar-chatting-capability-on-you/"><u>Unpacking the Implications of Removing Windows 11'S Taskbar Chatting Capability on You</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-the-critical-windows-c0000022-bug/"><u>Confronting the Critical Windows C0000022 Bug</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-restore-your-usb-wi-fi-on-a-pc/"><u>7 Key Steps to Restore Your USB Wi-Fi On a PC</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-batch-jobs-leveraging-task-scheduler/"><u>Supercharge Batch Jobs: Leveraging Task Scheduler</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-ending-the-gpsvc-hang-up-loop/"><u>Strategies for Ending the GPSVC Hang-Up Loop</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-tasks-custom-windows-shortcuts-for-uwp/"><u>Breeze Through Tasks: Custom Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unexpected-token-call-issues-on-windows-devices/"><u>How To Resolve “Unexpected Token Call” Issues on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-open-issues-windows-11s-mail-and-calendar-hiccup/"><u>Fixing Open Issues: Windows 11'S Mail & Calendar Hiccup</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-0x800713f-issue-for-smooth-function-of-win11s-mail-app/"><u>Decoding 0X800713F Issue for Smooth Function of Win11's Mail App</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-apple-iphone-x-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on Apple iPhone X</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-converse-with-computers-for-free/"><u>[Updated] Converse with Computers for Free</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-crafting-high-quality-igtv-footage-on-smartphonesdslrs/"><u>In 2024, Crafting High-Quality IGTV Footage on Smartphones/DSLRs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-get-unbranded-tiktok-content-free-full-quality-download/"><u>[Updated] 2024 Approved  Get Unbranded TikTok Content  Free, Full Quality Download</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-top-5-factors-to-master-when-using-tiktok-web-mac/"><u>[New] 2024 Approved  Top 5 Factors to Master When Using TikTok Web (Mac)</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-itel-p40plus-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Change Location On Facebook Dating for your Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-choosing-the-ultimate-action-cam-does-black-gopro-outshine-x1000v/"><u>2024 Approved  Choosing the Ultimate Action Cam  Does Black GoPro Outshine X1000V?</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-onscreen-text-craftsman/"><u>In 2024, Onscreen Text Craftsman</u></a></li>
</ul></div>

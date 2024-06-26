---
title: Disabling Explore Tab Glitches in Modern OS
date: 2024-06-25T09:45:28.794Z
updated: 2024-06-26T09:45:28.794Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Explore Tab Glitches in Modern OS
excerpt: This Article Describes Disabling Explore Tab Glitches in Modern OS
keywords: Fix Explore Tab Issue,Disable OS Glitches,Resolve Modern OS Bug,Stop OS Explorer Errors,Eliminate OS Navigation Flaws,End Glitch in OS Search,Counteract OS Explorer Crash
thumbnail: https://thmb.techidaily.com/6eaf9b365a6361451b5795d958332fe971bf3b2af37ac8e9e5c055811b75ea47.jpg
---

## Disabling Explore Tab Glitches in Modern OS

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
<li><a href="https://win11.techidaily.com/guide-setting-up-or-removing-wi-fi-cost-tracking-in-win11/"><u>Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-with-6-advanced-trackers-for-win-users/"><u>Streamline System Use with 6 Advanced Trackers for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-search-failures-immediately/"><u>Addressing Windows 11 Search Failures Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/averting-interruptions-with-solid-connections-in-windows/"><u>Averting Interruptions with Solid Connections in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-taskbar-space-on-windows-11-os/"><u>Customizing Taskbar Space on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-terminal-in-quake-mode-on-windows/"><u>Utilizing Terminal in Quake Mode on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-the-best-9-features-in-new-outlook/"><u>Unlocking Potential: The Best 9 Features in New Outlook</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-oppo-find-x6-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Oppo Find X6 Through Google Earth?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-sound-scourge-methods-for-eradicating-irrelevant-audio-noise-in-productions/"><u>New The Sound Scourge Methods for Eradicating Irrelevant Audio Noise in Productions</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-smartphone-storytelling-mastering-vertical-video-creation-for-2024/"><u>New Smartphone Storytelling Mastering Vertical Video Creation for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-google-meet-for-everyone-a-comprehensive-no-cost-strategy-booklet/"><u>[Updated] Google Meet for Everyone  A Comprehensive, No-Cost Strategy Booklet</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-simplified-path-to-mastery-in-using-cc-licenses/"><u>2024 Approved  Simplified Path to Mastery in Using CC Licenses</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-novice-to-expert-free-lut-techniques-for-color-grading-for-2024/"><u>From Novice to Expert  Free LUT Techniques for Color Grading for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-whatsapp-status-masterclass-best-apps-for-video-and-photo-editing/"><u>Updated 2024 Approved WhatsApp Status Masterclass Best Apps for Video and Photo Editing</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-huawei-nova-y71-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Huawei Nova Y71 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/cutting-edge-fb-video-ads-mastery-with-free-toolset/"><u>Cutting-Edge FB Video Ads  Mastery with FREE Toolset</u></a></li>
</ul></div>

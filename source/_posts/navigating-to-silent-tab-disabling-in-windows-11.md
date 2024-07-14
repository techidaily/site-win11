---
title: Navigating to Silent Tab Disabling in Windows 11
date: 2024-07-13T10:54:26.864Z
updated: 2024-07-14T10:54:26.864Z
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

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
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
<li><a href="https://win11.techidaily.com/accelerate-your-winning-path-with-efficient-play/"><u>Accelerate Your Winning Path with Efficient Play</u></a></li>
<li><a href="https://win11.techidaily.com/5-peak-auto-clickers-hotkeys-plus-high-performance/"><u>5 Peak Auto Clickers: Hotkeys + High Performance</u></a></li>
<li><a href="https://win11.techidaily.com/1719328494393-uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present!</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-tube-top-ten-twitters-most-watched-video-rankings/"><u>In 2024, Tube Top Ten  Twitter's Most Watched Video Rankings</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-instagram-editors-handbook-maximizing-video-impact/"><u>[New] The Instagram Editor's Handbook  Maximizing Video Impact</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-here-are-the-top-ten-movie-trailer-apps-for-iphones-and-ipads-you-can-use-to-create-eye-catching-trailers-for-all-types-of-videos-you-create-for-202/"><u>Updated Here Are the Top Ten Movie Trailer Apps for iPhones and iPads You Can Use to Create Eye-Catching Trailers for All Types of Videos You Create for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719330298923-self-host-your-local-free-windows-based-chatgpt-clone-using-gpt4all/"><u>Self-Host Your Local, FREE Windows-Based ChatGPT Clone Using GPT4All.</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-unveiling-the-trailblazers-shaping-discords-visual-language/"><u>[New] In 2024, Unveiling the Trailblazers Shaping Discord's Visual Language</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-judicious-use-of-ping-in-windows-operations/"><u>A Guide to Judicious Use of Ping in Windows Operations</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/free-mov-video-orientation-changers-top-rated-for-2024/"><u>Free MOV Video Orientation Changers Top Rated for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/innovative-strategies-for-captivate-demonstrations-for-2024/"><u>Innovative Strategies for Captivate Demonstrations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719336940768-cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now.</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-preserving-your-win-11-push-notification-functionality/"><u>A Guide to Preserving Your Win 11 Push Notification Functionality</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-discover-the-top-5-pc-clipping-utilities-for-quick-samples/"><u>[New] Discover the Top 5 PC Clipping Utilities for Quick Samples</u></a></li>
<li><a href="https://win11.techidaily.com/1719352483219-resurrect-computer-sounds-immediate-action-steps/"><u>Resurrect Computer Sounds – Immediate Action Steps!</u></a></li>
<li><a href="https://win11.techidaily.com/1719374553725-new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/"><u>New Era of Connectivity: Windows for iPhones, iPads and PCs Just Dropped</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-or-disable-the-delete-confirmation-dialog-on-windows/"><u>3 Ways to Enable or Disable the Delete Confirmation Dialog on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719337262601-cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly.</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-fix-the-windows-terminal-not-opening/"><u>6 Ways to Fix the Windows Terminal Not Opening</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-keeping-your-tasks-visible-and-high-priority/"><u>A Guide to Keeping Your Tasks Visible and High-Priority</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-adding-virtual-gaming-archives-into-playnite/"><u>A Comprehensive Guide to Adding Virtual Gaming Archives Into Playnite</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-the-negative-side-of-low-end-windows-licenses/"><u>A Deep Dive Into the Negative Side of Low-End Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-vulnerability-alerts/"><u>A Comprehensive Look at Windows’ Vulnerability Alerts</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-ideal-steadicams-for-capturing-quality-uav-visuals/"><u>2024 Approved  Ideal Steadicams for Capturing Quality UAV Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-reviving-stuck-windows-itunes/"><u>A Comprehensible Guide to Reviving Stuck Windows iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-linux-vms-within-windows-via-hyper-v/"><u>A Step-by-Step Guide to Linux VMs Within Windows via Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-of-the-most-reliable-window-pomodoros-for-work/"><u>A Compreenas of The Most Reliable Window Pomodoros for Work</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-connect-instagram-to-facebook-for-2024/"><u>[New] How to Connect Instagram to Facebook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-strategies-for-switching-out-of-unwanted-night-mode/"><u>5 Strategies for Switching Out of Unwanted Night Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-plan-for-reclaiming-your-disconnected-ps4-link/"><u>A Step-by-Step Plan for Reclaiming Your Disconnected PS4 Link</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-taming-the-sound-waves-with-audacity-seamless-setup-and-removal-processes-in-ubuntu/"><u>New Taming the Sound Waves with Audacity Seamless Setup and Removal Processes in Ubuntu</u></a></li>
<li><a href="https://win11.techidaily.com/1719350686194-unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues</u></a></li>
<li><a href="https://win11.techidaily.com/8-mistakes-you-should-avoid-making-as-a-beginner-to-windows-11/"><u>8 Mistakes You Should Avoid Making as a Beginner to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719358882925-solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-xiaomi-redmi-note-12-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Xiaomi Redmi Note 12 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11.techidaily.com/1719320743244-windows-users-run-a-cost-free-locally-operated-gpt-model/"><u>Windows Users: Run a Cost-Free, Locally Operated GPT Model</u></a></li>
<li><a href="https://win11.techidaily.com/30-minute-guide-to-resolving-windows-onedrive-fails/"><u>30 Minute Guide to Resolving Windows OneDrive Fails</u></a></li>
<li><a href="https://win11.techidaily.com/6-simple-time-management-and-productivity-apps-for-windows/"><u>6 Simple Time Management and Productivity Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-do-you-want-to-know-how-to-add-a-vhs-effect-premiere-look-you-can-easily-apply-the-vhs-effect-to-your-videos-using-adobe-premiere-pro/"><u>New Do You Want to Know How to Add a VHS Effect Premiere Look? You Can Easily Apply the VHS Effect to Your Videos Using Adobe Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-windows-11-the-essentials-of-its-registry-data/"><u>A Window Into Windows 11: The Essentials of Its Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-winning-bittorrent-clients/"><u>A Comprehensive Guide to Winning BitTorrent Clients</u></a></li>
<li><a href="https://win11.techidaily.com/1719360575372-trouble-on-windows-discover-assistance-methods/"><u>Trouble on Windows? Discover Assistance Methods!</u></a></li>
</ul></div>

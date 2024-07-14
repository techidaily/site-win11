---
title: The Essential Steps for Windows Sandbox Configuration in 11
date: 2024-07-13T10:14:41.942Z
updated: 2024-07-14T10:14:41.942Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Steps for Windows Sandbox Configuration in 11
excerpt: This Article Describes The Essential Steps for Windows Sandbox Configuration in 11
keywords: Windows Sandoz Setup Guide,Sandbox on Win Config Steps,Configuring Windows Sandbox Quickly,Mastering Windows Sandbox Configuration,Win Sandbox Initial Setup Basics,Efficient Win Sandbox Setup Tips,Secure Windows Sandbox Guide Essential
thumbnail: https://thmb.techidaily.com/c74a6f4cbc3131991d1108cc0cd3851c9f4624d9f7132bc54e3318b3d6ad9b70.jpg
---

## The Essential Steps for Windows Sandbox Configuration in 11

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can [add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.


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
<li><a href="https://win11.techidaily.com/smashing-through-disconnection-issues-during-wins-discord-setup/"><u>Smashing Through Disconnection Issues During Win's Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-strategies-with-a-focus-on-windows-diskusage/"><u>Streamlining Storage Strategies with a Focus on Windows' DiskUsage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-jokejuggernaut-top-humor-tool/"><u>[Updated] JokeJuggernaut - Top Humor Tool</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-silent-the-screen-how-to-strip-audio-from-your-movies-in-imovie/"><u>New In 2024, Silent the Screen How to Strip Audio From Your Movies in iMovie</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-your-emulated-games-into-playnite-on-windows/"><u>How to Add Your Emulated Games Into Playnite on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/escape-heavy-requirements-tiny11-delight/"><u>Escape Heavy Requirements: Tiny11 Delight</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-boomerang-on-instagram-create-addictive-loop-videos-on-ig/"><u>[Updated] In 2024, Boomerang on Instagram  Create Addictive Loop Videos on IG</u></a></li>
<li><a href="https://win11.techidaily.com/from-obscured-space-to-optimization-windows-guide-for-reclaiming-disk/"><u>From Obscured Space to Optimization: Windows Guide for Reclaiming Disk</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-enhancing-youtube-video-screens-without-barriers-for-2024/"><u>[Updated] Enhancing YouTube Video Screens  Without Barriers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-not-found-the-ultimate-list/"><u>Overcoming Windows Not Found: The Ultimate List</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-apps-for-making-reaction-video-for-2024/"><u>Best Apps for Making Reaction Video for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/top-8-best-fbx-game-recorder-alternatives-for-2024/"><u>Top 8 Best FBX Game Recorder Alternatives for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-guide-to-cropping-and-combining-content-in-wondershare-filmora-latest/"><u>In 2024, Guide To Cropping and Combining Content in Wondershare Filmora Latest</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-make-a-countdown-video/"><u>Updated 2024 Approved Make A Countdown Video</u></a></li>
<li><a href="https://win11.techidaily.com/the-easy-guide-to-opening-iis-explorer/"><u>The Easy Guide to Opening IIS Explorer</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/video-cut-off-chronicles-in-digital-photobooths/"><u>Video Cut-Off Chronicles in Digital Photobooths</u></a></li>
<li><a href="https://win11.techidaily.com/handling-glitches-in-microsofts-nearby-sharing-service/"><u>Handling Glitches in Microsoft's Nearby Sharing Service</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-essential-tips-on-acquiring-ideal-instrumental-sounds-for-enhanced-video-experience/"><u>2024 Approved Essential Tips on Acquiring Ideal Instrumental Sounds for Enhanced Video Experience</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-realme-c67-4g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Realme C67 4G Devices | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-exclusive-insights-into-making-memorable-instagram-movies/"><u>[Updated] 2024 Approved  Exclusive Insights Into Making Memorable Instagram Movies</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-ultimate-handbook-for-swapping-music-libraries/"><u>In 2024, The Ultimate Handbook for Swapping Music Libraries</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-multiple-computers-to-one-printer-seamlessly/"><u>Syncing Multiple Computers to One Printer Seamlessly</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-gaming-prowess-on-display-with-15-best-apps-for-pc-and-mac/"><u>[New] 2024 Approved  Gaming Prowess on Display with #15 Best Apps for PC and Mac</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-erase-apple-iphone-15-pro-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>3 Ways to Erase Apple iPhone 15 Pro When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-solutions-workarounds-when-renaming-folders-is-impossible-on-win-11/"><u>Innovative Solutions: Workarounds When Renaming Folders Is Impossible on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-discoverability-of-lost-network-elements-in-winos/"><u>Enhancing Discoverability of Lost Network Elements in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activate-superior-control-over-windows-11-task-management/"><u>How to Activate Superior Control Over Windows 11 Task Management</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-pioneering-proficiency-the-complete-guide-to-music-and-media-fusion-on-youtube/"><u>In 2024, Pioneering Proficiency  The Complete Guide to Music & Media Fusion on YouTube</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-streamline-your-workflow-macos-screencast-tutorial/"><u>In 2024, Streamline Your Workflow  MacOS Screencast Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-d3d11-hardware-error-in-w11w10-environments/"><u>Fixing D3D11 Hardware Error in W11/W10 Environments</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-rhythmic-resonance-top-10-yogis-on-the-web-for-2024/"><u>[Updated] Rhythmic Resonance  Top 10 Yogis on the Web for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-restoring-secure-file-connections-on-win/"><u>Strategies for Restoring Secure File Connections on Win</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-reconnect-controlled-audio-from-windows-bluetooth-devices/"><u>Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-global-communicators-essential-list-of-top-36-platforms-for-video-conversion/"><u>2024 Approved  The Global Communicator’s Essential List of Top 36 Platforms for Video Conversion</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-top-ten-capture-hardware-rankings-for-professional-streamers/"><u>In 2024, Top Ten Capture Hardware Rankings for Professional Streamers</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-a-new-era-of-photo-display-best-frame-makers/"><u>[New] 2024 Approved  A New Era of Photo Display  Best Frame Makers</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-sign-out-problem-due-to-malware-intrusion/"><u>Remedying Windows Sign-Out Problem Due to Malware Intrusion</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-vivo-y17s-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Vivo Y17s Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-jamboree-discovering-5-entertaining-techniques/"><u>Command Prompt Jamboree: Discovering 5 Entertaining Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-shortcut-creation-on-windows-11/"><u>Harness the Power of Shortcut Creation on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-art-of-video-integration-youtube-meets-microsoft-powerpoint/"><u>The Art of Video Integration  YouTube Meets Microsoft PowerPoint</u></a></li>
<li><a href="https://win11.techidaily.com/ease-system-load-cutting-back-on-malware-scanning-power/"><u>Ease System Load: Cutting Back on Malware Scanning Power</u></a></li>
<li><a href="https://win11.techidaily.com/setting-updeactivating-wi-fi-data-tracking-on-windows-11/"><u>Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-troubleshooting-fs-problems-on-windows-11/"><u>Strategies for Troubleshooting FS Problems on Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-professional-strategies-for-screen-capturing-facetime-for-2024/"><u>[Updated] Professional Strategies for Screen-Capturing FaceTime for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-pasting-snippets-via-crafted-keybinds-in-windows-11-and-11/"><u>Effortless Pasting Snippets via Crafted Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-camera-conflict-error-0xa00f4243/"><u>Remedying Windows' Camera Conflict Error 0xA00F4243</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-peak-activity-on-instagram-finding-the-perfect-moment/"><u>2024 Approved  Peak Activity on Instagram  Finding the Perfect Moment</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-cpu-consumption-by-dropbox-on-windows-pcs/"><u>Decreasing Excessive CPU Consumption by Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-non-existing-device-alert-on-win-11/"><u>Overcoming Erroneous Non-Existing Device Alert on Win 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-prime-video-trendsetters-top-likers-and-viewers-on-twitter/"><u>[New] Prime Video Trendsetters  Top Likers & Viewers on Twitter</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-unveiling-windows-11s-narrator-commands/"><u>Comprehensively Unveiling Windows 11'S Narrator Commands</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-map-a-network-drive-in-windows-11/"><u>How to Map a Network Drive in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-realme-gt-neo-5-se-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Realme GT Neo 5 SE Phone? Unlock It Now</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-top-6-techniques-for-capturing-your-minecraft-adventures/"><u>[Updated] Top 6 Techniques for Capturing Your Minecraft Adventures</u></a></li>
</ul></div>

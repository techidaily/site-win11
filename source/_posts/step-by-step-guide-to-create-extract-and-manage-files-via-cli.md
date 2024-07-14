---
title: Step-by-Step Guide to Create, Extract and Manage Files via CLI
date: 2024-07-13T10:30:26.373Z
updated: 2024-07-14T10:30:26.373Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Create, Extract and Manage Files via CLI
excerpt: This Article Describes Step-by-Step Guide to Create, Extract and Manage Files via CLI
keywords: File Creation CLI Guide,File Management via Command Line,Command Line File Extraction,CLI File Operations Steps,Automating File Tasks CLI,Basic CLI File Handling,Scripting Files via Terminal
thumbnail: https://thmb.techidaily.com/f5eeb9ebfa2de64a3d4ee3942e718c9f14502e6b864cfccf1cdec1e982bafc3d.jpg
---

## Step-by-Step Guide to Create, Extract and Manage Files via CLI

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

## How to Zip Files Using Windows PowerShell

 There are several viable ways to [create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

## How to Unzip Files Using Command Prompt

 There may be situations where you want to [unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


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
<li><a href="https://some-guidance.techidaily.com/the-art-of-mastering-funimate-for-2024/"><u>The Art of Mastering Funimate for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-comparative-study-of-cloud-and-physical-methods-for-windows-setup/"><u>A Comparative Study of Cloud & Physical Methods for Windows Setup</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-obs-vs-streamlabs-which-is-better/"><u>2024 Approved  OBS vs Streamlabs   Which Is Better?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/creating-polished-composites-with-skillful-modes-use-for-2024/"><u>Creating Polished Composites with Skillful Modes Use for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-epic-gaming-on-pc-by-solving-login-glitches/"><u>Unlock Epic Gaming on PC by Solving Login Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-itel-a60-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Itel A60 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719362389609-determining-cpu-version-on-windows-here-are-8-ways/"><u>Determining CPU Version on Windows – Here Are 8 Ways</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ing-in-the-world-of-youtube-content-creation-for-2024/"><u>Thriving in the World of YouTube Content Creation for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-a34-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy A34 5G Phones with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-google-pixel-8-pro-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Google Pixel 8 Pro</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-brilliant-setups-top-17-gear-for-online-videographers/"><u>[Updated] Brilliant Setups  Top 17 Gear for Online Videographers</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-video-editing-on-a-budget-top-free-ubuntu-options/"><u>Updated 2024 Approved Video Editing on a Budget Top Free Ubuntu Options</u></a></li>
<li><a href="https://video-capture.techidaily.com/get-pcs-audio-capture-tool-x-recorder-for-2024/"><u>Get PC's Audio Capture Tool  X-Recorder for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-the-sky-the-syma-x5c-for-drone-beginners/"><u>[New] Exploring the Sky  The Syma X5C for Drone Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-ultra-clear-video-in-zoom-meetings/"><u>[New] Unlocking Ultra-Clear Video in Zoom Meetings</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-resolving-upgrade-error-in-windows-os/"><u>A Step-By-Step Guide to Resolving Upgrade Error in Windows OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/samsung-secrets-crafting-compelling-time-lapses/"><u>Samsung Secrets  Crafting Compelling Time Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/1719359813770-cloud-connected-computers-integrating-files-with-dropboxgoogledrive-in-c/"><u>Cloud-Connected Computers: Integrating Files with Dropbox/GoogleDrive in C</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-essential-tutorial-for-xbox-fb-streams/"><u>[New] The Essential Tutorial for Xbox FB Streams</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-record-audio-on-windows-11/"><u>2024 Approved  How To Record Audio on Windows 11?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/investing-insights-on-screen-best-youtube-guides-for-stocks/"><u>Investing Insights on Screen  Best YouTube Guides for Stocks</u></a></li>
<li><a href="https://win11.techidaily.com/5-must-have-windows-software-for-mac-refugees/"><u>5 Must-Have Windows Software for Mac Refugees</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-clear-the-tpm-on-windows-11/"><u>4 Ways to Clear the TPM on Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-maximizing-visibility-how-to-upload-videos-to-instagram-desktop/"><u>[Updated] 2024 Approved  Maximizing Visibility  How to Upload Videos to Instagram Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-starting-a-new-chapter-establishing-an-enterprise-ig-page-for-2024/"><u>[New] Starting a New Chapter  Establishing an Enterprise IG Page for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-efficient-methods-for-nvidia-screen-recording/"><u>[New] Efficient Methods for NVIDIA Screen Recording</u></a></li>
<li><a href="https://win11.techidaily.com/1719348018496-skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tweetvidsoundscape-instant-video-to-sound-for-2024/"><u>[New] TweetVidSoundscape  Instant Video-to-Sound for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-stop-automatic-office-updates-on-windows/"><u>4 Ways to Stop Automatic Office Updates on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-motorola-razr-40-ultra-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Motorola Razr 40 Ultra Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-sending-past-moments-via-snapchat-camera-roll-guide/"><u>[Updated] In 2024, Sending Past Moments via Snapchat  Camera Roll Guide</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-reasons-users-prefer-older-windows-versions/"><u>7 Key Reasons Users Prefer Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-the-secret-to-a-professional-looking-facebook-video-cover-size-matters/"><u>2024 Approved The Secret to a Professional-Looking Facebook Video Cover Size Matters</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-to-revamping-group-policy-settings/"><u>A Practical Approach to Revamping Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-lava-blaze-pro-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Lava Blaze Pro 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-avoiding-common-pitfalls-in-pc-based-youtube-video-editing/"><u>[New] 2024 Approved  Avoiding Common Pitfalls in PC-Based YouTube Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/1719366255245-functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now!</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-premium-selection-of-free-4k-software-for-windows-plus-os-x/"><u>[New] In 2024, Premium Selection of Free 4K Software for Windows + OS X</u></a></li>
<li><a href="https://win11.techidaily.com/5-apps-that-elevate-your-desktop-writing-game/"><u>5 Apps That Elevate Your Desktop Writing Game</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-ten-titles-that-triumph-top-8-apps-to-gain-facebook-likeability/"><u>[New] In 2024, Ten Titles That Triumph  Top 8 Apps to Gain Facebook Likeability</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-resolve-virtual-machines-on-windows-11-vmware/"><u>7 Key Steps to Resolve Virtual Machines on Windows 11-VMware</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/10-most-popular-aspect-ratio-changer-tools-for-2024/"><u>10 Most Popular Aspect Ratio Changer Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-immaculate-window-display-on-w11/"><u>A Guide to Immaculate Window Display on W11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/driver-not-found-windows-10-and-pixma-mp620-disconnect/"><u>Driver Not Found: Windows 10 and Pixma MP620 Disconnect</u></a></li>
</ul></div>

---
title: Overcoming Sound System Issue with Windows General Device
date: 2024-07-13T11:05:25.784Z
updated: 2024-07-14T11:05:25.784Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Sound System Issue with Windows General Device
excerpt: This Article Describes Overcoming Sound System Issue with Windows General Device
keywords: WinSoundTroubleshoot,FixWindowsAudio,AudioSystemRepair,ResolveDeviceNoise,ClearWinMediaError,OptimizePCSound,EliminateWindowAudioIssues
thumbnail: https://thmb.techidaily.com/900dc848292f751f63b27f646fc76a619bc7384a4aedd9106177497020dbae72.jpg
---

## Overcoming Sound System Issue with Windows General Device

 It’s advisable to safely eject a USB drive inserted in your Windows 11/10 PC. However, upon doing so, some users report seeing an error message that reads “Windows can’t stop your generic volume device.” Consequently, users can’t safely eject USB drives with their PCs on.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.

## 1\. Disable Background App Processes

 Disabling background app processes is the first thing you should try when you see the “Windows can’t stop your generic volume device” error. Even the error message suggests closing programs that could still be using the device.

 Make sure there aren’t any minimized software windows on your taskbar; close unneeded apps within the system tray area by right-clicking their icons and selecting exit options.

![System tray icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/system-tray-programs.jpg)

 Beyond the taskbar and system tray, you’ll need to look for and disable background app processes with Task Manager. Task Manager is a tool that provides a comprehensive overview of app and service background processes.

 Our guide on [fixing too many background processes running](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides more detail on how to terminate unneeded background apps and services with Task Manager.

## 2\. End and Restart the Windows Explorer Process

 Some users confirm ending and restarting the File Explorer process fixes the “Windows can’t stop your generic volume device” error. That highlights File Explorer is causing the error and needs to be stopped from utilizing the USB drive.

 Follow these steps to end and restart File Explorer:

1. Right-click a taskbar space and select the **Task Manager** context menu option.
2. Scroll down the **Processes** tab in Task Manager until you see Windows Explorer.
3. Right-click Windows Explorer and select **End task**. Your desktop will go blank, but restarting Explorer will restore it.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/end-task-option.jpg)
4. Click Task Manager’s **File** menu.
5. Select **Run new task** on the menu.
6. Then input **explorer** in Create new task.  
![The Create a new task tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-create-a-new-task-window.jpg)
7. Select **Create this task with administrative privileges**.
8. Click **OK** to restart Explorer.

## 3\. Troubleshoot the Device

 You can troubleshoot a USB device by running the Hardware and Devices troubleshooter with the drive connected. That troubleshooter might address some drive ejection issues.

 The Hardware and Devices troubleshooter isn’t listed in Settings. However, you can still find and use it by opening it via the Command Prompt using these steps:

1. Press **Windows** key **+** **S** to activate a file search tool, and input Command Prompt within its text box.
2. Select **Command Prompt** to open it from the search results.
3. Input and execute this Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter.jpg)
4. Click **Next** to run the troubleshooting tool.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hardware-and-devices-troubleshooter4.jpg)
5. The troubleshooter might ask you to select a device. If it does, select your connected USB storage device.  
![A USB Attached option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-attached-option.jpg)
6. Click **Apply this fix** if the Hardware and Devices troubleshooter suggests a resolution.

## 4\. Select the Quick Removal Option

 Selecting the **Quick Removal** option is another confirmed fix for the “Windows can’t stop your generic volume device” error. The **Quick Removal** option disables write caching. You can select the **Quick Removal** option for an affected drive using the following steps:

1. Click File Explorer’s taskbar shortcut and select This PC.
2. Right-click your USB drive and select **Properties**.
3. Click the **Hardware** tab.  
![The Hardware tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-hardware-tab.jpg)
4. Then press the **Properties** button.
5. Click **Change settings** to bring up another window.  
![The Change settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-settings-button.jpg)
6. Select **Policies** in the second window.
7. Then click the **Quick removal (default)** option.  
![The Quick removal radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/quick-removal-option.jpg)
8. Select **OK** to exit the device properties window.

## 5\. Deselect the Index Drive Setting

 Having file indexing enabled for an external USB drive can cause the “Windows can’t stop your generic volume” error. If that option is enabled, files copied onto your USB drive will be indexed, which can keep it in use for some time after transferring lots of files onto it.

 Follow these steps to deselect indexing for a USB drive:

1. Go to This PC in File Explorer.
2. Right-click the USB drive connected and select **Properties**.
3. Deselect the **Allow files on this drive to have contents indexed in addition to file properties** option.  
![The Allow files on this drive to have contents indexed box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/index-option.jpg)
4. Select **Apply** and **OK** to set the drive’s new setting.

## 6\. Set the Connected USB Drive to Be in Offline Mode

 A lot of users have fixed the “Windows can’t stop your generic volume device” error by setting their USB drives into offline mode. So, try setting your connected USB drive to offline mode with the DiskPart command-line line tool using these steps:

1. Press the **Windows** logo + **R** key combo for activating Run.
2. Input **cmd** into Run, and press **Ctrl** \+ **Shift** \+ **Enter** to [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
3. Then input this Diskpart command and hit **Enter**:  
`diskpart`
4. To view a drive list, input the following text and press **Return**:  
`list disk`  
![The diskpart command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command.jpg)
5. Next, execute this command to select your USB drive:  
`select disk <drive number>`
6. Finally, set the selected disk to offline by executing this command:  
`offline disk`  
![The offline command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/offline-command.jpg)

 You will need to replace **<drive number>** for the select disk command with the actual number of your USB drive listed by Diskpart. For example, if your USB drive is disk 1, the required command would look like this:

`select disk 1`

 Setting a drive offline changes its status to missing. You can set the same drive back to an online status by repeating steps one to five above and then executing this command:

`online disk`

## 7\. Assign a Different Letter to the USB Drive

 Some users have also resolved the “Windows can’t stop your generic volume device” by changing the letters of their USB drives. Assigning a different letter to a USB drive will disconnect it from certain processes.

 You can even change the drive letter back to what it originally was another time. To apply this fix, check out this [guide to changing a drive’s letter in Windows](https://www.makeuseof.com/tag/change-drive-letter-windows/).

![The Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disk-management-window.jpg)

## Safely Eject Your USB Drive

 Removing a USB drive from a PC without safely ejecting it can corrupt the data on it. So, it’s not a good idea to ignore the “Windows can’t stop your generic volume device” error.

 Applying the potential solutions covered here will resolve the error for most users. Then, you can safely remove your USB drive in Windows 11/10 with alternative methods.

 Of course, you can still safely remove a USB drive with a PC off. However, many users still prefer to be able to safely eject their connected drives without shutting down their computer. This is how you can fix the “Windows can’t stop your generic volume device” error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/mastering-the-art-of-decreasing-decibents-a-guide-to-fading-out-sounds/"><u>Mastering the Art of Decreasing Decibents  A Guide to Fading Out Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-msstore-from-error-0x0-issue-in-windows-os/"><u>Unblocking MsStore From Error 0X0 Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/organize-your-workspace-attaching-this-pc-icon-to-desktop/"><u>Organize Your Workspace: Attaching 'This PC' Icon to Desktop</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-stream-control-tactics-10-ways-to-unwind-live-play/"><u>[New] Stream Control Tactics  10 Ways to Unwind Live Play</u></a></li>
<li><a href="https://win11.techidaily.com/win11-fixing-persistent-read-only-folders/"><u>Win11: Fixing Persistent Read-Only Folders</u></a></li>
<li><a href="https://audio-editing.techidaily.com/platforms-to-download-and-listen-to-dj-music-for-2024/"><u>Platforms to Download and Listen to DJ Music for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-surprise-your-friends-with-these-unheard-memes/"><u>In 2024, Surprise Your Friends with These Unheard Memes</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/captivating-audience-leading-5-tiktok-font-generators-of-2023-for-2024/"><u>Captivating Audience  Leading 5 TikTok Font Generators of 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/making-the-most-of-windows-11-using-dev-drive-effectively/"><u>Making the Most of Windows 11: Using Dev Drive Effectively</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-art-of-synchronized-streams-implementing-smooth-volume-level-changes-using-obs/"><u>New 2024 Approved The Art of Synchronized Streams Implementing Smooth Volume Level Changes Using OBS</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-errors-with-proper-use-of-winservicesexe/"><u>Avoiding Errors with Proper Use of Winservices.exe</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-taskbar-size-tweaks/"><u>Mastering Windows 11 Taskbar Size Tweaks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-apex-productions-audit-studio-25-breakdown-2023/"><u>In 2024, Apex Productions Audit  Studio 25 Breakdown, 2023</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-line-up-of-artistic-software-for-windows-10/"><u>The Ultimate Line-Up of Artistic Software for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-sluggish-windows-printer/"><u>Troubleshoot Sluggish WIndows Printer</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-iphone-7-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>Unlocking iPhone 7 Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-overcoming-geforce-nows-xc0f1103f-problem-in-win11/"><u>Guides to Overcoming GeForce Now’s Xc0f1103f Problem in Win11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-top-10-gratuitous-video-chats-with-desktop-viewing/"><u>[Updated] In 2024, Top 10 Gratuitous Video Chats with Desktop Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-configuring-windows-data-sources-by-odbc/"><u>Accessing and Configuring Windows Data Sources by ODBC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-key-combinations-for-effortless-recalibration/"><u>Mastering Windows: Key Combinations for Effortless Recalibration</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-file-transfers-in-battlenet-windows/"><u>Mastering Fast File Transfers in Battle.net Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-lyric-video-magic-top-online-tools-to-bring-your-songs-to-life/"><u>Updated 2024 Approved Lyric Video Magic Top Online Tools to Bring Your Songs to Life</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-simplified-guide-crafting-and-altering-multisnap-stories/"><u>[New] In 2024, Simplified Guide  Crafting & Altering Multisnap Stories</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-an-unadulterated-system-restart-in-windows-11/"><u>Achieving an Unadulterated System Restart in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-the-disparity-between-remote-windows-upgrades-and-purchases/"><u>Evaluating the Disparity Between Remote Windows Upgrades & Purchases</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-androids-very-own-podcasters/"><u>2024 Approved  Android's Very Own Podcasters</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-10-youtube-tips-for-teachers/"><u>[New] In 2024, 10 YouTube Tips for Teachers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-11-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-11-overcoming-5ghz-wi-fi-barriers/"><u>Breaking Down Windows 11: Overcoming 5GHz Wi-Fi Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-for-bulk-folder-formation-in-windows-1011/"><u>Efficient Methods for Bulk Folder Formation in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-app-size-metrics-in-windows/"><u>Navigating Through App Size Metrics in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/commanding-control-navigating-the-windows-print-hub/"><u>Commanding Control: Navigating the Windows Print Hub</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-elevate-your-content-youtube-movie-maker-101/"><u>2024 Approved  Elevate Your Content  YouTube Movie Maker 101</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/direct-unwatermarked-tiktok-content-download-to-iphone/"><u>Direct Unwatermarked TikTok Content Download to iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-basics-windows-system-configuration/"><u>Master the Basics: Windows System Configuration</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-meme-code-principles-of-viral-video-content-creation-for-2024/"><u>The Meme Code  Principles of Viral Video Content Creation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-repairing-windows-based-pen-tablets/"><u>Guide: Repairing Windows-Based Pen Tablets</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-final-touch-youtube-outro-essentials-plus-premier-creator-list-for-2024/"><u>The Final Touch  YouTube Outro Essentials + Premier Creator List for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-samsung-galaxy-f34-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP on Samsung Galaxy F34 5G?</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-windows-10-top-new-apps-and-games-for-your-pc/"><u>[New] 2024 Approved  Windows 10  Top New Apps & Games for Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3d11-gpu-error-on-windows-11-and-10/"><u>Troubleshooting D3D11 GPU Error on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/keep-it-neat-how-to-make-windows-recycle-bin-self-cleanse/"><u>Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-strategies-for-finding-and-using-a-lost-iphone-x/"><u>In 2024, Top Strategies for Finding & Using a Lost iPhone X</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-safe-ways-to-download-and-convert-youtubes-audios-as-mp3/"><u>[New] Safe Ways to Download and Convert YouTube's Audios as MP3</u></a></li>
<li><a href="https://win11.techidaily.com/faster-booting-window-11s-boot-delay-adjustment-explained/"><u>Faster Booting: Window 11'S Boot Delay Adjustment Explained</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-taskbar-while-running-full-screen-edges/"><u>Unveiling Hidden Taskbar While Running Full Screen Edges</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-sweets-and-snacks-tiktoks-top-food-trends/"><u>[Updated] 2024 Approved  Sweets & Snacks  TikTok's Top Food Trends</u></a></li>
<li><a href="https://win11.techidaily.com/master-windows-integration-with-steam-deck/"><u>Master Windows Integration with Steam Deck</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-perfecting-your-technique-a-vr-recordists-manual/"><u>In 2024, Perfecting Your Technique  A VR Recordist's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-file-damaged-message-error-0x80070570-in-windows-oses/"><u>Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-vivo-x-fold-2-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Vivo X Fold 2 Device</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-to-reclaim-blank-login-screen-on-windows-11/"><u>Fixes to Reclaim Blank Login Screen on Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-unlock-chromecasts-full-potential-how-to-stream-local-videos-on-windows-mac-android-and-ios/"><u>New 2024 Approved Unlock Chromecasts Full Potential How to Stream Local Videos on Windows, Mac, Android, and iOS</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-defeat-bot-intruders-elevate-video-engagement/"><u>[New] 2024 Approved  Defeat Bot Intruders, Elevate Video Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-bsod-traces-within-windows-108/"><u>Understanding BSOD Traces Within Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-free-media-tools-for-windows-pcs/"><u>Explore the Finest Free Media Tools for Windows PCs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/enhancing-visual-storytelling-with-impeccable-voice-over-for-2024/"><u>Enhancing Visual Storytelling with Impeccable Voice Over for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-how-to-use-twitter-archive-for-2024/"><u>[Updated] How to Use Twitter Archive for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-grouped-taskbar-symbols-on-windows-11/"><u>Clearing Grouped Taskbar Symbols on Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/spark-creativity-get-to-know-windows-11s-movie-maker-app-for-2024/"><u>Spark Creativity  Get to Know Windows 11'S Movie Maker App for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/instant-setup-acquiring-adobe-reader-via-ms-store/"><u>Instant Setup: Acquiring Adobe Reader via MS Store</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlock-the-secrets-for-a-viral-instagram-account-gain-fans-and-verified-status-in-less-than-150-characters-for-2024/"><u>[New] Unlock the Secrets for a Viral Instagram Account  Gain Fans and Verified Status in Less Than 150 Characters for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ancestry-unveiled-7-enduring-features-of-windows-11/"><u>Ancestry Unveiled: 7 Enduring Features of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-permission-restrictions-and-open-hidden-folders/"><u>How to Disable Permission Restrictions and Open Hidden Folders</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-seamless-live-broadcasting-on-facebook-a-simple-guide/"><u>[Updated] 2024 Approved  Seamless Live Broadcasting on Facebook  A Simple Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win11-quick-fixes-for-photoshop-not-launching/"><u>Win11: Quick Fixes for Photoshop Not Launching</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-xs-learn-all-4-methods-by-drfone-ios/"><u>How Do You Unlock your Apple iPhone XS? Learn All 4 Methods</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-maximize-your-reach-ideal-video-dimensions-for-instagram-feed-and-stories/"><u>2024 Approved Maximize Your Reach Ideal Video Dimensions for Instagram Feed and Stories</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-best-sound-choices-essential-downloads-guide/"><u>2024 Approved  Best Sound Choices  Essential Downloads Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-potential-with-latest-patch-details/"><u>Unlocking Windows 11'S Potential with Latest Patch Details</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-displaying-messages-errors-in-discord-for-windows/"><u>Fixing Non-Displaying Messages Errors in Discord for Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-understanding-facebooks-new-policies-and-updates/"><u>In 2024, Understanding Facebook's New Policies and Updates</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nveiling-top-5-strategies-boosting-your-brand-via-youtube-marketing-for-2024/"><u>[New] Unveiling Top 5 Strategies  Boosting Your Brand via YouTube Marketing for 2024</u></a></li>
</ul></div>

---
title: "The Chronometer's Comeback: Recovering Windows Time Service"
date: 2024-07-13T10:33:38.913Z
updated: 2024-07-14T10:33:38.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Chronometer's Comeback: Recovering Windows Time Service"
excerpt: "This Article Describes The Chronometer's Comeback: Recovering Windows Time Service"
keywords: Comeback Windows Time,Time Service Restore,Windows Time Repair,ChronoSync in Windows,Reviving TimeService,Timeline Recovery,Windows Time Fixation
thumbnail: https://thmb.techidaily.com/f5fbbf41453d9824bf6879798120e6de2082db27f668f4cb2a72d45c0fe37f64.jpg
---

## The Chronometer's Comeback: Recovering Windows Time Service

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-your-apple-iphone-12-pro-max-from-your-apple-id-by-drfone-ios/"><u>In 2024, How To Unlink Your Apple iPhone 12 Pro Max From Your Apple ID</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pro-level-webcams-the-ultimate-choice-for-your-podcasts/"><u>Pro Level Webcams  The Ultimate Choice for Your Podcasts</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-echoes-in-editing-innovative-methods-for-seamlessly-combining-sound-and-video/"><u>Updated Echoes in Editing Innovative Methods for Seamlessly Combining Sound and Video</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-leveraging-xml-and-ttml-for-cutting-edge-srt-creation-processes/"><u>[New] In 2024, Leveraging XML & TTML for Cutting-Edge SRT Creation Processes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-win1011-screen-flicker/"><u>How to Quickly Resolve WIN10/11 Screen Flicker</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-clandestine-windows-11-taskbar-seeker/"><u>Accessing Clandestine Windows 11 Taskbar Seeker</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-handbook-to-github-desktop-and-windows-integration/"><u>The Beginner's Handbook to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/heroic-quests-ranking-gaming-epics-in-action-adventure/"><u>Heroic Quests  Ranking Gaming Epics in Action-Adventure</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-say-goodbye-to-imovie-the-best-video-editing-software-for-windows-10/"><u>Updated Say Goodbye to iMovie The Best Video Editing Software for Windows 10</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-create-your-own-luts-for-your-video/"><u>How to Create Your Own LUTs for Your Video</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-eradicate-fluctuating-display-on-windows-1011/"><u>Expert Tips to Eradicate Fluctuating Display on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-in-the-digital-age-with-these-best-windows-tools/"><u>Boosting Efficiency in the Digital Age with These Best Windows Tools</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-10-telegram-spy-tools-on-apple-iphone-13-mini-for-parents-drfone-by-drfone-virtual-ios/"><u>Top 10 Telegram Spy Tools On Apple iPhone 13 mini for Parents | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-ultimate-blueprint-for-setting-up-google-meet-for-2024/"><u>[Updated] The Ultimate Blueprint for Setting Up Google Meet for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-ensuring-accurate-age-on-tiktok/"><u>2024 Approved  Step-by-Step  Ensuring Accurate Age on TikTok</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-yt-presence-and-skyrocket-to-1000plus-fans/"><u>[New] 2024 Approved  Elevate Your YT Presence and Skyrocket To 1000+ Fans</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-failure-codes/"><u>Overcoming Windows 10/11 Failure Codes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-create-stunning-movies-online-for-free-top-9-options/"><u>Updated In 2024, Create Stunning Movies Online for Free Top 9 Options</u></a></li>
<li><a href="https://win11.techidaily.com/freezing-wi-fi-mouse-how-to-reset-and-restore-functionality-in-windows/"><u>Freezing Wi-Fi Mouse? How to Reset and Restore Functionality in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-temporal-twist-mastering-video-flipping-in-snapchat/"><u>[Updated] 2024 Approved  Temporal Twist  Mastering Video Flipping in Snapchat</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-with-the-datamoshing-effect-the-user-can-damage-the-video-clips-to-offer-a-glitch-effect-the-article-introduces-datamosh-after-effects-its-wor/"><u>2024 Approved With the Datamoshing Effect, the User Can Damage the Video Clips to Offer a Glitch Effect. The Article Introduces Datamosh After Effects Its Workability in the Industry</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-optimal-video-techniques-to-dominate-freefire-vlogs/"><u>[New] 2024 Approved  Optimal Video Techniques to Dominate FreeFire Vlogs</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-connect-and-entertain-stream-xbox-games-on-the-worlds-stage-facebook/"><u>[New] 2024 Approved  Connect & Entertain  Stream Xbox Games on the World's Stage - Facebook</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-time-saving-tactics-for-saving-google-voice-speeches/"><u>[Updated] In 2024, Time-Saving Tactics for Saving Google Voice Speeches</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users.</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/7-excellent-screen-capture-tools/"><u>7 Excellent Screen Capture Tools</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-assess-and-adapt-image-dimensions-for-2024/"><u>New Assess and Adapt Image Dimensions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-11-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-tasks-as-an-admin-in-windows-11/"><u>Securely Manage Tasks as an Admin in Windows 11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/boost-creativity-in-photos-the-ultimate-list-of-20-snap-lenses/"><u>Boost Creativity in Photos  The Ultimate List of 20 Snap Lenses</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win1011-unraveling-error-code-0x800704b3/"><u>Fixing Win10/11: Unraveling Error Code 0X800704B3</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1716069987601-new-2024-approved-best-linux-screen-capture-software-ranked/"><u>[New] 2024 Approved  Best Linux Screen Capture Software Ranked!</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-k70e-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi K70E Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/1716464169834-phenomenal-flair-youtubes-ultimate-video-magic/"><u>Phenomenal Flair  YouTube’s Ultimate Video Magic!</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-optimize-windows-powershell-script-policies/"><u>Activate and Optimize Windows PowerShell Script Policies</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-effective-rgb-light-settings-in-win11/"><u>Tips for Effective RGB Light Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-management-skills-multi-zip-extraction-techniques/"><u>Elevate Your File Management Skills: Multi-Zip Extraction Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-11-quick-selective-copy-and-move/"><u>Unlock the Power of Windows 11: Quick Selective Copy & Move</u></a></li>
<li><a href="https://win11.techidaily.com/a-systematic-approach-to-rejuvenating-your-media-software/"><u>A Systematic Approach to Rejuvenating Your Media Software</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-fps-conundrum-deciding-between-standard-and-higher-video-speeds/"><u>[Updated] The FPS Conundrum  Deciding Between Standard & Higher Video Speeds</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-free-tools-for-efficient-screen-recording-on-windows-os/"><u>2024 Approved  Free Tools for Efficient Screen Recording on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-expert-tips-for-mastering-iphones-sound-capture/"><u>[New] In 2024, Expert Tips for Mastering iPhone's Sound Capture</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-unreachable-issue-in-windows/"><u>Resolving 'Network Unreachable' Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-expert-techniques-to-download-tiktoks-without-apple-watermarks-for-2024/"><u>[New] Expert Techniques to Download TikToks without Apple Watermarks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-customize-windows-10-and-11-with-winbubble/"><u>8 Ways to Customize Windows 10 and 11 With WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/path-pursuit-6-efficient-strategies-for-copying-file-and-folder-paths-in-windows-11/"><u>Path Pursuit: 6 Efficient Strategies for Copying File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-shortened-terms-alias-and-application-lifecycle/"><u>Diving Into Shortened Terms: Alias & Application Lifecycle</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-xiaomi-redmi-a2-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Xiaomi Redmi A2</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnect-error-during-discord-setup-in-windows-os/"><u>Fixing Disconnect Error During Discord Setup in Windows OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-motorola-edge-40-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Motorola Edge 40</u></a></li>
<li><a href="https://win11.techidaily.com/continuous-edge-background-on-windows-11-tips/"><u>Continuous Edge Background on Windows 11 - Tips</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-facebooks-premier-10-music-clip-showcase/"><u>2024 Approved  Facebook's Premier 10 Music Clip Showcase</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-11s-fatal-error/"><u>Deciphering and Resolving Windows 11'S Fatal Error</u></a></li>
</ul></div>

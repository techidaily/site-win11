---
title: Advanced Techniques to Clear Microsoft Defender History on PCs
date: 2024-07-13T11:21:35.644Z
updated: 2024-07-14T11:21:35.644Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Techniques to Clear Microsoft Defender History on PCs
excerpt: This Article Describes Advanced Techniques to Clear Microsoft Defender History on PCs
keywords: Clearing Defender History,Defender History Erase,Microsoft Defender Cleanse,XP Defender Delete,Windows Defender Cleanup,Removing Defender Logs,Safe Mode Defender Wipe
thumbnail: https://thmb.techidaily.com/1ed4f091728645649c840ae907d2be87aba494a53f4cf1942b1dcf1c240fc190.jpg
---

## Advanced Techniques to Clear Microsoft Defender History on PCs

 Windows Defender is Microsoft's antivirus built into your Windows PC to protect you from viruses, malware threats, and attacks. It maintains a record of its scans and actions in its Protection History folder.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

## What Is the Microsoft Defender Protection History? Why Should You Clear It?

 One of the best antivirus for your PC, [Windows Defender keeps getting better with some powerful upgrades](https://www.makeuseof.com/microsoft-defender-riskai-upgrade/). The detections made by Windows Defender appear on the Protection History page—which means you can view actions that Microsoft Defender Antivirus has taken on your behalf. These would be scans done to identify and block malware and other threats. And also the recommendations (highlighted in red or yellow) for actions you should take.

 You also have access to all this information in a clear and easily understandable form, including Potentially Unwanted Apps that have been removed, or key services that have been turned off. The Protection History will also show the detections that appear while performing a Windows Defender Offline scan.

![Protection History Page in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ProtectionHistory1.jpg)

 Though Windows Defender keeps the history of its detections for 30 days, you can clear it before that time if you need to—for example, when a lot of scan logs have accumulated. Clearing the Protection History would help you make space on your PC and keep Defender running smoothly. Remember, you must be signed in as an administrator to clear the protection history so [do check if you have administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/).

 Now let's see four easy ways to clear Protection History in Windows 10 and 11\.

## 1\. How to Clear the Microsoft Defender's Protection History Folder

 You can manually clear the Protection History by deleting the contents of the Service folder in the Windows Defender folder using File Explorer. Here's how:

1. Press **Windows + R** keys to bring up the Run box.
2. Copy and paste the path below and click on **OK** or hit **enter:** **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History**  
![Defender History Folder Path Typed in Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/open-defender-history-folder-via-run.jpg)
3. You can also paste the **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History** path in the File Explorer navigation bar and then hit **enter**.  
![Defender History Folder Path in File Explorer Navigation Bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/defender-history-folder-path-in-file-explorer.jpg)  
 Alternatively, you can navigate to the **Defender Protection History** folder using the above path in File Explorer. If you don't see the **ProgramData** folder when you open the Local Drive, select **View** and then tick the box next to **Hidden items**.  
![Click Hidden Items under View to See ProgramData Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Click-Hidden-Items-under-View-to-See-ProgramData-Folder.jpg)
4. Open the **Service** folder and select all the files inside it. **Right-click** and select **Delete** to clear all the files. Then exit File Explorer.  
![Select Files in History Folder and Delete Them](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Select-Files-in-History-Folder-and-Delete-Them.jpg)
5. Next, search for **Windows Security** and open it.
6. Under **Virus & threat protection** click on **Manage settings**.  
![Virus and Threat Protection Settings in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Virus-and-Threat-Protection-in-Windows-Security.jpg)
7. Finally, toggle the button to **Off** and then to **On** again, for **Real-Time protection** and **Cloud-delivered protection**.

## 2\. How to Clear the Microsoft Defender Protection History Using the Event Viewer

 You can also manually clear the Defender Protection History via the [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/)—a useful app to analyze the event logs on your device. Here's how:

1. First, do a Windows search for **Event Viewer** and click on the app result under **Best match** to open **Event Viewer.**
2. Under the **Event Viewer (Local)** on the left pane, expand the **Applications and Services Logs**.
3. Under **Applications and Services Logs**, click on the down arrow next to the **Microsoft** folder.
4. Click on **Windows** in the left pane to open the list of Windows files on the middle pane.
5. Scroll down through the list of files on the middle pane to find **Windows Defender**.  
![Windows Defender selected in Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-in-Event-Viewer.jpg)
6. Double-click on **Windows Defender**.
7. Then right-click on **Operational** and select **Open** to view all the past logs.  
![Open Operational Option to View Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Operational-Option-to-View-Defender-Logs.jpg)
8. Now you can right-click on **Operational** in the left pane and choose **Clear Log**. Or click on **Clear Log** on the right pane under **Actions**.  
![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  
![Options to Clear Logs or Save and Clear Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Clear-and-Save-and-Clear-Options-for-Defender-Logs.jpg)

## 3\. How to Clear the Microsoft Defender Protection History via PowerShell

 What if you want the Protection History to clear automatically after a specific number of days? You can also use a PowerShell command to do that. Let's see how to do this:

1. Type **PowerShell** in the search bar. Right-click on **Windows PowerShell** under **Best match** and select **Run as administrator**. Or choose **Run as administrator** on the right search pane.
2. Click **Yes** on the UAC prompt that appears.
3. The **Administrator: PowerShell** window will open up. Type or copy and paste the following command and then hit **enter**:

`Set-MpPreference -ScanPurgeItemsAfterDelay 7`

![Command to Clear Protection History in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-Command-to-Clear-Protection-History.jpg)

 The number **7** at the end of the command is the number of days after which the protection history logs will be cleared. Just change that number to specify when you want the protection history to be cleared. And it will be cleared automatically.

## 4\. How to Clear the Microsoft Defender Protection History Using the Group Policy Editor

 If you have a PC with Windows 10 Pro, Windows 11 Pro, or a higher version, you can also use the Group Policy Editor to clear the Defender Protection History automatically. Though there are solutions to [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) too. But let's see how to clear Protection History via Group Policy Editor in Windows Pro and higher versions:

1. Press **Win + R** keys to open the Run box. Type **gpedit.msc** to open the **Local Group Policy Editor**. Or just type **gpedit** in the search bar and click on **Edit Group Policy** under **Best match** to open it.
2. In the **Local Group Policy Editor**, on the left pane under **Computer Configuration**, expand **Administrative Templates** by clicking on the down arrow next to it.
3. Inside the **Administrative Templates** folder, click on **Windows Components** and the list of its components would come up on the middle pane of the **Group Policy Editor**.
4. Then scroll down to find **Windows Defender Antivirus** and double-click on it.  
![Navigate to Windows Defender Antivirus in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-Antivirus-in-Group-Policy-Editor.jpg)
5. In the list of **Windows Defender** items, **double-click** on the **Scan** folder.
6. In the right pane, **double-click** on **Turn on removal of items from scan history folder**. Or click **Edit policy setting** in the middle pane. This policy setting defines the number of days items should be kept in the scan history folder before being permanently removed.  
![Turn on Removal of Items Policy in Defender Scan Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Edit-Removal-of-Items-Policy-in-Defender-Scan-Folder.jpg)
7. Next, select **Edit policy setting** to open the policy window. It would be showing **Not Configured** by default. To set the number of days, toggle on the button next to **Enabled**. The default number of days, which is **30**, would then be set. If you set the number of days to zero, items will be kept forever and will not be automatically removed. So just change the days to whenever you want the items to be removed. Finally, click **Apply** and then **OK**.  
![Specify Number of Days to Remove Scan Items in Defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Set-Number-of-Days-to-Remove-Scan-Items.jpg)

 Now, you won't need to manually clear Protection History every time—the items in the scan history folder would be deleted automatically after the days you've specified.

## Clear the Microsoft Defender Protection History Whenever You Want

 If you ever want to clear Defender Protection History, you know how easy it is to do it through any of the four ways discussed above. If you would want to refer to the Protection History logs later, you can use the Save and Clear option while clearing Protection History using Event Viewer.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-realme-narzo-60-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Realme Narzo 60 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-boot-failures-8-fixes-for-virtual-machines-on-wm11os/"><u>Overcome Boot Failures: 8 Fixes for Virtual Machines on WM11OS</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-prodigies-top-10-gaming-ladies-on-yt-for-2024/"><u>Pixel Prodigies  Top 10 Gaming Ladies on YT for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-windows-11-desktop-sparkle-with-lively-wallpaper-art/"><u>Make Your Windows 11 Desktop Sparkle with Lively Wallpaper Art</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now</u></a></li>
<li><a href="https://extra-support.techidaily.com/nighttime-iphone-photography-secrets-revealed-for-2024/"><u>Nighttime iPhone Photography Secrets Revealed for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-superior-8-filter-trios-for-broadcast-excellence/"><u>In 2024, Superior 8 Filter Trios for Broadcast Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-addressing-windows-non-response-to-powershell-command/"><u>Steps for Addressing Windows Non-Response to PowerShell Command</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sector-mastering-windows-methods-for-adapter-velocity-check/"><u>Speed Sector: Mastering Windows Methods for Adapter Velocity Check</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-dive-into-the-art-of-asmr-recording-a-comprehensive-overview/"><u>[Updated] Dive Into the Art of ASMR Recording – A Comprehensive Overview</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-re-establishing-managed-status-on-windows-11/"><u>Comprehensive Guide for Re-Establishing Managed Status on Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-keeping-up-with-aspect-ratios-for-twitter-content/"><u>2024 Approved  Keeping Up with Aspect Ratios for Twitter Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-perfectly-filled-no-ad-android-screen-recording/"><u>[New] 2024 Approved  Perfectly Filled  No-Ad Android Screen Recording</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-the-art-of-setting-yourself-aside-from-influencer-currents/"><u>2024 Approved  The Art of Setting Yourself Aside From Influencer Currents</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-non-functional-email-banners-for-office-users/"><u>Reviving Non-Functional Email Banners for Office Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/change-your-virtual-rooms-palette-with-google-meet/"><u>Change Your Virtual Room's Palette with Google Meet</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-pro-stock-market-strategies-in-yt-reviews/"><u>[New] Pro Stock Market Strategies in YT Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-overcoming-geforce-x0001-on-w10w11-pcs/"><u>Quick Tips: Overcoming GeForce X0001 on W10/W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sharing-with-the-top-5-software-picks-for-pcs/"><u>Streamlined Sharing with the Top 5 Software Picks for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-efficiency-via-powertoys/"><u>Accelerate Keyboard Efficiency via PowerToys</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-echoes-of-excellence-10-strategies-for-superior-sound-quality/"><u>2024 Approved  Echoes of Excellence  10 Strategies for Superior Sound Quality</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-windows-laptop-lag-on-dual-screens/"><u>Overcoming the Hurdle of Window's Laptop Lag on Dual Screens</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-what-is-an-ai-avatar/"><u>Updated 2024 Approved What Is an AI Avatar?</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-memes-that-spark-global-conversation/"><u>2024 Approved  Memes that Spark Global Conversation</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-typing-experience-changing-layouts-on-windows-11/"><u>Tailoring Your Typing Experience: Changing Layouts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-reviving-windows-or-beyond/"><u>Rethink Reviving: Windows or Beyond?</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-uncertainty-check-cpu-generation-on-windows-8-ways/"><u>Avoid Uncertainty – Check CPU Generation on Windows (8 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-the-search-function-in-windows-11-for-you/"><u>Adapting the Search Function in Windows 11 for You</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/pioneering-change-a-step-by-step-guide-to-reinventing-your-tiktok-identity/"><u>Pioneering Change  A Step-by-Step Guide to Reinventing Your TikTok Identity</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-windows-voice-recording/"><u>A Step-By-Step Guide to Windows Voice Recording</u></a></li>
<li><a href="https://win11.techidaily.com/windows-best-cryptographic-solutions-ranked-148-chars/"><u>Window's Best Cryptographic Solutions Ranked (148 Chars)</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-samsung-galaxy-z-flip-5-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Samsung Galaxy Z Flip 5 Phones with/without a PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-pinnacle-mac-recording-options-top-5-for-clarity-for-2024/"><u>[New] Pinnacle Mac Recording Options  Top 5 for Clarity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-microsofts-smartguard-in-win-10/"><u>Enabling/Disabling Microsoft's SmartGuard in Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-reopen-stuck-adobe-photoshop-in-windows/"><u>Guidelines to Reopen Stuck Adobe Photoshop in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-requires-privilege-error-code-0x80070522-in-windows-devices/"><u>Eradicating Requires Privilege Error (Code 0X80070522) in Windows Devices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-bridging-the-gap-integrating-spotify-and-youtube-music-playlists/"><u>[Updated] Bridging the Gap  Integrating Spotify and YouTube Music Playlists</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-administrator-experience-via-terminals-every-time/"><u>Unhindered Administrator Experience via Terminals Every Time</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-tips-and-tricks-for-windows-hdr-video-workflows/"><u>[New] Tips and Tricks for Windows HDR Video Workflows</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-demystified-how-to-resolve-windows-crashes-quickly/"><u>Blue Screen Demystified: How To Resolve Windows Crashes Quickly</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mirror-movies-a-guide-to-flipping-your-youtube-video-upside-down/"><u>2024 Approved  Mirror Movies  A Guide to Flipping Your YouTube Video Upside Down</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-voice-capture-made-easy-the-ultimate-mac-users-guide-for-high-quality-recordings/"><u>2024 Approved Voice Capture Made Easy The Ultimate Mac Users Guide for High-Quality Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-unlock-the-secrets-of-measuring-ethernet-speeds/"><u>Windows Wonders: Unlock the Secrets of Measuring Ethernet Speeds</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-explore-advanced-video-control-in-youtubes-playback-features/"><u>[Updated] 2024 Approved  Explore Advanced Video Control in YouTube’s Playback Features</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-reliable-voice-commands-for-valorant-gaming/"><u>Ensuring Reliable Voice Commands for Valorant Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-technologies-in-microsofts-ai-hub/"><u>Demystifying the Technologies in Microsoft's AI Hub</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-easy-steps-to-deactivate-igtv/"><u>[Updated] Easy Steps to Deactivate IGTV</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-offline-android-delights-9-most-addictive-mobile-games/"><u>[New] 2024 Approved  Offline Android Delights  9 Most Addictive Mobile Games</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-peek-into-personality-traits-top-6-quizzes-to-determine-youtuber-preferences/"><u>[Updated] Peek Into Personality Traits  Top 6 Quizzes to Determine YouTuber Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-pcs-current-window-background-file/"><u>How to Locate PC's Current Window Background File</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-greyed-out-display-changes-on-windows-system/"><u>Eliminate Greyed-Out Display Changes on Windows System</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-ensuring-long-term-access-to-itunes-videos-for-2024/"><u>[New] Ensuring Long-Term Access to iTunes Videos for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-9-best-free-and-easy-editing-apps-you-should-know/"><u>2024 Approved  9 Best Free and Easy Editing Apps You Should Know</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-saturating-the-market-precision-in-sharing-through-shorts/"><u>[Updated] In 2024, Saturating the Market  Precision in Sharing Through Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-gallery-in-file-explorer-in-windows-11/"><u>How to Enable the Gallery in File Explorer in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unmatched-tech-elevation-through-srs-enhancement/"><u>[Updated] Unmatched Tech Elevation Through SRS Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-canary-your-security-ally/"><u>Intro to Windows Canary: Your Security Ally</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-concept-art-to-cinematic-masterpiece-utilizing-luts-from-cg-central-for-2024/"><u>From Concept Art to Cinematic Masterpiece  Utilizing Luts From CG Central for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transition-tunes-mastering-crossfading-in-music/"><u>[New] Transition Tunes  Mastering Crossfading in Music</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-pc-power-for-distributed-video-conversion-by-tdarr/"><u>Optimize PC Power for Distributed Video Conversion by Tdarr</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-bypassing-hiccups-and-blockades/"><u>Streamlining Windows 11: Bypassing Hiccups & Blockades</u></a></li>
</ul></div>

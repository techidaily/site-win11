---
title: Guidelines for Windows 11 VM Reset
date: 2024-07-13T10:47:20.918Z
updated: 2024-07-14T10:47:20.918Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines for Windows 11 VM Reset
excerpt: This Article Describes Guidelines for Windows 11 VM Reset
keywords: Win11 VM Reset Guide,Windows 11 Recovery Steps,VM Setup Procedures,System Restore in Win11,Virtual Machine Settings,Rebooting Win11 VMs,Reinstalling Windows 11 OS
thumbnail: https://thmb.techidaily.com/07f3d5f057a0a1f3c1d2492add732e27fc47138ba4a1808a078297c558520a47.png
---

## Guidelines for Windows 11 VM Reset

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://win11.techidaily.com/accessing-clandestine-windows-11-taskbar-seeker/"><u>Accessing Clandestine Windows 11 Taskbar Seeker</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-new-year-new-animations-the-10-best-2d-animation-software-for-2024/"><u>Updated New Year, New Animations The 10 Best 2D Animation Software for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-unlocking-the-secrets-of-text-styling-in-discord/"><u>[Updated] In 2024, Unlocking the Secrets of Text Styling in Discord</u></a></li>
<li><a href="https://win11.techidaily.com/instant-repair-tactics-for-windows-photo-app-malfunctions/"><u>Instant Repair Tactics for Windows Photo App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-eradicate-fluctuating-display-on-windows-1011/"><u>Expert Tips to Eradicate Fluctuating Display on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-xiaomi-13-ultra-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Xiaomi 13 Ultra to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-tailoring-sound-techniques-for-altering-audio-speed-and-pitch-in-adobe-rush/"><u>Updated In 2024, Tailoring Sound Techniques for Altering Audio Speed & Pitch in Adobe Rush</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-step-by-step-guide-how-to-translate-twitter-video-easily-for-2024/"><u>New Step-by-Step Guide How to Translate Twitter Video Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-a-harmonious-link-spotify-with-discord/"><u>[Updated] 2024 Approved  A Harmonious Link  Spotify with Discord</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-11-quick-selective-copy-and-move/"><u>Unlock the Power of Windows 11: Quick Selective Copy & Move</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/swapping-sequence-a-simple-guide-to-reversed-playlists-for-2024/"><u>Swapping Sequence  A Simple Guide to Reversed Playlists for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-beyond-simplicity-exploring-the-intricacies-of-youtubes-view-count-algorithm/"><u>[New] 2024 Approved  Beyond Simplicity  Exploring the Intricacies of YouTube’s View Count Algorithm</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-handbook-to-github-desktop-and-windows-integration/"><u>The Beginner's Handbook to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-comprehensive-list-of-non-udemy-e-learning-success-stories/"><u>2024 Approved  Comprehensive List of Non-Udemy E-Learning Success Stories</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-design-your-signature-discord-pfp-for-standout-presence/"><u>[New] Design Your Signature Discord PFP for Standout Presence</u></a></li>
<li><a href="https://win11.techidaily.com/continuous-edge-background-on-windows-11-tips/"><u>Continuous Edge Background on Windows 11 - Tips</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-huawei-p60mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Huawei P60Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-spark-20c-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Spark 20C to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-instant-inspiration-free-video-intro-kits/"><u>[Updated] Instant Inspiration - Free Video Intro Kits</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-shortened-terms-alias-and-application-lifecycle/"><u>Diving Into Shortened Terms: Alias & Application Lifecycle</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mov-files-on-samsung-galaxy-s23-fe-by-aiseesoft-video-converter-play-mov-on-android/"><u>How do you play .mov files on Samsung Galaxy S23 FE ?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-premium-chrome-modifiers-for-streamlined-vimeo-content/"><u>[Updated] 2024 Approved  Premium Chrome Modifiers for Streamlined Vimeo Content</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-facebook-to-mp3-best-online-conversion-tools-ranked/"><u>In 2024, Facebook to MP3 Best Online Conversion Tools Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-11-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-unreachable-issue-in-windows/"><u>Resolving 'Network Unreachable' Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/path-pursuit-6-efficient-strategies-for-copying-file-and-folder-paths-in-windows-11/"><u>Path Pursuit: 6 Efficient Strategies for Copying File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-management-skills-multi-zip-extraction-techniques/"><u>Elevate Your File Management Skills: Multi-Zip Extraction Techniques</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exclusive-selection-of-vr-for-drone-pilots/"><u>[Updated] Exclusive Selection of VR for Drone Pilots</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ideas-on-boosting-gopro-energy-retention/"><u>[Updated] Ideas on Boosting GoPro Energy Retention</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-acoustic-amplification-of-social-media-content-on-facebook/"><u>2024 Approved  Acoustic Amplification of Social Media Content on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-installation-windows-cab-files-unpacked-and-utilized/"><u>Initiating Installation: Windows CAB Files Unpacked and Utilized</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-beat-hunters-delight-accessible-online-scanners/"><u>[New] 2024 Approved  Beat Hunters Delight  Accessible Online Scanners</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-how-to-start-and-sustain-an-indie-podcast-hit/"><u>2024 Approved  How to Start & Sustain an Indie Podcast Hit</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-descriptive-folders-in-windows-11/"><u>Boosting Productivity with Descriptive Folders in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-win1011-screen-flicker/"><u>How to Quickly Resolve WIN10/11 Screen Flicker</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-xiaomi-14-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-how-to-create-a-live-stream-on-youtube-with-the-best-webcams/"><u>In 2024, How to Create a Live Stream on YouTube With the Best Webcams</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win1011-unraveling-error-code-0x800704b3/"><u>Fixing Win10/11: Unraveling Error Code 0X800704B3</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-in-the-digital-age-with-these-best-windows-tools/"><u>Boosting Efficiency in the Digital Age with These Best Windows Tools</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-efficient-ad-elimination-select-7-android-adblockers/"><u>[Updated] Efficient Ad Elimination  Select 7 Android AdBlockers</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-effective-rgb-light-settings-in-win11/"><u>Tips for Effective RGB Light Settings in Win11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-celebrity-evanescent-video-review-for-2024/"><u>[Updated] Celebrity Evanescent Video Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnect-error-during-discord-setup-in-windows-os/"><u>Fixing Disconnect Error During Discord Setup in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/a-systematic-approach-to-rejuvenating-your-media-software/"><u>A Systematic Approach to Rejuvenating Your Media Software</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-tasks-as-an-admin-in-windows-11/"><u>Securely Manage Tasks as an Admin in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-11s-fatal-error/"><u>Deciphering and Resolving Windows 11'S Fatal Error</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-lan-play-fixes-for-no-connection-woes/"><u>Winning at LAN Play: Fixes for No Connection Woes</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gain-traction-in-the-algorithm-the-insiders-manual-for-featured-channels/"><u>[New] In 2024, Gain Traction in the Algorithm  The Insider's Manual for Featured Channels</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-essential-fix-re-emerge-missing-watch-icon-2023/"><u>In 2024, Essential Fix  Re-Emerge Missing Watch Icon, 2023</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/editing-essentials-your-go-to-guide-for-beginner-vloggers/"><u>Editing Essentials  Your Go-To Guide for Beginner Vloggers</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-google-pixel-8-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Google Pixel 8? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/mastering-the-technique-playing-videos-in-slow-motion-on-your-iphone-like-a-pro/"><u>Mastering the Technique Playing Videos in Slow Motion on Your iPhone Like a Pro</u></a></li>
</ul></div>

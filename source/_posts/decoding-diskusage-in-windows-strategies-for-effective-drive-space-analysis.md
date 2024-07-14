---
title: "Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis"
date: 2024-07-13T10:22:26.496Z
updated: 2024-07-14T10:22:26.496Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis"
excerpt: "This Article Describes Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis"
keywords: WinDiskSpaceAnalysis,DrivespaceManagement,DiskUsageStrategies,EffectiveStorageUse,WindowsResourceTracking,SpaceOptimizationTips,DriveCapacityInsight
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/eliminate-persistent-boot-related-windows-audio-failures/"><u>Eliminate Persistent Boot-Related Windows Audio Failures</u></a></li>
<li><a href="https://win11.techidaily.com/nine-strategies-for-precise-pdf-conversions-from-powerpoint-windows/"><u>Nine Strategies for Precise PDF Conversions From PowerPoint Windows</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-lifelong-deletion-functions-on-windows-1011-desktop/"><u>Configuring Lifelong Deletion Functions on Windows 10/11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/from-software-to-functionality-ms-workspace-on-windows-1011/"><u>From Software to Functionality: MS Workspace on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolving-error-x800704cf-on-windows-devices/"><u>Guide to Resolving Error X800704CF on Windows Devices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unified-vision-ventures-a-complete-cms-selection-journey/"><u>Unified Vision Ventures  A Complete CMS Selection Journey</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-playable-media-error-xc10100bf/"><u>Overcoming Non-Playable Media Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lag-on-extended-screens/"><u>Addressing Windows Lag on Extended Screens</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-window-resolutions/"><u>Enhancing Your Visual Experience with Window Resolutions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-tiny-tempo-truths-character-beats-exposed/"><u>In 2024, Tiny Tempo Truths  Character Beats Exposed</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-streamline-your-channel-adobe-premiere-to-youtube/"><u>[Updated] Streamline Your Channel  Adobe Premiere to YouTube</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-transform-your-tech-experience-learn-how-to-screen-record-efficiently-for-2024/"><u>[Updated] Transform Your Tech Experience  Learn How to Screen Record Efficiently for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unlock-the-potential-of-live-streaming-facebook-via-obs-devices/"><u>Unlock the Potential of Live Streaming Facebook via OBS Devices</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-the-vertical-video-revolution-how-to-resize-for-maximum-impact/"><u>Updated 2024 Approved The Vertical Video Revolution How to Resize for Maximum Impact</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-site-trust-on-windows-11/"><u>Mastering Site Trust on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-elite-audio-engineers-choice-premium-voice-alteration-tools-for-windows-and-macos-platforms/"><u>New 2024 Approved Elite Audio Engineers Choice Premium Voice Alteration Tools for Windows and macOS Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-tech-titans-android-and-microsoft-pc/"><u>Uniting Two Tech Titans: Android and Microsoft PC</u></a></li>
<li><a href="https://facebook.techidaily.com/apple-decides-its-path-no-mimicking-of-facebooks-metaverse/"><u>Apple Decides Its Path, No Mimicking of Facebook's Metaverse</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-advanced-backup-capabilities/"><u>Unlock Advanced Backup Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-wizardry-unmasking-your-ip/"><u>Command Prompt Wizardry: Unmasking Your IP</u></a></li>
<li><a href="https://extra-tips.techidaily.com/yearly-review-youtubes-most-immersive-stories/"><u>Yearly Review  YouTube's Most Immersive Stories</u></a></li>
<li><a href="https://win11.techidaily.com/first-day-with-windows-11-heres-what-not-to-do-top-7-mistakes/"><u>First Day with Windows 11? Here's What Not to Do! - Top 7 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-meteorological-measurements-on-windows-11-pcs/"><u>Mastering Meteorological Measurements on Windows 11 PCs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-secure-conversation-services-identifying-the-best-platforms-for-stranger-communication/"><u>New Secure Conversation Services Identifying the Best Platforms for Stranger Communication</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-economical-audience-expansion-buy-subscribers-not-time/"><u>[New] In 2024, Economical Audience Expansion  Buy Subscribers, Not Time</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-revolutionize-gaming-sounds-ps5ps4-edition/"><u>[Updated] Revolutionize Gaming Sounds  PS5/PS4 Edition</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-tiktok-aspect-ratio-explained-tips-and-tricks-success/"><u>New TikTok Aspect Ratio Explained Tips and Tricks Success</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-innovation-new-pcs-best-tools-from-msistore/"><u>Accelerated Innovation: New PC's Best Tools From MSIStore</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-6s-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>In 2024, iPhone 6s Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-file-management-altering-timestamps-in-windows/"><u>Cutting-Edge File Management: Altering Timestamps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-to-counteract-accelerated-mice/"><u>Adjusting Windows to Counteract Accelerated Mice</u></a></li>
<li><a href="https://win11.techidaily.com/turning-oculus-quest-into-a-windows-based-vr-device/"><u>Turning Oculus Quest Into a Windows-Based VR Device</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-high-quality-methodology-stitching-gopro-sequences-in-virtual-reality-films-for-2024/"><u>[New] High-Quality Methodology  Stitching GoPro Sequences in Virtual Reality Films for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-experience-new-pcs-ultimate-tools/"><u>Elevate Your Experience: New PC's Ultimate Tools</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-distractions-mastering-wins-on-windows-11/"><u>Avoiding Distractions: Mastering Wins on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-high-performance-navigate-valorant-lag-reduction/"><u>Unlock High Performance: Navigate Valorant Lag Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-clutter-eliminate-onedrive-symbol-from-explorer/"><u>Confronting Clutter: Eliminate OneDrive Symbol From Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-nonexistent-devices-in-os-windows-1011/"><u>Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-installs-time-mastering-grouped-deployments-with-winstall-on-windows-11/"><u>Cutting Down Installs Time: Mastering Grouped Deployments with Winstall on Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-the-ways-for-fee-free-pictorial-clips/"><u>In 2024, Navigating the Ways for Fee-Free Pictorial Clips</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-windows-login-after-failures/"><u>How to Reactivate Windows Login After Failures</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-essential-guide-fetching-twitter-videos-directly-from-mobile/"><u>[Updated] 2024 Approved  Essential Guide  Fetching Twitter Videos Directly From Mobile</u></a></li>
<li><a href="https://data-recovery.techidaily.com/comprehensive-data-restoration-suite-seamless-recovery-for-diverse-file-formats/"><u>Comprehensive Data Restoration Suite - Seamless Recovery for Diverse File Formats</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-accelerated-sound-adjustment-apps-overview/"><u>[New] In 2024, Accelerated Sound Adjustment Apps Overview</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-discover-efficiency-with-these-5-essential-mac-snippers/"><u>[Updated] 2024 Approved  Discover Efficiency with These 5 Essential Mac Snippers</u></a></li>
<li><a href="https://win11.techidaily.com/creating-digital-wonders-on-win11-with-paint-cocreator-the-ultimate-guide-for-ai-image-creation/"><u>Creating Digital Wonders on Win11 With Paint Cocreator: The Ultimate Guide for AI Image Creation</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-the-electrical-footprint-of-your-personal-windows-pc/"><u>Analyzing the Electrical Footprint of Your Personal Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-phone-link-microsofts-bluetooth-connectivity-app/"><u>Unveiling 'Phone Link': Microsoft’s Bluetooth Connectivity App</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-ultimate-ranking-8-best-ios-compatible-daws-for-ipad-and-iphone-enthusiasts-for-2024/"><u>Updated The Ultimate Ranking 8 Best iOS-Compatible DAWs for iPad and iPhone Enthusiasts for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-vivo-x100-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-e84-glitches-on-windows-systems/"><u>Overcoming Steam E84 Glitches on Windows Systems</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2-ways-to-fade-audio-in-ableton/"><u>2 Ways to Fade Audio in Ableton</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-proven-methods-for-professional-video-editing-and-dvd-burning-on-mac/"><u>In 2024, Proven Methods for Professional Video Editing and DVD Burning on Mac</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-system-top-tips-for-black-screen-on-win11/"><u>Jumpstart Your System: Top Tips for Black Screen on Win11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-merging-markets-youtube-and-brand-collaboration-concepts/"><u>2024 Approved  Merging Markets  YouTube and Brand Collaboration Concepts</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-with-personal-touches/"><u>Enhancing Windows 11 with Personal Touches</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-high-res-display-settings-in-windows/"><u>Mastering High-Res Display Settings in Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-stabilize-your-camera-without-buying-a-tripod/"><u>[Updated] In 2024, How to Stabilize Your Camera without Buying a Tripod?</u></a></li>
<li><a href="https://techidaily.com/unlock-iphone-13-pro-lock-with-itunes-by-drfone-ios-unlock-ios-unlock/"><u>Unlock iPhone 13 Pro lock with iTunes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-the-apple-iphone-se-2022-icloud-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing the Apple iPhone SE (2022) iCloud Lock</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-setting-updeactivating-metric-tracker-in-win11/"><u>Mastery: Setting Up/Deactivating Metric Tracker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-performance-with-vm-cache-clear/"><u>Boost PC Performance with VM Cache Clear</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-15-best-apps-to-turn-photos-into-cartoons-and-sketches/"><u>2024 Approved 15 Best Apps to Turn Photos Into Cartoons and Sketches</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-master-the-art-of-sharing-gaming-moments-xboxfb-livestream/"><u>In 2024, Master the Art of Sharing Gaming Moments  Xbox/FB Livestream</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-hues-overcoming-color-issues-on-windows/"><u>Harmonizing Hues: Overcoming Color Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/verifying-your-version-three-ways-for-windows-11/"><u>Verifying Your Version: Three Ways for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-finding-and-fixing-windows-update-issues/"><u>Mastering the Art of Finding and Fixing Windows Update Issues</u></a></li>
</ul></div>

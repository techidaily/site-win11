---
title: "Secure & Efficient Storage: Controlling NTFS Compression in Win11"
date: 2024-07-13T10:58:26.364Z
updated: 2024-07-14T10:58:26.364Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure & Efficient Storage: Controlling NTFS Compression in Win11"
excerpt: "This Article Describes Secure & Efficient Storage: Controlling NTFS Compression in Win11"
keywords: Win11 Compression Control,Secure Storage Techniques,Efficient File Management,NTFS Data Safety,Enhanced File Saving,Optimized Storage Efficiency,Advanced Win11 Storage
thumbnail: https://thmb.techidaily.com/d3a69700e0cb55adae67e72e210fb2f2a9d54f1a94f5e0b261b4ccf5f3207b46.jpg
---

## Secure & Efficient Storage: Controlling NTFS Compression in Win11

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS [file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
![Apply changes option in folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/apply-changes-option.jpg)
7. Click**OK.**

 That's it, the folder has now been compressed. You can confirm this by comparing the current folder size with its previous size.

 From now on, every file or folder that you will move inside the compressed folder will be compressed automatically. To disable compression, uncheck the**Compress contents to save disk space** box and save the changes.

Similarly, you can compress an entire drive. Here's how:

1. Open the File Explorer, and right-click on the drive you want to compress.
2. In the**General** tab, check the**Compress this drive to save disk space** box.  
![Driver properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties.jpg)
3. Click**Apply** and then click**OK** on the confirmation box that crops up.

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

## Free Up Space on Windows 11 With File Compression

 Enabling file compression is a great way to free up some space on Windows 11\. Using this feature can come in handy when you are running out of space but also don't want to compress your files using third-party compression tools.

 Meanwhile, you might be interested in learning more about the NTFS file system.


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
<li><a href="https://extra-hints.techidaily.com/exclusive-list-the-top-10-camcorders-for-2ranking/"><u>Exclusive List  The Top 10 Camcorders for 2Ranking</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/evaluating-the-long-term-benefits-of-purchasing-video-traction-for-2024/"><u>Evaluating the Long-Term Benefits of Purchasing Video Traction for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-hookup-opportunities-in-discord-chats/"><u>[Updated] Hookup Opportunities in Discord Chats</u></a></li>
<li><a href="https://win11.techidaily.com/managing-failed-app-verifications-in-windows-os/"><u>Managing Failed App Verifications in Windows OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/global-earning-maestro-of-video-content/"><u>Global Earning Maestro of Video Content</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-revealing-the-masters-behind-discords-most-beloved-glyphs/"><u>[Updated] 2024 Approved  Revealing the Masters Behind Discord's Most Beloved Glyphs</u></a></li>
<li><a href="https://article-helps.techidaily.com/visual-magic-implementing-filters-on-digital-media-for-2024/"><u>Visual Magic  Implementing Filters on Digital Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/wrapping-windows-games-in-christmas-carols/"><u>Wrapping Windows Games in Christmas Carols</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-enhancing-classroom-learning-through-recorders/"><u>2024 Approved  Enhancing Classroom Learning Through Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-guide-to-unlock-your-oppo-a1x-5g-by-drfone-android/"><u>Full Guide to Unlock Your Oppo A1x 5G</u></a></li>
<li><a href="https://win11.techidaily.com/windows-history-top-removed-and-evolved-characteristics/"><u>Windows History: Top Removed and Evolved Characteristics</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-radeon-driver-updates-in-windows-11-step-by-step-guide/"><u>Mastering Radeon Driver Updates in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-essential-8-strategies-for-digital-sound-recording/"><u>[Updated] 2024 Approved  Essential 8 Strategies for Digital Sound Recording</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-culinary-stars-on-tiktok/"><u>[Updated] In 2024, Culinary Stars on TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-sync-blueprint-for-android-plus-microsoft-os/"><u>The Perfect Sync Blueprint for Android + Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-concurrent-wi-fi-and-ethernet-on-windows-pcs/"><u>Mastering Concurrent Wi-Fi and Ethernet on Windows PCs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-inside-the-leaderboard-10-prime-tiktok-analytic-resources/"><u>[Updated] In 2024, Inside the Leaderboard  10 Prime TikTok Analytic Resources</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-system-performance-wins-top-diagnostic-list/"><u>Smooth System Performance: Win's Top Diagnostic List</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/share-the-moment-how-to-post-on-twitter/"><u>Share the Moment  How To Post on Twitter</u></a></li>
<li><a href="https://win11.techidaily.com/master-subtitles-management-with-prime-and-windows-11/"><u>Master Subtitles Management with Prime and Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-14-pro-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Xiaomi 14 Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-ultimate-list-the-finest-fps-titles-in-gaming/"><u>[New] In 2024, Ultimate List  The Finest FPS Titles in Gaming</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-decoding-facebooks-in-stream-ad-setup-process-from-basics-to-advanced-strategies/"><u>[Updated] Decoding Facebook's In-Stream Ad Setup Process  From Basics to Advanced Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-robloxs-restrictive-error-403-on-pc/"><u>Unraveling Roblox's Restrictive Error 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-network-drive-setup-a-comprehensive-walkthrough/"><u>Win11's Network Drive Setup: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-access-control-personalized-windows-pin-creation/"><u>Revolutionize Access Control: Personalized Windows Pin Creation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-beyond-one-viewpoint-the-ultimate-review-of-best-11-bridge-cams/"><u>In 2024, Beyond One Viewpoint  The Ultimate Review of Best 11 Bridge Cams</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-become-a-viral-sensation-maximizing-your-youtube-reach-for-2024/"><u>[Updated] Become a Viral Sensation  Maximizing Your YouTube Reach for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-memory-efficiency-for-device-interaction-windows/"><u>Streamlining Memory Efficiency for Device Interaction Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-movie-talent-release-declaration/"><u>[Updated] Free Movie Talent Release Declaration</u></a></li>
<li><a href="https://win11.techidaily.com/provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships.</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/transform-your-footage-best-free-android-editors-reviewed-for-2024/"><u>Transform Your Footage  Best Free Android Editors Reviewed for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-top-10-tiktok-viral-videos-on-twitter/"><u>[New] 2024 Approved  Top 10 TikTok Viral Videos on Twitter</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-streamline-meeting-recording-on-devices-with-gotomeeting/"><u>[New] In 2024, Streamline Meeting Recording on Devices with GoToMeeting</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-rectify-slow-windows-app-connections-for-peak-performance/"><u>Swiftly Rectify Slow Windows App Connections for Peak Performance</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-5-best-free-avi-video-rotators-for-2024/"><u>Updated Top 5 Best Free AVI Video Rotators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-past-the-steam-file-access-hurdle/"><u>Stepping Past the Steam “File Access” Hurdle</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premier-gopro-hero5-black-batteries-with-certified-chargers/"><u>2024 Approved  Premier GoPro Hero5 Black Batteries with Certified Chargers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-collabs-for-youtube-channel-expansion-for-2024/"><u>[New] Crafting Collabs for YouTube Channel Expansion for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unblocked-windows-reviving-context-menus-swiftly/"><u>Unblocked Windows: Reviving Context Menus Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-computing-10-top-alternatives-to-windows-defaults/"><u>Redefining Computing: 10 Top Alternatives to Windows' Defaults</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-screen-snafus-with-sonic-frontiers-securing-smooth-play-on-w11/"><u>Navigating Screen Snafus with Sonic Frontiers - Securing Smooth Play on W11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-itel-p55-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Itel P55 5G</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/1719193162154-unlocking-the-secrets-to-fixing-non-working-win-plus-printer/"><u>Unlocking The Secrets to Fixing Non-Working Win + Printer.</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-and-prevent-windows-drive-vanishing/"><u>Pinpoint and Prevent Windows Drive Vanishing</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-quick-solutions-for-cursor-on-black-screen/"><u>Win10/11: Quick Solutions for Cursor on Black Screen</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-adjustment-the-six-essential-techniques/"><u>Windows 11 Image Adjustment: The Six Essential Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/expert-analysis-10-webinar-software-titans-for-2024/"><u>Expert Analysis  10 Webinar Software Titans for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-connection-error-restoring-mb-link-on-windows-11/"><u>Overcoming Connection Error: Restoring MB Link on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-xiaomi-redmi-k70e-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Xiaomi Redmi K70E Fingerprint Lock</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-create-a-lasting-impression-best-free-animated-logo-makers-and-design-secrets/"><u>In 2024, Create a Lasting Impression Best Free Animated Logo Makers & Design Secrets</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-premium-biz-cloud-vault-services/"><u>2024 Approved  Premium Biz Cloud Vault Services</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-leading-cameras-for-automotive-tracking-unveiled/"><u>[Updated] Leading Cameras for Automotive Tracking Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-clarity-with-windows-11s-enhanced-photo-app/"><u>Maximizing Image Clarity with Windows 11'S Enhanced Photo App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-stalker-unveiled-preventive-measures-against-wacatacbml/"><u>The Silent Stalker Unveiled: Preventive Measures Against Wacatac.B!ml</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-direct-dissemination-from-tiktok-to-social-networks-for-2024/"><u>[New] Direct Dissemination From TikTok to Social Networks for 2024</u></a></li>
</ul></div>

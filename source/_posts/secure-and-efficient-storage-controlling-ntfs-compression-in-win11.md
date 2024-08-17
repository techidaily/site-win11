---
title: "Secure & Efficient Storage: Controlling NTFS Compression in Win11"
date: 2024-08-15T23:37:19.808Z
updated: 2024-08-16T23:37:19.808Z
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-web.techidaily.com/024-approved-secrets-to-massive-channel-subscription-growth/"><u>[New] 2024 Approved  Secrets to Massive Channel Subscription Growth</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-unlock-advanced-broadcast-techniques-with-obs-on-youtube-and-twitch/"><u>[New] 2024 Approved  Unlock Advanced Broadcast Techniques with OBS on YouTube & Twitch</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-discreet-downloaders-ranked-2023s-best-8-selections/"><u>[New] In 2024, Discreet Downloaders Ranked  2023'S Best 8 Selections</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-mapping-out-your-ideal-tiktok-conclusion/"><u>[New] Mapping Out Your Ideal TikTok Conclusion</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-switching-up-your-iphones-call-sound-effectively/"><u>[New] Switching up Your iPhone's Call Sound Effectively</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-celebrity-quick-shot-analysis/"><u>[Updated] 2024 Approved  Celebrity Quick Shot Analysis</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-turboupload-the-ultimate-guide-to-fast-youtube-video-rendering/"><u>[Updated] TurboUpload  The Ultimate Guide to Fast YouTube Video Rendering</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-masters-of-illusion-top-vr-producers/"><u>2024 Approved  Masters of Illusion  Top VR Producers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-quick-start-utilizing-zoom-in-windows-10-systems/"><u>2024 Approved  Quick Start  Utilizing Zoom in Windows 10 Systems</u></a></li>
<li><a href="https://extra-information.techidaily.com/affordable-action-camera-choices-top-6-under-100/"><u>Affordable ACTION Camera Choices – Top 6 Under $100</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/are-reviews-on-goods-and-services-for-cash-for-2024/"><u>Are Reviews on Goods & Services for Cash for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-restore-microsofts-pc-manager-on-win/"><u>Breakthrough: Restore Microsoft's PC Manager on Win</u></a></li>
<li><a href="https://win11.techidaily.com/bring-forward-elusive-cameras-in-device-management/"><u>Bring Forward Elusive Cameras in Device Management</u></a></li>
<li><a href="https://win11.techidaily.com/browsers-efficiency-ranking-ram-and-cpu-usage-across-oses/"><u>Browsers' Efficiency Ranking: RAM & CPU Usage Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/correct-misplaced-second-display-on-windows-11/"><u>Correct Misplaced Second Display on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-mixed-user-microsoft-login-issues/"><u>Dealing with Mixed-User Microsoft Login Issues</u></a></li>
<li><a href="https://win-solutions.techidaily.com/diablo-immortals-missing-launch-date-what-gamers-need-to-know-about-the-pc-version/"><u>Diablo Immortal's Missing Launch Date - What Gamers Need to Know About the PC Version</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-windows-11-a-guide-to-taskbar-search-functionality/"><u>Dive Into Windows 11: A Guide to Taskbar Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-dns-flushing-in-modern-windows-os/"><u>Efficient Techniques for DNS Flushing in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-entry-points-to-troubled-boots-in-win-writable-steps/"><u>Eliminate Entry Points to Troubled Boots in Win' Writable Steps</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-folder-context-menus-on-windows-11/"><u>Enhancing Folder Context Menus on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/entrusting-administration-to-command-line/"><u>Entrusting Administration to Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-handle-printmanagement-service-failure/"><u>Essential Tips to Handle 'PrintManagement' Service Failure</u></a></li>
<li><a href="https://extra-information.techidaily.com/explore-the-finest-8-high-quality-3d-and-shimmering-texts-online/"><u>Explore the Finest  8 High-Quality 3D & Shimmering Texts Online</u></a></li>
<li><a href="https://win11.techidaily.com/fix-steams-inaccessible-game-content-on-latest-windows-11/"><u>Fix Steam's Inaccessible Game Content on Latest Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/flawless-ppt-transitions-adding-voice-over-effectively-for-2024/"><u>Flawless PPT Transitions  Adding Voice Over Effectively for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-immediate-assist-feature-windows-11/"><u>How to Engage Immediate Assist Feature: Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-has-been-blocked-by-your-system-administrator-error-in-windows/"><u>How to Fix This App Has Been Blocked by Your System Administrator Error in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-make-360-videos-with-iphone/"><u>How to Make 360 Videos with iPhone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-honor-90-pro-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Honor 90 Pro</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-vivo-x100-pro-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Vivo X100 Pro to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-11/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-apple-iphone-6ipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled Apple iPhone 6/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-windows-update-stuck-at-100-here-are-6-fixes/"><u>Is Your Windows Update Stuck at 100%%? Here Are 6 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-clickers-the-best-auto-click-cars-and-keys/"><u>Masterful Clickers: The Best Auto Click Cars & Keys</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-edit-mp4-files-on-mac-mavericks-a-comprehensive-guide/"><u>New In 2024, Edit MP4 Files on Mac Mavericks A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-network-barriers-reviving-spotify-streams/"><u>Overcoming Network Barriers: Reviving Spotify Streams</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/rising-above-the-crowd-trending-techniques-for-youtubers-for-2024/"><u>Rising Above the Crowd  Trending Techniques for YouTubers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/secure-file-access-preventing-read-only-windows-folders/"><u>Secure File Access: Preventing Read-Only Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-activate-windows-media-player/"><u>Simplified Steps to Activate Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-stopping-bsod-from-vmware-on-windows-11/"><u>Strategies for Stopping BSOD From VMware on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-desktops-aesthetic-essential-theme-tips-for-win11/"><u>Transforming Your Desktop's Aesthetic: Essential Theme Tips for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x8007007e/"><u>Troubleshooting Windows Error 0X8007007E</u></a></li>
</ul></div>

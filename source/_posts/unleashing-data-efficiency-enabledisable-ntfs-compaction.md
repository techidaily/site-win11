---
title: "Unleashing Data Efficiency: Enable/Disable NTFS Compaction"
date: 2024-09-13T20:23:39.976Z
updated: 2024-09-16T18:12:53.382Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unleashing Data Efficiency: Enable/Disable NTFS Compaction"
excerpt: "This Article Describes Unleashing Data Efficiency: Enable/Disable NTFS Compaction"
keywords: Data Efficiency Unleashed,NTFS Disabling,NTFS Compaction Control,Optimize Disk Space,Enable NTFS Sparing,Disable NTFS Compression,Boost Storage Utility
thumbnail: https://thmb.techidaily.com/643f417ea21e236b7a77b1b03708fbc61c8fba5f4fb99ee9f899025e02ab5d17.jpg
---

## Unleashing Data Efficiency: Enable/Disable NTFS Compaction

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS[file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

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
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to[open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
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

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-navigate-the-melody-maze-crafting-a-personalized-youtube-playlist/"><u>[New] 2024 Approved Navigate the Melody Maze Crafting a Personalized YouTube Playlist</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-galaxy-s8-review-a-leap-forward-with-4k-display/"><u>2024 Approved Galaxy S8 Review - A Leap Forward with 4K Display</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1715859822942-2024-approved-virtual-playstation-revival-on-android-try-the-5-best-emulators-here/"><u>2024 Approved Virtual PlayStation Revival on Android? Try the 5 Best Emulators Here!</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/climates-with-a-warm-twist-selecting-video-bgs/"><u>Cool Climates with a Warm Twist Selecting Video Bg's</u></a></li>
<li><a href="https://win11.techidaily.com/direct-to-victory-windows-methods-of-gaming-directories/"><u>Direct to Victory: Windows Methods of Gaming Directories</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fix-why-your-steam-client-froze-and-how-to-get-it-running-smoothly-again/"><u>Fix: Why Your Steam Client Froze & How To Get It Running Smoothly Again</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/lossless-vlc-trimming-on-mac-the-ultimate-solution-for-video-editing/"><u>Lossless VLC Trimming on Mac The Ultimate Solution for Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-in-setting-up-mstore-apps/"><u>Overcoming Obstacles in Setting Up MSTORE Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pro-photography-insiders-top-picks-for-6-premium-4k-dslrs-for-2024/"><u>Pro Photography Insiders Top Picks for 6 Premium 4K DSLRs for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/revolutionizing-connectivity-what-to-expect-from-fbs-boombox-with-spotify/"><u>Revolutionizing Connectivity: What to Expect From FB's Boombox With Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-11-icon-size-decline/"><u>Solving Windows 11 Icon Size Decline</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-workflow-with-personalized-fn-key-settings/"><u>Streamlining Workflow with Personalized FN Key Settings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-vivo-s17e-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Vivo S17e Device</u></a></li>
</ul></div>


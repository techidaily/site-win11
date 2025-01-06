---
title: Maximizing Disk Space with Windows 11'S NTFS Options
date: 2024-12-30T17:51:57.355Z
updated: 2025-01-06T17:58:33.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Maximizing Disk Space with Windows 11'S NTFS Options
excerpt: This Article Describes Maximizing Disk Space with Windows 11'S NTFS Options
keywords: WinSpaceNTFS,SaveDiskSpaceWin11,OptimizeDiskNTFS,EnhanceFileStorageWin11,NTFSSpaceManagementWin11,SpaceEfficientWindows11,NtfsOptionsMaximize
thumbnail: https://thmb.techidaily.com/778dacc021ae6d569afd3e62fa61bf15ba6fe429d937373bba78e772659986e3.jpg
---

## Maximizing Disk Space with Windows 11'S NTFS Options

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/avigating-best-options-expert-picks-from-top-9-free-logomakers-for-2024/"><u>[New] Navigating Best Options Expert Picks From Top 9 Free Logomakers for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-revolutionizing-cinematography-with-advanced-3d-luts-for-2024/"><u>[New] Revolutionizing Cinematography with Advanced 3D LUTs for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-in-game-capture-kings/"><u>[Updated] 2024 Approved In-Game Capture Kings</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-step-by-step-guide-to-perfecting-videos-on-a-pc-for-youtubers/"><u>[Updated] 2024 Approved Step-by-Step Guide to Perfecting Videos on a PC for YouTubers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-craft-a-compelling-narrative-with-your-igtv-video-titles-and-texts/"><u>[Updated] In 2024, Craft a Compelling Narrative with Your IGTV Video Titles & Texts</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-mystery-of-team-up-glitch-80080300-on-w11-systems/"><u>Decoding the Mystery of Team Up Glitch #80080300 on W11 Systems</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-realme-12-proplus-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Realme 12 Pro+ 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-restore-windows-alt-key-functionality/"><u>How to Restore Windows ALT Key Functionality</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-your-ultimate-guide-to-top-streamers-platforms/"><u>In 2024, Your Ultimate Guide to Top Streamers Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-in-overcoming-non-initialized-drives-on-windows-pc/"><u>Masterclass in Overcoming Non-Initialized Drives on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-custom-screensavers-in-win11/"><u>Mastering Custom Screensavers in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-fix-media-creators-issue-x8007043c-x90017/"><u>Methods to Fix Media Creator's Issue: X.8007043C, X.90017</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-using-vn-editor-to-add-luts-for-video-editing-for-2024/"><u>New Using VN Editor To Add Luts for Video Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/sniplink-trouble-quick-fixes-for-a-smooth-experience/"><u>SnipLink Trouble? Quick Fixes for a Smooth Experience</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-best-free-mpeg-video-splitters-a-comprehensive-guide-for-2024/"><u>The Best Free MPEG Video Splitters A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-secret-of-masking-windows-11s-search-icon/"><u>The Secret of Masking Windows 11'S Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-no-network-detection-by-windows/"><u>Troubleshoot No Network Detection by Windows</u></a></li>
</ul></div>


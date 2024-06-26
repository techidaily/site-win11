---
title: "Mastering NTFS: Enabling/Disabling File Compression"
date: 2024-06-25T10:12:24.224Z
updated: 2024-06-26T10:12:24.224Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering NTFS: Enabling/Disabling File Compression"
excerpt: "This Article Describes Mastering NTFS: Enabling/Disabling File Compression"
keywords: NTFS File Management,NTFS Compression Control,Enable/Disable NTFS Comp,Optimize NTFS Performance,NTFS Storage Efficiency,Advanced NTFS Configuring,Mastering NTFS Settings
thumbnail: https://thmb.techidaily.com/8b7337516e3ab4c7de40944c48ebe243474ab75d4e4c1c2d693991f9d3085553.jpg
---

## Mastering NTFS: Enabling/Disabling File Compression

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
<li><a href="https://win11.techidaily.com/self-contained-strategies-for-hardware-duplication/"><u>Self-Contained Strategies for Hardware Duplication</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-wows-unexpected-crash-in-windows-1111/"><u>How to Tackle WoW’s Unexpected Crash in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-network-visibility-in-windows/"><u>Solving Disabled Network Visibility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-0x80070194-a-guide-to-onedrive-in-ws/"><u>Counteracting 0X80070194: A Guide to OneDrive in WS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-power-indicators-full-charge-alerts-for-windows-11/"><u>Mastering Power Indicators: Full Charge Alerts for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-unblocking-steam-when-playing-games/"><u>Essential Tips for Unblocking Steam When Playing Games</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-code-navigating-through-lost-windows-1110-patches/"><u>Unlock the Code: Navigating Through Lost Windows 11/10 Patches</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-translate-videos-like-a-pro-with-subtitle-cat-your-essential-guide/"><u>New In 2024, Translate Videos Like a Pro with Subtitle Cat Your Essential Guide</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-realme-c53-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Realme C53 on Mac</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/elevating-your-igtv-visuals-cover-photos-update-for-2024/"><u>Elevating Your IGTV Visuals  Cover Photos Update for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-motionmaster-win8-edition/"><u>[Updated] MotionMaster Win8 Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-a-teachers-guide-to-enhancing-learning-through-youtube-videos-for-2024/"><u>[Updated] A Teacher's Guide to Enhancing Learning Through YouTube Videos for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-motorola-moto-g34-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Motorola Moto G34 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-become-a-tiktok-filming-pro-a-step-by-step-approach/"><u>[New] In 2024, Become a TikTok Filming Pro  A Step-by-Step Approach</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-improving-hues-a-beginners-approach-to-ps-grading/"><u>[Updated] Improving Hues  A Beginner's Approach to PS Grading</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-poco-c65-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Poco C65 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-art-of-color-harmony-explore-this-select-list-of-7-techniques/"><u>The Art of Color Harmony  Explore This Select List of 7 Techniques</u></a></li>
</ul></div>

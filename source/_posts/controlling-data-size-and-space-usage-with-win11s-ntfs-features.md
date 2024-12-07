---
title: Controlling Data Size & Space Usage with Win11's NTFS Features
date: 2024-11-30T23:06:26.872Z
updated: 2024-12-06T23:54:18.930Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Data Size & Space Usage with Win11's NTFS Features
excerpt: This Article Describes Controlling Data Size & Space Usage with Win11's NTFS Features
keywords: Win11 NTFS Control,Reduce Data Size Win11,Manage Space Win11,Optimize File Storage Win11,Limit Disk Usage Windows,Efficient Data Management Win11,Minimize File Size, Win11
thumbnail: https://thmb.techidaily.com/dba89d459ade8c7de3368900b426d88c278b90eb374e6b587ae53e82dd50d862.jpg
---

## Controlling Data Size & Space Usage with Win11's NTFS Features

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/new-free-templates-for-bespoke-video-epilogues/"><u>[New] Free Templates for Bespoke Video Epilogues</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tricks-to-improve-instagram-video-load-speeds-mobile/"><u>[New] Tricks to Improve Instagram Video Load Speeds (Mobile)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-social-sharing-simplified-uploading-immersive-mobile-photography/"><u>[Updated] 2024 Approved Social Sharing Simplified Uploading Immersive Mobile Photography</u></a></li>
<li><a href="https://win11.techidaily.com/explore-win10s-top-7-pencil-to-pixels-apps/"><u>Explore: Win10's Top 7 Pencil-to-Pixels Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-hide-or-show-the-firewall-and-network-protection-area-in-windows-security/"><u>How to Hide or Show the Firewall and Network Protection Area in Windows Security</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo A56s 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tactics-restoring-functionality-to-outlook-on-pc/"><u>Quick-Fix Tactics: Restoring Functionality to Outlook on PC</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-missing-rockalldlldll-errors-on-pcs/"><u>Resolving Missing Rockalldll.dll Errors on PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
</ul></div>


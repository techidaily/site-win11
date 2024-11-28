---
title: Dive Into Disk Space Management with Win11's NTFS Features
date: 2024-11-26T02:18:32.386Z
updated: 2024-11-27T19:15:07.854Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dive Into Disk Space Management with Win11's NTFS Features
excerpt: This Article Describes Dive Into Disk Space Management with Win11's NTFS Features
keywords: Win11 NTFS DiskSpace,ManageNTFS Windows,StorageSpace Optimization,FileSystem Control,NTFSSpace Management,DataManagement Win11,OptimizeDisk Windows
thumbnail: https://thmb.techidaily.com/f2cea06ab8ae79e3da9341215d5a2b3791081a5d0d2f702dc7f4ecb1fa023ae2.jpg
---

## Dive Into Disk Space Management with Win11's NTFS Features

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to[open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/ed-danger-lurking-online-spotting-the-falsehood-of-fake-viewers-on-youtube/"><u>[Updated] Danger Lurking Online Spotting the Falsehood of Fake Viewers on YouTube</u></a></li>
<li><a href="https://tech-hub.techidaily.com/10-custom-gpts-that-actually-make-chatgpt-better/"><u>10 Custom GPTs That Actually Make ChatGPT Better</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-superior-guide-to-16-freeware-players-for-pc-and-mac/"><u>2024 Approved Superior Guide to 16 Freeware Players for PC & Mac</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-samsung-galaxy-a24-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/comprehensive-guide-amazons-prime-day-2024-unveiled/"><u>Comprehensive Guide: Amazon's Prime Day 2024 Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/does-your-system-qualify-for-next-gen-windows-11/"><u>Does Your System Qualify for Next-Gen Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-interface-with-three-column-widgets-in-win11/"><u>Elevate Your Interface with Three-Column Widgets in Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-vivo-v27-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Vivo V27 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-outlook-preview-app-on-windows-11-and-11/"><u>How to Get the Outlook Preview App on Windows 11 and 11</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-xs-max-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone XS Max to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-se-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock on Apple iPhone SE</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-quick-and-easy-fb-video-access-choose-from-these-5-chromium-tools/"><u>In 2024, Quick and Easy FB Video Access Choose From These 5 Chromium Tools</u></a></li>
<li><a href="https://win11.techidaily.com/learn-the-trick-for-swift-folder-reorganization-on-windows-11/"><u>Learn the Trick for Swift Folder Reorganization on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-savings-on-windows-11-keys/"><u>Maximizing Savings on Windows 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-fatal-0xf0831-problem-with-ease/"><u>Overcoming Windows' Fatal 0XF0831 Problem with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-the-joy-of-win-11-gaming-master-these-seven-game-changing-tweaks/"><u>Reignite the Joy of Win 11 Gaming: Master These Seven Game-Changing Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-alternate-antivirus-without-defenders-restrictions/"><u>Tips for Integrating Alternate Antivirus without Defender’s Restrictions</u></a></li>
</ul></div>


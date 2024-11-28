---
title: "Windows 11 Guide: Turning On/Off NTFS Compression"
date: 2024-11-24T01:24:38.585Z
updated: 2024-11-28T02:46:12.194Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Guide: Turning On/Off NTFS Compression"
excerpt: "This Article Describes Windows 11 Guide: Turning On/Off NTFS Compression"
keywords: Windows 11 NTFS Tips,NTFS Compression Windows 11,Enable NTFS Compression,Disable NTFS Compression,NTFS Settings Guide,Optimize File System,NTFS Performance Tips
thumbnail: https://thmb.techidaily.com/93e8b8eb6bc88169936766a6461fe23e663eb59793bd9736b13ed221555fa6ea.jpg
---

## Windows 11 Guide: Turning On/Off NTFS Compression

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-lab.techidaily.com/levate-video-quality-mastering-aspect-ratio-and-size-settings-on-youtube-for-2024/"><u>[New] Elevate Video Quality Mastering Aspect Ratio and Size Settings on YouTube for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-building-brands-through-innovative-design-work/"><u>[Updated] 2024 Approved Building Brands Through Innovative Design Work</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-youtubes-journey-seamlessly-converted-into-high-quality-avis/"><u>[Updated] In 2024, YouTube's Journey Seamlessly Converted Into High-Quality AVIs</u></a></li>
<li><a href="https://win11.techidaily.com/1-ultimate-guide-downloading-youtube-content-onto-your-ipad/"><u>1. Ultimate Guide: Downloading YouTube Content Onto Your iPad</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-step-by-step-on-hosting-webinars-a-beginners-guide-to-zoom/"><u>2024 Approved Step-by-Step on Hosting Webinars A Beginner's Guide to Zoom</u></a></li>
<li><a href="https://win11.techidaily.com/1726027881327-youtube/"><u>効果的な方法でYoutube映像ダウンロード術</u></a></li>
<li><a href="https://win11.techidaily.com/1726029196115-youtube/"><u>最高の解決策! YouTube動画をセキュリティ保証付きでダウンロードするためのベストソフト選び方</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/celebrity-fleeting-frame-study-for-2024/"><u>Celebrity Fleeting Frame Study for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/iphone-external-storage-troubles-fix-your-usb-mtp-drivers-now/"><u>IPhone External Storage Troubles? Fix Your USB MTP Drivers Now!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1726027705515-pc-and-smartphone/"><u>PC & Smartphoneで組み合わせ編集:ビデオ・オーディオの最適化</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210133167-9781644111666-the-ancient-language-of-sacred-sound-2nd-ed/"><u>The Ancient Language of Sacred Sound (2nd ed.) | Free Book</u></a></li>
<li><a href="https://extra-information.techidaily.com/transition-smoothly-with-chromes-picture-in-picture/"><u>Transition Smoothly with Chrome’s Picture In Picture</u></a></li>
<li><a href="https://win11.techidaily.com/1726027640655-wav/"><u>WAV形式のメタデータ管理 - 最適な編集ソフトと使用手順</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfoxs-limited-time-deal-earn-high-value-ripper-pro-licenses-discounted-3995-7990-during-this-months-movie-campaign-join-now/"><u>WonderFox's Limited-Time Deal: Earn High-Value Ripper Pro Licenses (Discounted @$3995-$7990) During This Month’s Movie Campaign – Join Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1726026812283-tiktok/"><u>パーフェクトなTikTok動画の縦横サイズ及び製作技術</u></a></li>
</ul></div>


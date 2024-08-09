---
title: Advanced Tips for NTFS Compression in Win11 Systems
date: 2024-08-08T13:14:32.839Z
updated: 2024-08-09T13:14:32.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Tips for NTFS Compression in Win11 Systems
excerpt: This Article Describes Advanced Tips for NTFS Compression in Win11 Systems
keywords: Win11 NTFS Compress,NTFS Win11 Optimize,Win11 Filespace Save,Efficient NTFS Compression,Data Reduce Win11 NTFS,Compression Tips Windows 11,Enhance NTFS Space Usage
thumbnail: https://thmb.techidaily.com/583e140408c2ec351f3efcf4716a6b87c865b3b8a448b26c52bfccdf2d778b7a.png
---

## Advanced Tips for NTFS Compression in Win11 Systems

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS [file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
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
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-effortless-audio-extraction-best-youtube-to-mp3-tools-list-for-2024/"><u>[New] Effortless Audio Extraction  Best YouTube to MP3 Tools List for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-prime-cloud-storage-options/"><u>[New] Unveiling Prime Cloud Storage Options</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-decoding-youtube-premium-complete-information-inside-for-2024/"><u>[Updated] Decoding YouTube Premium  Complete Information Inside for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exhaustive-breakdown-of-vsco-photography-tool/"><u>[Updated] Exhaustive Breakdown of VSCO Photography Tool</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-audiotrack-collection-pc-noises/"><u>[Updated] In 2024, Audiotrack Collection  PC Noises</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-conquer-your-screen-space-integrating-video-within-video/"><u>2024 Approved  Conquer Your Screen Space  Integrating Video Within Video</u></a></li>
<li><a href="https://win11.techidaily.com/automating-zipunzip-tasks-in-windows-using-scripting-tools/"><u>Automating Zip/Unzip Tasks in Windows Using Scripting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/break-down-drives-hdd-vs-ssd-explained/"><u>Break Down Drives: HDD vs SSD Explained</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-memory-caching-in-windows-os/"><u>Breaking Down Memory Caching in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/color-confusion-correcting-windows-desktop-hues-quickly/"><u>Color Confusion? Correcting Windows Desktop Hues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/creative-steps-to-obliviate-win-11s-taskbar-button/"><u>Creative Steps to Obliviate Win 11'S Taskbar Button</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-6-oddities-in-windows-11-design/"><u>Decoding the 6 Oddities in Windows 11 Design</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-setup-with-canon-mg3620-driver-downloads-for-ultimate-printing-performance/"><u>Effortless Setup with Canon MG3620 Driver Downloads for Ultimate Printing Performance</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-unblocking-steam-when-playing-games/"><u>Essential Tips for Unblocking Steam When Playing Games</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unchecked-cpu-usage-by-wmi-worker/"><u>Fixing Unchecked Cpu Usage by WMI Worker</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-beginnings-executing-a-clean-windows-11-reinstall/"><u>Fresh Beginnings: Executing a Clean Windows 11 Reinstall</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-resolve-microphone-problems-on-pc-and-xbox/"><u>Guidelines to Resolve Microphone Problems on PC & Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-blank-login-screen-in-windows-11-and-11/"><u>How to Fix a Blank Login Screen in Windows 11 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-apple-iphone-6s-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your Apple iPhone 6s and iPad</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-of-apple-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS of Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-for-reviving-freeze-ups-on-resource-monitor-win11/"><u>Immediate Actions for Reviving Freeze-Ups on Resource Monitor, Win11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-6-plus-unavailable-issue-with-ease-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 6 Plus Unavailable Issue With Ease</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-strategies-for-selecting-and-syncing-music-with-visuals/"><u>In 2024, Strategies for Selecting and Syncing Music with Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/is-it-necessary-to-keep-pagefilesys-reasons-explored/"><u>Is It Necessary to Keep Pagefile.sys? Reasons Explored</u></a></li>
<li><a href="https://win11.techidaily.com/masked-commands-the-win-1011-trickery-guide/"><u>Masked Commands: The Win 10/11 Trickery Guide</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-comic-experience-with-windows-11-techniques/"><u>Maximizing Comic Experience with Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-bypassing-non-active-window-firewall/"><u>Methods for Bypassing Non-Active Window Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/new-wave-windows-leap-from-the-legacy-of-11/"><u>New Wave Windows: Leap From the Legacy of 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-a-guide-to-mastering-window-11s-taskbar-search-function/"><u>Quick Start: A Guide to Mastering Window 11’S Taskbar Search Function</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-windows-default-settings-on-reboot/"><u>Quick Tips for Windows Default Settings on Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/realign-google-chrome-clock-with-windows-time/"><u>Realign Google Chrome Clock with Windows Time</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-traditional-windows-explorer-look/"><u>Reclaiming Traditional Windows Explorer Look</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-pc-with-the-top-10-must-try-powertoy-applications/"><u>Reimagine Your PC with the Top 10 Must-Try PowerToy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-absence-of-printmanagement-on-your-system/"><u>Remedying the Absence of 'Printmanagement' On Your System</u></a></li>
<li><a href="https://win11.techidaily.com/removing-no-associated-error-on-windows-devices/"><u>Removing 'No Associated' Error on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/seven-keys-to-unlocking-the-full-potential-of-windows-software/"><u>Seven Keys to Unlocking the Full Potential of Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-to-rectify-windows-defenders-error-0x80004004/"><u>Step-by-Step to Rectify Windows Defender’s Error 0X80004004</u></a></li>
<li><a href="https://win-blog.techidaily.com/stop-suffering-top-fixes-for-state-of-decay-2-crashes/"><u>Stop Suffering: Top Fixes for State of Decay 2 Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-update-freeze-implementing-effective-fixes/"><u>Stop Windows Update Freeze: Implementing Effective Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-hypervisor-errors-for-winxose-users/"><u>Swift Resolution to Hypervisor Errors for WINXOSE Users</u></a></li>
<li><a href="https://win11.techidaily.com/turn-your-windows-pc-into-a-distributed-transcoding-powerhouse-with-tdarr/"><u>Turn Your Windows PC Into a Distributed Transcoding Powerhouse With Tdarr</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-wpm-in-windows-11-environments/"><u>Unveiling the Power of WPM in Windows 11 Environments</u></a></li>
</ul></div>

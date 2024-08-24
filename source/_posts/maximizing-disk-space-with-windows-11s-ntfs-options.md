---
title: Maximizing Disk Space with Windows 11'S NTFS Options
date: 2024-08-23T06:09:30.714Z
updated: 2024-08-24T06:09:30.714Z
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-best-templates-no-cost-explore-premiere-pro-samples-free/"><u>[New] Best Templates, No Cost! Explore Premiere Pro Samples (FREE)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-nikon-j5-sets-new-standards-in-4k-video-capture/"><u>[New] Nikon J5 Sets New Standards in 4K Video Capture</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-vibrant-voices-audible-updates-to-whatsapp-for-2024/"><u>[New] Vibrant Voices  Audible Updates to WhatsApp for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-speedy-view-of-vimeo-videos/"><u>[Updated] 2024 Approved  Speedy View of Vimeo Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-aspect-ratio-guidelines-for-twitter-videos-for-2024/"><u>[Updated] Aspect Ratio Guidelines for Twitter Videos for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-capture-without-capsule-the-no-limit-story-saving-app-for-2024/"><u>[Updated] Capture Without Capsule  The No-Limit Story Saving App for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-video-edits-made-simple-with-windows-10s-story-remix/"><u>[Updated] Innovative Video Edits Made Simple with Windows 10'S Story Remix</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-vr-future-latest-trends/"><u>[Updated] Unveiling the VR Future  Latest Trends</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-skys-the-limit-with-dji-spark-an-in-depth-miniature-drone-study/"><u>2024 Approved  Sky's the Limit with DJI Spark  An In-Depth Miniature Drone Study</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/compress-mpeg2-videos-with-free-virtualdub-software-for-2024/"><u>Compress MPEG2 Videos with Free VirtualDub Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-file-system-interactions-with-new-commands/"><u>Customizing File System Interactions with New Commands</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-emotion-ai-is-it-possible-for-algorithms-to-accurately-understand-human-emotions/"><u>Decoding Emotion AI: Is It Possible for Algorithms to Accurately Understand Human Emotions?</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-11-firewall-with-ease/"><u>Disabling Windows 11 Firewall with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hidden-windows-programs/"><u>Enabling Hidden Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-three-column-widgets-on-windows-11-os/"><u>Enabling Three-Column Widgets on Windows 11 OS</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-itel-a60s-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Itel A60s | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-motorola-moto-g-stylus-5g-2023-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Motorola Moto G Stylus 5G (2023)</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-lava-blaze-2-pro-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Lava Blaze 2 Pro without Losing Data | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-samsung-galaxy-a25-5g-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Samsung Galaxy A25 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-nubia-z50-ultra-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Nubia Z50 Ultra to iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-become-a-pro-with-2023s-free-templates/"><u>In 2024, Become a Pro with 2023'S FREE Templates</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-google-pixel-7a-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Google Pixel 7a to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-a23-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy A23 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-the-essential-guide-to-obs-and-zoom-live-stream-setup/"><u>In 2024, The Essential Guide to OBS and Zoom Live Stream Setup</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-iphone-15-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>In 2024, Unlock iPhone 15 With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-screen-controls-for-better-accessibility/"><u>Mastering Windows' Screen Controls for Better Accessibility</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-elite-selection-best-selling-mac-audio-editing-tools-ranked/"><u>New In 2024, The Elite Selection Best-Selling Mac Audio Editing Tools, Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-external-display-not-recognized-problem-in-windows/"><u>Overcoming External Display Not Recognized Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-invalid-temporary-folder-issues-on-w11/"><u>Preventing Invalid Temporary Folder Issues on W11</u></a></li>
<li><a href="https://win11.techidaily.com/proven-methods-to-stop-display-glitches-on-windows-1011/"><u>Proven Methods to Stop Display Glitches on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-vanished-windows-steam-games/"><u>Reactivating Vanished Windows Steam Games</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-1011-store-error-code-0x800704cf/"><u>Rectifying Windows 10/11 Store Error: Code 0X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-functionality-fixing-malfunctioning-ccleaner-on-win1011/"><u>Regaining Functionality: Fixing Malfunctioning CCleaner on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-installer-rights-troubles-on-modern-oses/"><u>Remedying Installer Rights Troubles on Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-missing-presets-for-win-11-system-use/"><u>Reviving Missing Presets for Win 11 System Use</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-recovering-a-disabled-delete-functionality/"><u>Solutions for Recovering a Disabled Delete Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-stopping-load-failure-in-microsoft-marketplace/"><u>Solutions for Stopping 'Load Failure' In Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-restoring-audio-on-windows-pcs/"><u>Steps for Restoring Audio on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/stop-active-use-of-cortana-in-windows-11/"><u>Stop Active Use of Cortana in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-stop-unpredictable-printer-changes/"><u>Tactics to Stop Unpredictable Printer Changes</u></a></li>
<li><a href="https://win11.techidaily.com/taming-zero-x-eight-oh-three-one-f-error-in-microsoft-written-word/"><u>Taming Zero X Eight Oh Three One F Error in Microsoft' Written Word</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-taming-troublesome-updates/"><u>The Ultimate Guide to Taming Troublesome Updates</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-voice-of-action-crafting-moving-screenplay-conversations/"><u>The Voice of Action  Crafting Moving Screenplay Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-display-brightness-control/"><u>Troubleshooting Unresponsive Display Brightness Control</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-regain-access-to-microsoft-onedrive-via-pc/"><u>Troubleshooting: Regain Access to Microsoft OneDrive via PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-windows-side-by-side-conflict/"><u>Troubleshooting: Resolving 'Windows Side-by-Side Conflict'</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-next-gen-phone-integration/"><u>Unveiling Windows 11'S Next-Gen Phone Integration</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-update-impact-on-linux-subsystem/"><u>Windows 11 Update: Impact on Linux Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/windows-graphics-scheduler-control-explained/"><u>Windows Graphics Scheduler Control Explained</u></a></li>
</ul></div>

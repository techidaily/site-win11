---
title: "Mastering NTFS: Enabling/Disabling File Compression"
date: 2024-08-16T00:15:12.036Z
updated: 2024-08-17T00:15:12.036Z
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to [open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
9. Click**OK** to save the changes.

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://extra-lessons.techidaily.com/new-2023s-best-updated-lg-bp550-overview/"><u>[New] 2023'S Best  Updated LG BP550 Overview</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-pc-setup-for-smooth-tiktok-livestreams-made-easy/"><u>[New] 2024 Approved  PC Setup for Smooth TikTok Livestreams Made Easy</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ostering-relationships-not-just-viewers-a-guide-to-subscriptions-for-2024/"><u>[New] Fostering Relationships, Not Just Viewers  A Guide to Subscriptions for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-enchanting-viewers-the-art-of-crafting-engaging-youtube-description-templates/"><u>[New] In 2024, Enchanting Viewers  The Art of Crafting Engaging YouTube Description Templates</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/eamless-transitions-smooth-editing-techniques-for-youtube-content/"><u>[New] Seamless Transitions  Smooth Editing Techniques for YouTube Content</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-sending-streamed-content-to-discord-with-finesse-and-precision/"><u>[Updated] 2024 Approved  Sending Streamed Content to Discord with Finesse and Precision</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-effective-methods-to-document-facetime-calls-for-2024/"><u>[Updated] Effective Methods to Document FaceTime Calls for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-flip-the-like-ratio-with-squared-up-social-media-content/"><u>[Updated] In 2024, Flip the Like Ratio with Squared-Up Social Media Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-blueprint-of-movies-a-scripts-role/"><u>[Updated] In 2024, The Blueprint of Movies  A Script's Role</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-understanding-the-impact-of-igtv-videos-through-analysis/"><u>[Updated] In 2024, Understanding the Impact of IGTV Videos Through Analysis</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-monetization-strategies-for-gamers-for-2024/"><u>[Updated] Monetization Strategies for Gamers for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-navigating-the-ways-to-share-youtube-listings-for-2024/"><u>[Updated] Navigating the Ways to Share YouTube Listings for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-standing-out-with-personalized-tiktok-pfps/"><u>[Updated] Standing Out with Personalized TikTok PFPs</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-cost-efficient-sky-companions-drone-guide-(500/"><u>2024 Approved  Cost-Efficient Sky Companions  Drone Guide <$500</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-open-a-games-directory-on-windows/"><u>3 Ways to Open a Game's Directory on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-realme-11-pro-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Realme 11 Pro Phone When You Forget the Password</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-how-win11-collects-your-personal-data/"><u>A Closer Look: How Win11 Collects Your Personal Data</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-the-ultimate-student-friendly-laptop/"><u>ASUS Vivobook S 15: The Ultimate Student-Friendly Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-firewall-defenses-in-5-easy-steps/"><u>Customizing Firewall Defenses in 5 Easy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-update-failure-code-0x80246007-windows-guide/"><u>Disabling Update Failure Code 0X80246007: Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-navigation-of-files-with-gallery-on-pc/"><u>Efficient Navigation of Files with Gallery on PC</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-ms-store-problem-fix-code-0x0-error-on-pcs/"><u>Eradicating MS Store Problem - Fix Code 0X0 Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-boosting-productivity-in-project-management-tools/"><u>Expert Tips for Boosting Productivity in Project Management Tools</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expertly-edit-your-imagery-with-top-androidios-montage-apps/"><u>Expertly Edit Your Imagery with Top Android/iOS Montage Apps</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-screen-unresponsive-message-in-windows-1111/"><u>Fixing Screen Unresponsive Message in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-disabling-laptops-hardware-keys-on-windows-pc/"><u>Guide: Disabling Laptop's Hardware Keys on Windows PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-realme-gt-5-pro-by-drfone-android/"><u>How to Bypass FRP on Realme GT 5 Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-error-0x800704b3/"><u>How to Bypass Windows Error 0X800704B3</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-find-and-install-latest-rndis-network-adapter-drivers-on-your-pc/"><u>How to Find and Install Latest RNDIS Network Adapter Drivers on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-your-laptop-or-desktop-a-portable-network-hub-on-windows-11/"><u>How to Make Your Laptop or Desktop a Portable Network Hub on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-sony-xperia-10-v-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Sony Xperia 10 V to iPad | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-savvy-screens-10-best-tools-for-live-recording/"><u>In 2024, Savvy Screens  #10 Best Tools for Live Recording</u></a></li>
<li><a href="https://youtube-web.techidaily.com/e-ring-of-creatives-evaluating-own-and-adversary-arts/"><u>In the Ring of Creatives  Evaluating Own and Adversary Arts</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-overlooked-window-11-styles/"><u>In-Depth Look at Overlooked Window 11 Styles</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-update-notifier-into-the-windows-ui-context-of-win11/"><u>Integrating Update Notifier Into the Windows UI Context of Win11</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-reno-11f-5g-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo Reno 11F 5G Phone FRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-world-google-map-powerhouse/"><u>Microsoft World, Google Map Powerhouse</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-best-10-vector-stock-pools/"><u>Navigating the Best 10 Vector Stock Pools</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-apple-maps-on-windows/"><u>Navigating the World: Apple Maps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-in-use-device-names-on-your-windows-system/"><u>Overcoming In-Use Device Names on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-non-operational-ccleaner-on-win11/"><u>Overhauling Non-Operational CCleaner on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-picturesaveerror-in-windows-11/"><u>Resolving PictureSaveError in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-failed-volume-shadow-copy-in-windows-os/"><u>Solving Failed Volume Shadow Copy in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-procedure-to-independently-update-windows/"><u>Stepwise Procedure to Independently Update Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-comic-file-access-in-modern-windows/"><u>Streamlining Comic File Access in Modern Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/top-20-strategies-for-boosting-fb-ads-via-video-content/"><u>Top 20 Strategies for Boosting FB Ads via Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-tactics-to-master-wsl-2-in-windows-environments/"><u>Top 5 Tactics to Master WSL 2 in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-advanced-backup-capabilities/"><u>Unlock Advanced Backup Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-phone-link-microsofts-bluetooth-connectivity-app/"><u>Unveiling 'Phone Link': Microsoft’s Bluetooth Connectivity App</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-vivo-y100i-power-5g-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Vivo Y100i Power 5G Phone Network-Ready</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
</ul></div>

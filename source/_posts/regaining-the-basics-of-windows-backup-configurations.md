---
title: Regaining the Basics of Windows Backup Configurations
date: 2024-08-08T13:19:10.544Z
updated: 2024-08-09T13:19:10.544Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining the Basics of Windows Backup Configurations
excerpt: This Article Describes Regaining the Basics of Windows Backup Configurations
keywords: Windows Backup Guide,Basic Backup Steps,Restore System Files,Backup Settings Overview,Save Data Safely,Windows Recovery Options,Configuring File Protection
thumbnail: https://thmb.techidaily.com/9416939e5407a18ea81200cd7e119e61ff04e31fb3c5cd004cd4601ad28e3eb8.jpg
---

## Regaining the Basics of Windows Backup Configurations

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-expert-tips-on-adding-yt-playlists-to-your-website-content/"><u>[New] 2024 Approved  Expert Tips on Adding YT Playlists to Your Website Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-from-flashy-feeds-to-fm-sounds-the-instagram-to-mp3-methodology/"><u>[New] 2024 Approved  From Flashy Feeds to FM Sounds  The Instagram-to-Mp3 Methodology</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-stillness-to-stirring-tips-for-bouncing-text/"><u>[New] 2024 Approved  From Stillness to Stirring  Tips for Bouncing Text</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-essential-tv-gear-for-premium-live-broadcasts/"><u>[New] Essential TV Gear for Premium Live Broadcasts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-10-free-web-conferencing-software-for-online-meeting-with-screen-sharing-for-2024/"><u>[Updated] 10 Free Web Conferencing Software for Online Meeting (with Screen Sharing) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-mastery-guide-for-instagrams-favorite-interrogation-icon/"><u>[Updated] 2024 Approved  Mastery Guide for Instagram's Favorite Interrogation Icon</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-delving-into-magix-photo-editors-features-for-2024/"><u>[Updated] Delving Into MAGIX Photo Editor's Features for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-explore-10-premier-historical-youtube-networks/"><u>[Updated] In 2024, Explore 10 Premier Historical Youtube Networks</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-finest-6-video-snaggers-for-mac-users-now-for-2024/"><u>[Updated] The Finest 6 Video Snaggers for Mac Users Now for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-grasp-free-to-use-vimeo-editing-techniques/"><u>2024 Approved  Grasp Free-to-Use Vimeo Editing Techniques</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-the-hub-of-your-youtube-success/"><u>2024 Approved  Navigating the Hub of Your YouTube Success</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/6-methods-to-mirror-apple-iphone-xr-to-your-windows-pc-drfone-by-drfone-ios/"><u>6 Methods to Mirror Apple iPhone XR to your Windows PC | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-remote-desktop-failures-in-current-windows/"><u>Addressing Remote Desktop Failures in Current Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/blending-techniques-for-seamless-picture-merging/"><u>Blending Techniques for Seamless Picture Merging</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/decoding-the-essentials-of-german-linguistics/"><u>Decoding the Essentials of German Linguistics</u></a></li>
<li><a href="https://win11.techidaily.com/fix-static-speakers-after-disabling-default-sounds/"><u>Fix Static Speakers After Disabling Default Sounds</u></a></li>
<li><a href="https://vp-tips.techidaily.com/from-novice-to-expert-free-lut-techniques-for-color-grading-for-2024/"><u>From Novice to Expert  Free LUT Techniques for Color Grading for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-mcuicntexe-entry-point-not-found-error-on-windows/"><u>How to Fix the “McUICnt.exe Entry Point Not Found” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-app-is-using-the-camera-already-0xa00f4243-error-on-windows/"><u>How to Fix the Another App Is Using the Camera Already 0xA00F4243 Error on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-6-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 6 to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-gt-5-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Realme GT 5 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-iphone-xr-without-itunes-drfone-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked iPhone XR Without iTunes | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-5-solutions-for-oppo-find-x6-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Oppo Find X6 Unlock Without Password</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-11-pro-max-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone 11 Pro Max When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-efficiently-engaging-recovery-tool/"><u>Key Steps for Efficiently Engaging Recovery Tool</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-image-editing-techniques-for-subject-separation/"><u>Masterful Image Editing: Techniques for Subject Separation</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-fine-tune-windows-with-ease-using-alomware-suite/"><u>Navigate & Fine-Tune Windows with Ease Using AlomWare Suite</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obtrusive-quit-request-error-in-roblox-players-computers/"><u>Overcoming Obtrusive Quit Request Error in Roblox Players' Computers</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-windows-11-cc-issues/"><u>Quick-Fix Strategies for Windows 11 CC Issues</u></a></li>
<li><a href="https://win11.techidaily.com/quicker-battlenet-file-syncing-on-windows-devices/"><u>Quicker Battle.net File Syncing on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/refinement-of-visuals-windows-11-dpi-tweaks/"><u>Refinement of Visuals: Windows 11 DPI Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-windows-automatic-deletion/"><u>Revolutionize File Management with Windows' Automatic Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-creativity-microsoft-paints-fresh-additions/"><u>Revolutionizing Creativity: Microsoft Paint's Fresh Additions</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gaming-setup-direct-to-windows-ps3-pad/"><u>Seamless Gaming Setup: Direct-to-Windows PS3 Pad</u></a></li>
<li><a href="https://win11.techidaily.com/sharpen-system-speed-lowering-high-usage-of-interest-tasks/"><u>Sharpen System Speed: Lowering High Usage of Interest Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-acquire-and-implement-microsoft-stores-application-bundles/"><u>Simple Steps to Acquire & Implement Microsoft Store's Application Bundles</u></a></li>
<li><a href="https://tech-hub.techidaily.com/solving-chatgpt-plugin-service-connection-problems/"><u>Solving ChatGPT Plugin Service Connection Problems</u></a></li>
<li><a href="https://win11.techidaily.com/stop-system-spontaneities-fixing-windows-11-restarts/"><u>Stop System Spontaneities: Fixing WIndows 11 Restarts</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-11-installation-with-these-essential-tweaks/"><u>Streamline Your Windows 11 Installation with These Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-usage-options-on-windows-11-devices-and-systems/"><u>Streamlining Usage Options on Windows 11 Devices and Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-zero-empty-directories-issue-in-windows-11-and-11/"><u>Tackling the Zero-Empty Directories Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/ten-simple-steps-for-fixing-def5-onedrive-woes-on-win11/"><u>Ten Simple Steps for Fixing DEF5: OneDrive Woes on Win11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-solution-to-missing-avcodecdll-errors-in-windows-1087/"><u>The Ultimate Solution to Missing Avcodec.dll Errors in Windows 10/8/7</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-9-free-android-mp3-extractors/"><u>Top 9 FREE Android MP3 Extractors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-audio-access-failures-in-audacity/"><u>Troubleshooting Audio Access Failures in Audacity</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-samsung-galaxy-xcover-6-pro-tactical-edition-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Samsung Galaxy XCover 6 Pro Tactical Edition FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/uncluttered-windows-desktop-at-a-glance/"><u>Uncluttered Windows Desktop at a Glance</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-beast-boosting-fps-in-cs-go/"><u>Unleash the Beast - Boosting FPS in CS Go</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-java-vm-error-on-windows/"><u>Unraveling the Mystery of Java VM Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-a-strategy-to-resolve-locked-windows-update/"><u>Unveiling a Strategy to Resolve Locked Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/visual-clarity-in-note-taking-with-obsidian-design/"><u>Visual Clarity in Note-Taking with Obsidian Design</u></a></li>
<li><a href="https://win11.techidaily.com/windows-filing-mastery-key-principles-max-156/"><u>Windows Filing Mastery: Key Principles (Max 156)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
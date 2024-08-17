---
title: How to Make Win OS Files Editable Again
date: 2024-08-16T00:20:10.078Z
updated: 2024-08-17T00:20:10.078Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make Win OS Files Editable Again
excerpt: This Article Describes How to Make Win OS Files Editable Again
keywords: Restore Win File Permissions,Editing Windows Files,Regain File Accessibility,Overcoming Read-Only Errors,Modify WinOS Documents,Unlock OS File Lock,Change Read-Only Windows Files
thumbnail: https://thmb.techidaily.com/b43da9b8fec14dde01c0becd6729005fd0db59f099a461c4a5b1f228776ffdea.jpg
---

## How to Make Win OS Files Editable Again

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-top-10-youtube-business-channels-and-how-to-create-one-easily/"><u>[New] 2024 Approved  Top 10 YouTube Business Channels and How to Create One Easily</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pioneering-color-grading-with-3d-luts/"><u>[New] Pioneering Color Grading with 3D LUTs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-essential-tips-for-perfect-gopro-time-lapse-for-2024/"><u>[New] The Essential Tips for Perfect GoPro Time Lapse for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-2023-updates-the-next-generation-of-samsung-k850u/"><u>[Updated] 2023 Updates - The Next Generation of Samsung K850U</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unleashing-discord-video-talks-desktop-and-mobile-guide-for-2024/"><u>[Updated] Unleashing Discord Video Talks - Desktop & Mobile Guide for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-augment-pixel-tiles-with-concentric-blur-magic-ps/"><u>2024 Approved  Augment Pixel Tiles with Concentric Blur Magic PS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-solo-creators-path-to-dynamic-animation-art/"><u>2024 Approved  The Solo Creator’s Path to Dynamic Animation Art</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-zoomview-partition-inspection/"><u>2024 Approved  ZoomView Partition Inspection</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-xiaomi-mix-fold-3-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Xiaomi Mix Fold 3? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-find-missing-devices-in-dm/"><u>Bridge the Gap: Find Missing Devices In DM</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-microsoft-edges-heavy-background-tasks/"><u>Curbing Microsoft Edge's Heavy Background Tasks</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo T2 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-macos-with-cross-platform-windows-features/"><u>Enhancing macOS with Cross-Platform Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-server-not-available-error-steams-content-link-issue/"><u>Fixing Server Not Available Error: Steam's Content Link Issue</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-itel-p55t-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Itel P55T | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-from-iphone-15-pro-max-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud from iPhone 15 Pro Max Safe and Legal</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-unwrapped-to-personalized-perfection-10-leading-shopping-platforms/"><u>In 2024, From Unwrapped to Personalized Perfection  10 Leading Shopping Platforms</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/innovative-and-elite-tech-devices-for-the-savvy-shopper/"><u>Innovative and Elite Tech Devices for the Savvy Shopper</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-activating-windows-recovery-software/"><u>Key Steps for Activating Windows Recovery Software</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-permissions-to-prevent-read-only-mode/"><u>Mastering File Permissions to Prevent Read-Only Mode</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-fixing-audacitys-failed-sound-device-openings-on-win-os/"><u>Methods for Fixing Audacity's Failed Sound Device Openings on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-code-0xc00ce556/"><u>Navigating Windows Error Code: 0XC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sound-system-issue-with-windows-general-device/"><u>Overcoming Sound System Issue with Windows General Device</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dormant-radeon-software-interface/"><u>Quick Fixes for Dormant Radeon Software Interface</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/removing-personal-data-from-the-windows-login-area/"><u>Removing Personal Data From the Windows Login Area</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-access-error-on-windows-a-step-by-step-guide/"><u>Resolving File Access Error on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/tailor-your-narrative-crafting-engaging-youtube-descriptions-using-pre-set-templates/"><u>Tailor Your Narrative  Crafting Engaging YouTube Descriptions Using Pre-Set Templates</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-route-from-gaming-archives-to-windows-memories/"><u>The Essential Route From Gaming Archives to Windows Memories</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-science-of-choosing-music-for-movie-previews-for-2024/"><u>The Science of Choosing Music for Movie Previews for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-poco-m6-pro-4g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Poco M6 Pro 4G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-a-runtime-broker-unpacking-its-importance-for-pcs/"><u>What Is a Runtime Broker? Unpacking Its Importance for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
</ul></div>

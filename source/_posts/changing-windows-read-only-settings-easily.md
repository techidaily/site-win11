---
title: Changing Windows Read-Only Settings Easily
date: 2024-08-16T00:09:36.241Z
updated: 2024-08-17T00:09:36.241Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Windows Read-Only Settings Easily
excerpt: This Article Describes Changing Windows Read-Only Settings Easily
keywords: Change ReRead Only WinSettings,Simplify WinReadModify,EasyWinRWControlToggle,AlterWindowsReadLock,UnlockReadOnlyFileWin,TweakWindowsLockedFiles,EnableEditReadFilesWin
thumbnail: https://thmb.techidaily.com/bf32c159170edbc355c721b22ee8ee6c67dda36feed408fdb0ec7f3ca8b4ddc2.jpg
---

## Changing Windows Read-Only Settings Easily

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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
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
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-maximizing-money-smart-tactics-for-video-monetization/"><u>[New] 2024 Approved  Maximizing Money  Smart Tactics for Video Monetization</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-guide-to-turn-off-ig-predictions-for-2024/"><u>[New] The Guide to Turn Off IG Predictions for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/our-first-steps-in-video-content-creation/"><u>[New] Your First Steps in Video Content Creation</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-drive-more-watch-time-not-churn-discover-the-top-6-techniques-on-youtube-for-2024/"><u>[Updated] Drive More Watch Time, Not Churn  Discover the Top 6 Techniques on YouTube for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-effective-ways-to-archive-and-record-youtube-events/"><u>[Updated] Effective Ways to Archive and Record Youtube Events</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-relaxation-playlist-20-sweetest-country-tunes-on-tiktok/"><u>[Updated] In 2024, Relaxation Playlist  20 Sweetest Country Tunes on TikTok</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-tips-for-capturing-whatsapp-chat-calls-methods-and-techniques-for-2024/"><u>[Updated] Tips for Capturing WhatsApp Chat Calls  Methods & Techniques for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-insiders-guide-overcome-iphone-video-dullness-using-4-adobe-solutions/"><u>2024 Approved  [Insider's Guide] Overcome iPhone Video Dullness Using 4 Adobe Solutions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-chinese-vr-headset-marketplace-wonders/"><u>2024 Approved  Chinese VR Headset Marketplace Wonders</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-highest-quality-radio-dramatic-works/"><u>2024 Approved  Highest Quality Radio Dramatic Works</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-metaverse-giggles-galore-ingenious-ways-to-craft-memes/"><u>2024 Approved  Metaverse Giggles Galore  Ingenious Ways to Craft Memes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-realizing-your-cinematic-dreams-the-art-of-perfect-sound-in-videos/"><u>2024 Approved  Realizing Your Cinematic Dreams  The Art of Perfect Sound in Videos</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/christmas-edition-enhance-windows-11/"><u>Christmas Edition: Enhance Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-how-to-execute-system-file-checker-sfc/"><u>Command Line: How to Execute System File Checker (SFC)</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsoft-family-safetys-core-functions/"><u>Decoding Microsoft Family Safety's Core Functions</u></a></li>
<li><a href="https://win11.techidaily.com/discover-why-your-windows-11-icons-are-diminishing/"><u>Discover Why Your Windows 11 Icons Are Diminishing</u></a></li>
<li><a href="https://win11.techidaily.com/does-the-geforce-experience-scan-fail-on-windows-heres-how-to-fix-it/"><u>Does the GeForce Experience Scan Fail on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-team-chats-on-windows-1110/"><u>Ensuring Smooth Team Chats on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-overcome-common-flaws-in-windows-applications/"><u>Essential Tips to Overcome Common Flaws in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-alternatives-how-to-access-imessage-on-windows/"><u>Exploring Alternatives: How to Access iMessage on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-novice-to-pro-mastering-the-art-of-editing-via-polarr-for-2024/"><u>From Novice to Pro  Mastering the Art of Editing via Polarr for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-phantom-v-fold-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Phantom V Fold to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6s-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6s to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-find-x7-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my Find X7</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-enhancing-visuals-iphone-magnification-hacks/"><u>In 2024, Enhancing Visuals  IPhone Magnification Hacks</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-bypass-the-required-apple-store-verification-for-iphone-6s-by-drfone-ios/"><u>In 2024, How To Bypass the Required Apple Store Verification For iPhone 6s</u></a></li>
<li><a href="https://win11.techidaily.com/make-ms-word-defaultly-use-reading-pane-for-email-attachments-no-editing/"><u>Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win-rpc-failures-five-must-try-fixes/"><u>Navigating Win RPC Failures: Five Must-Try Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/non-light-no-problem-master-five-cures-for-backlit-keyboard-failure/"><u>Non-Light, No Problem: Master Five Cures for Backlit Keyboard Failure</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launch-failures-fixing-windows-speech-recognition/"><u>Overcoming Launch Failures: Fixing Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/securely-storing-passwords-windows-file-integration-guide/"><u>Securely Storing Passwords: Windows File Integration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-control-of-active-elements-post-sleep/"><u>Strategic Control of Active Elements Post-Sleep</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-a-guide-to-idle-shutdown-in-windows-11/"><u>Streamline System Use: A Guide to Idle Shutdown in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-git-management-harnessing-power-with-github-desktop-and-windows-11/"><u>The Art of Git Management: Harnessing Power with GitHub Desktop & Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tips-to-revive-non-printing-hp-all-in-ones/"><u>Tips to Revive Non-Printing HP All-In-Ones</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-boost-mobile-iphone-13-before-the-plan-expires-by-drfone-ios/"><u>Unlock Your Boost Mobile iPhone 13 Before the Plan Expires</u></a></li>
<li><a href="https://network-issues.techidaily.com/win10-cant-find-wi-fi-driver-solved/"><u>Win10 Can't Find Wi-Fi Driver, Solved</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-moment-update-a-treasure-trove-of-features/"><u>Windows 11'S Moment Update - A Treasure Trove of Features?</u></a></li>
</ul></div>

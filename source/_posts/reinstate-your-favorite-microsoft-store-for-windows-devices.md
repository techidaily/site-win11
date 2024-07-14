---
title: Reinstate Your Favorite Microsoft Store for Windows Devices
date: 2024-07-13T10:32:21.726Z
updated: 2024-07-14T10:32:21.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
excerpt: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
keywords: WinStore Restore,MSFT Store Access,Reinstate MSOFT,Windows Device Hub,Devices Store Fix,Microsoft Window Support,Retrieve MStores
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Reinstate Your Favorite Microsoft Store for Windows Devices

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-the-essential-guide-to-affordable-video-conferencing-tools-for-corporateeducational-use-for-2024/"><u>[New] The Essential Guide to Affordable Video Conferencing Tools  For Corporate/Educational Use for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-system-audio-windows-11-mixer-configuration-steps/"><u>Fine-Tuning System Audio: Windows 11 Mixer Configuration Steps</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-enlightened-techniques-to-preserve-your-iptv-streams/"><u>In 2024, Enlightened Techniques to Preserve Your IPTV Streams</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-maximize-your-hd-vids-experience-the-ultimate-android-apps-list/"><u>2024 Approved  Maximize Your Hd Vids Experience  The Ultimate Android Apps List</u></a></li>
<li><a href="https://win11.techidaily.com/leap-ahead-your-in-store-purchase-speed-on-ms-platform/"><u>Leap Ahead Your In-Store Purchase Speed on MS Platform</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-utorrent-download-halt-on-windows-os/"><u>Overcoming uTorrent Download Halt on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-read-only-folders-a-step-by-step-guide/"><u>Unlocking Read-Only Folders: A Step-by-Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-xiaomi-redmi-note-12-5g-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Xiaomi Redmi Note 12 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-cybersecurity-essential-windows-protection-tips/"><u>Mastery in Cybersecurity: Essential Windows Protection Tips</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-lost-ms-store-access-on-windows-11-and-11/"><u>Reactivating Lost MS Store Access on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-credential-vault-access-blocks/"><u>Overcome Credential Vault Access Blocks</u></a></li>
<li><a href="https://win11.techidaily.com/probing-into-the-heart-of-windows-11-system32/"><u>Probing Into the Heart of Windows 11: System32</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-trembling-cursor-a-guide-to-windows/"><u>Stop the Trembling Cursor: A Guide to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/safeguard-your-screen-from-autonomous-scrolling/"><u>Safeguard Your Screen From Autonomous Scrolling</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-the-antique-ribbon-interface-of-explorer/"><u>Restoring the Antique Ribbon Interface of Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-dll-file-disappearance-on-windows/"><u>Troubleshooting DLL File Disappearance on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-a-disabled-app-in-windows/"><u>How to Unblock a Disabled App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-steps-before-factory-clearing-a-pc/"><u>Top 7 Steps Before Factory Clearing a PC</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-unused-disk-space-in-windows-efficiently/"><u>Harnessing Unused Disk Space in Windows Efficiently</u></a></li>
<li><a href="https://extra-tips.techidaily.com/everything-you-need-to-know-before-upgrading-to-windows-10/"><u>Everything You Need To Know Before Upgrading To Windows 10</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-mastering-digital-vhs-image-modification-techniques/"><u>2024 Approved  Mastering Digital VHS Image Modification Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-storage-space-a-window-into-w10-and-w11-disks/"><u>Mastering Your Storage Space: A Window Into W10 & W11 Disks</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-turning-twitter-video-into-engaging-customizable-gifs-for-2024/"><u>[Updated] Turning Twitter Video Into Engaging Customizable GIFs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/explore-and-manage-windows-11-writable-components/"><u>Explore and Manage Windows 11' Writable Components</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-installation-restrictions-in-windows-11/"><u>Resolving Installation Restrictions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hibernation-a-windows-users-guide/"><u>Resurrecting Hibernation: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-your-login-with-these-11-ultimate-tricks-to-open-windows-credentials/"><u>Speed Up Your Login with These 11 Ultimate Tricks to Open Windows Credentials</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-browse-the-list-of-the-best-8-scanners-or-converters-for-converting-the-slides-to-digital-images-also-know-the-other-important-information-of-slides-to-/"><u>New Browse the List of the Best 8 Scanners or Converters for Converting the Slides to Digital Images. Also, Know the Other Important Information of Slides to Digital Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/reward-system-reboot-for-your-favorite-titles/"><u>Reward System Reboot for Your Favorite Titles</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-git-with-github-desktop-for-windows-users/"><u>Navigating Git with GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-transform-viewership-seo-for-the-newbie-on-youtube/"><u>2024 Approved  Transform Viewership  SEO for the Newbie on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-windows-embracing-ai-dominance/"><u>Tomorrow's Windows: Embracing AI Dominance</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-realme-narzo-60x-5g-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Realme Narzo 60x 5G</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-macos-via-external-windows-utilities/"><u>Supercharging macOS via External Windows Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/leading-painting-programs-beyond-the-procreate-window-experience/"><u>Leading Painting Programs Beyond the Procreate Window Experience</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-restoring-functionality-of-ccleaner-in-windows-1011-pcs/"><u>Guide for Restoring Functionality of CCleaner in Windows 10/11 PCs</u></a></li>
<li><a href="https://fox-helps.techidaily.com/saving-gifs-on-your-iphone-a-step-by-step-approach-for-2024/"><u>Saving GIFs on Your iPhone - A Step-by-Step Approach for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-harmonic-transition-a-playlist-migration-masterclass/"><u>2024 Approved  Harmonic Transition  A Playlist Migration Masterclass</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-nonstop-teams-sign-ins-on-pc/"><u>Overcoming the Hurdle of Nonstop Teams Sign-Ins on PC</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-your-microphone-usage-with-keyboard-techniques-for-win-11/"><u>Speeding Up Your Microphone Usage with Keyboard Techniques for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-error-0x7e1-on-win1011/"><u>How to Reverse Error 0X7E1 on Win10/11</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-innovative-ai-tools-to-spark-your-podcast-written-name/"><u>[New] In 2024, Innovative AI Tools to Spark Your Podcast' Written Name</u></a></li>
<li><a href="https://win11.techidaily.com/quick-glance-windows-11-expert-guide-to-image-access/"><u>Quick Glance: Windows 11 Expert Guide to Image Access</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-instant-best-picture-viewer-pro/"><u>[Updated] In 2024, Instant Best Picture Viewer Pro</u></a></li>
<li><a href="https://win11.techidaily.com/ready-set-go-accelerate-your-pcs-warmup-with-win11-tips/"><u>Ready, Set, Go! Accelerate Your PC's Warmup with Win11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-window-hacks-restore-off-screen-on-windows-1011/"><u>Hidden Window Hacks: Restore Off-Screen on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-success-elevating-winning-frames/"><u>Fast-Track to Success: Elevating Winning Frames</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/pinnacle-10-royale-struggle-games-for-2024/"><u>Pinnacle 10 Royale Struggle Games for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/retro-redesign-challenge-windows-11-for-the-90s/"><u>Retro Redesign Challenge: Windows 11 for the ‘90S</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-adding-images-to-instagram-made-simple/"><u>[New] Adding Images to Instagram Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/stay-on-top-of-your-windows-11-devices-with-our-5-crucial-uptime-methods/"><u>Stay on Top of Your Windows 11 Devices with Our 5 Crucial Uptime Methods</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-securing-memories-a-comprehensive-guide-for-scanning-and-storing-vintage-photos/"><u>2024 Approved  Securing Memories  A Comprehensive Guide for Scanning and Storing Vintage Photos</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-m14-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy M14 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-files-preventing-read-only-in-win11/"><u>Unlocking Your Files: Preventing Read-Only in Win11</u></a></li>
</ul></div>

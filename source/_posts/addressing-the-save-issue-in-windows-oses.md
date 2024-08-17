---
title: Addressing the Save Issue in Windows OSes
date: 2024-08-15T23:17:05.062Z
updated: 2024-08-16T23:17:05.062Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing the Save Issue in Windows OSes
excerpt: This Article Describes Addressing the Save Issue in Windows OSes
keywords: Fix Windows Errors,Solve OS Glitches,Windows Stability Tips,Stop OS Crashes,Enhance OS Performance,Debugging Windows,Optimize PC Software
thumbnail: https://thmb.techidaily.com/07be777ce45c307461ad22ca534398f5c53e5285da087031d4c184f1389088d2.jpg
---

## Addressing the Save Issue in Windows OSes

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-run-a-sports-youtube-chain-on-macos/"><u>[New] 2024 Approved  How to Run a Sports YouTube Chain on MacOS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-boosting-channel-success-scaling-for-a-million-viewers-for-2024/"><u>[Updated] Boosting Channel Success  Scaling for a Million Viewers for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-daily-dharma-the-best-yoga-channels-for-self-growth/"><u>[Updated] Daily Dharma  The Best Yoga Channels for Self-Growth</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-easy-in-getting-vrecorder-on-your-pc/"><u>[Updated] Easy In  Getting VRecorder on Your PC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-dynamic-mac-screen-and-audio-capture-tool/"><u>[Updated] In 2024, Dynamic Mac Screen and Audio Capture Tool</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-perfect-iphone-mp3-conversion-top-6-software-recommendations/"><u>[Updated] Perfect iPhone MP3 Conversion  Top 6 Software Recommendations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-navigating-the-route-to-social-stardom-a-quick-overview-of-6-key-steps-on-instagram/"><u>2024 Approved  Navigating the Route to Social Stardom  A Quick Overview of 6 Key Steps on Instagram</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-transformative-strategies-in-creating-engaging-fb-content/"><u>2024 Approved  Transformative Strategies in Creating Engaging FB Content</u></a></li>
<li><a href="https://win11.techidaily.com/a-users-handbook-on-amplifying-mouse-cursor-lighting-on-win-11/"><u>A User's Handbook on Amplifying Mouse Cursor Lighting on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-file-error-xc10100bf/"><u>Addressing Windows File Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-shared-access-tools-google-vs-microsofts-nearby-sharing/"><u>Assessing Shared Access Tools: Google Vs. Microsoft's Nearby Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-emotions-easy-emoji-15-integration-for-win11/"><u>Avoid Missed Emotions: Easy Emoji 15 Integration for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-repeated-sign-in-alerts-team-collaboration-edition/"><u>Avoiding Repeated Sign-In Alerts: Team Collaboration Edition</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-breakdown-an-insiders-approach/"><u>Blue Screen Breakdown: An Insider's Approach</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dual-users-conflict-with-one-ms-login/"><u>Bypassing Dual Users’ Conflict with One MS Login</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-dual-camera-request-error-code-0xa00f4243/"><u>Dealing with Dual Camera Request Error (Code 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/easy-fixes-for-common-win-printer-issues/"><u>Easy Fixes for Common Win-Printer Issues</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visual-appeal-with-custom-pointer-design/"><u>Enhancing Visual Appeal with Custom Pointer Design</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-reviving-a-stuck-download-space-on-windows-os/"><u>Guide for Reviving a Stuck Download Space on Windows OS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-infinix-note-30-vip-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Infinix Note 30 VIP Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-merge-duplicate-person-photo-albums-on-your-iphone-and-mac/"><u>How to Merge Duplicate Person Photo Albums on Your iPhone & Mac</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-elevate-your-channels-templates-at-no-charge/"><u>In 2024, Elevate Your Channels - Templates at No Charge</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-foundations-of-fast-and-easy-nft-innovation/"><u>In 2024, Foundations of Fast & Easy NFT Innovation</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-vivo-v30-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP on Vivo V30 Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/key-considerations-when-shopping-for-a-windows-device/"><u>Key Considerations When Shopping for a Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-correction-of-writing-permissions-issue-on-pcs/"><u>Mastering Correction of Writing Permissions Issue on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-nooks-for-mac-address-in-windows-11/"><u>Navigating Network Nooks for Mac Address in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/next-gen-access-management-for-windows-administrators/"><u>Next-Gen Access Management for Windows Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-streaming-on-windows-counteracting-zero-speed-phenomenon/"><u>Optimize Streaming on Windows: Counteracting Zero-Speed Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-cannot-determine-error-on-windows-computers/"><u>Overcoming Cannot Determine Error on Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-package-registration-problems-in-windows-operating-system/"><u>Overcoming Package Registration Problems in Windows Operating System</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-honor-magic-6-lite-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Honor Magic 6 Lite? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-down-your-laptop-keyboard-with-simple-steps-in-win10win11/"><u>Quiet Down Your Laptop Keyboard with Simple Steps in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-lost-windows-secrets-for-restoring-hidden-panes-on-win-1011-with-ease/"><u>Reclaim Your Lost Windows! Secrets for Restoring Hidden Panes on Win 10/11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/reconnecting-windows-remotes-resolving-unacceptable-links/"><u>Reconnecting Windows Remotes: Resolving Unacceptable Links</u></a></li>
<li><a href="https://win11.techidaily.com/reel-in-efficiency-with-these-premium-video-editors-on-window-11/"><u>Reel-In Efficiency with These Premium Video Editors on Window 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-disconnect-error-for-malwarebytes-services-in-windows-11/"><u>Remedying Disconnect Error for Malwarebytes Services in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-media-player-server-crashes/"><u>Remedying Media Player Server Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/repair-restore-function-keys-in-windows-11/"><u>Repair: Restore Function Keys in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-seamless-link-for-windows-steam-streaming/"><u>Restoring Seamless Link for Windows Steam Streaming</u></a></li>
<li><a href="https://win-solutions.techidaily.com/six-easy-ways-to-solve-your-minecraft-crash-problems/"><u>Six Easy Ways to Solve Your Minecraft Crash Problems</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-conversations-testing-microphones-and-cameras-in-windows/"><u>Smooth Conversations: Testing Microphones & Cameras in Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/solve-your-diablo-immortal-pc-hiccups-ultimate-crash-fix-guide-for-the-modern-gamer/"><u>Solve Your Diablo Immortal PC Hiccups: Ultimate Crash Fix Guide for the Modern Gamer</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screen-interaction-proficient-use-of-windows-narrator-shortcuts/"><u>Streamlined Screen Interaction: Proficient Use of Windows Narrator Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-pc-finder-power-with-everythingapp/"><u>Supercharge PC Finder Power with EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-enabling-additional-av-software-on-windows/"><u>Techniques for Enabling Additional AV Software on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-nullifying-windows-tracking-mechanism/"><u>Techniques for Nullifying Windows' Tracking Mechanism</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721475888841-tired-of-audio-bouncing-around-in-your-airpods-disable-dynamic-head-tracking-now/"><u>Tired of Audio Bouncing Around in Your AirPods? Disable Dynamic Head Tracking Now</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-mute-reactivate-slack-alerts-in-win-11/"><u>Troubleshoot Mute: Reactivate Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-open-exes-without-issues/"><u>Troubleshooting Windows: Open EXEs Without Issues</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
</ul></div>

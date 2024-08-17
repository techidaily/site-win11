---
title: Altering Windows Lockout Duration Post-Failed Logon
date: 2024-08-15T23:38:49.664Z
updated: 2024-08-16T23:38:49.664Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows Lockout Duration Post-Failed Logon
excerpt: This Article Describes Altering Windows Lockout Duration Post-Failed Logon
keywords: Windows Login Delay,Account Unlock Time,Failed Logon Limit,Password Reset Period,Security Lockout Fix,Access Control Adjustment,Lockout Duration Change
thumbnail: https://thmb.techidaily.com/bcbbbb17c516407e41023c9df84564d9e208249f4419e84badf29d91094b0794.jpg
---

## Altering Windows Lockout Duration Post-Failed Logon

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-strategic-insights-for-triumph-in-smm/"><u>[New] Strategic Insights for Triumph in SMM</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-ultimate-instagram-photography-guide-for-crafting-perfect-covers-for-2024/"><u>[New] The Ultimate Instagram Photography Guide for Crafting Perfect Covers for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-how-to-fix-obs-not-recording-audio-for-2024/"><u>[Updated] How to Fix OBS Not Recording Audio for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-navigating-your-way-through-screen-recording-on-mac-os-x-for-2024/"><u>[Updated] Navigating Your Way Through Screen Recording on Mac OS X for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-streamlining-your-youtube-vids-for-igtv-adoption/"><u>[Updated] Streamlining Your YouTube Vids for IGTV Adoption</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-wonders-of-4k-with-benq-bl2711u-review/"><u>[Updated] Unveiling the Wonders of 4K with BenQ BL2711U Review</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-vidpin-facebook-call-recorder/"><u>2024 Approved  VidPin - Facebook Call Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience-35/"><u>7 Proven Methods to Enhance Your Windows 11 Experience (35)</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-heart-of-windows-print-controls/"><u>Accessing the Heart of Windows Print Controls</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-x70-file-and-directory-recovery-on-windows-1011/"><u>Bypassing Error X70: File and Directory Recovery on Windows 10/11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-a-successful-mukbang-video-journey-for-2024/"><u>Crafting a Successful Mukbang Video Journey for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-edges-load-times-and-resource-use/"><u>Decreasing Edge's Load Times and Resource Use</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-honor-x50-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Honor X50 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enliven-windows-11-desktop-a-step-by-step-guide-to-animated-walls/"><u>Enliven Windows 11 Desktop: A Step-by-Step Guide to Animated Walls</u></a></li>
<li><a href="https://win11.techidaily.com/flip-your-lens-6-simple-steps-for-picture-spin-on-windows-11/"><u>Flip Your Lens: 6 Simple Steps for Picture Spin on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/gently-lowering-highs-a-guide-to-windowed-serenity/"><u>Gently Lowering Highs: A Guide to Windowed Serenity</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-samsung-galaxy-a23-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-poco-m6-5g-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Poco M6 5G.</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-realme-12-proplus-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Realme 12 Pro+ 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-prosight-review-the-next-big-step-beyond-manycam/"><u>In 2024, ProSight Review  The Next Big Step Beyond ManyCam</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-bsod-data-for-system-debugging/"><u>Leveraging BSOD Data for System Debugging</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-grans-old-computer-senior-friendly-and-simple/"><u>Make Your Gran’s Old Computer Senior-Friendly & Simple</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gpu-memory-potential-in-windows-11-os/"><u>Maximizing GPU Memory Potential in Windows 11 OS</u></a></li>
<li><a href="https://data-wizards.techidaily.com/multi-platform-presence-integrating-facebook-linkedin-and-youtube/"><u>Multi-Platform Presence: Integrating Facebook, LinkedIn & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-characters-on-windows-11-screen/"><u>Navigating the Characters on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-your-guide-to-color-perfection-on-windows/"><u>Overcoming Obstacles: Your Guide to Color Perfection on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-default-heat-reduction-rules-in-winos/"><u>Reclaiming Default Heat Reduction Rules in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unseen-second-monitor-problems/"><u>Solving Unseen Second Monitor Problems</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-notes-obsidian-canvas-approach/"><u>Streamline Your Notes: Obsidian Canvas Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-vivo-t2x-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-9-issues-with-icloud-on-ios-devices-solutions-unveiled/"><u>Top 9 Issues with iCloud on iOS Devices: Solutions Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-malwarebytes-cant-properly-called-proc/"><u>Troubleshooting Error: Malwarebytes Can't Properly Called Proc</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-to-resolve-battlenet-login-on-pcs/"><u>Troubleshooting Steps to Resolve Battle.net Login on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unplugged-access-navigating-localized-onedrive-files/"><u>Unplugged Access: Navigating Localized OneDrive Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>Unraveling Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-expect-from-microsofts-win11-feb-release/"><u>What to Expect From Microsoft's Win11 Feb Release</u></a></li>
<li><a href="https://win11.techidaily.com/winx-troubleshooting-correcting-nvidias-retrieval-errors/"><u>WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors</u></a></li>
</ul></div>

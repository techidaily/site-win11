---
title: Changing the Time Before Next Login Attempt on Failure
date: 2024-07-29T15:53:56.951Z
updated: 2024-07-30T15:53:56.951Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing the Time Before Next Login Attempt on Failure
excerpt: This Article Describes Changing the Time Before Next Login Attempt on Failure
keywords: Login Time Change On Fail,Adjusting Login Delay,Prevent Repeated Logins,Login Retry Timer Modify,Post-Login Attempt Time,Alter Next Login Time,Increase Login Try Period
thumbnail: https://thmb.techidaily.com/f09a424aa99c62f7b51db30e0d97dc33c8611de88afaf819d747680f631cd289.jpg
---

## Changing the Time Before Next Login Attempt on Failure

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-chuckling-chambers-humor-for-special-days/"><u>[New] Chuckling Chambers  Humor for Special Days</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-get-into-a-friends-live-showcase-effortlessly-for-2024/"><u>[New] Get Into a Friend's Live Showcase Effortlessly for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-social-media-strategy-decoding-igtv-versus-youtubes-features/"><u>[New] In 2024, Social Media Strategy  Decoding IGTV Versus YouTube's Features</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-unlocking-the-value-in-twitters-archives/"><u>[New] Unlocking the Value in Twitters Archives</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-cyber-self-portraiture-creating-a-caricatured-emblem/"><u>[Updated] 2024 Approved  Cyber Self-Portraiture  Creating a Caricatured Emblem</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-enhance-your-media-experience-by-learning-vlcs-rotation-feature/"><u>[Updated] 2024 Approved  Enhance Your Media Experience by Learning VLC's Rotation Feature</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-essential-tips-for-digital-board-usage-during-web-conferences-on-diverse-devices/"><u>[Updated] 2024 Approved  Essential Tips for Digital Board Usage During Web Conferences on Diverse Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-top-10-hd-webcams-essential-purchasing-tips/"><u>[Updated] 2024 Approved  Top 10 HD Webcams  Essential Purchasing Tips</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-ultimate-guide-to-non-udemy-online-education-sites/"><u>[Updated] 2024 Approved  Ultimate Guide to Non-Udemy Online Education Sites</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-how-to-record-minecraft-gameplay-complete-guide-for-2024/"><u>[Updated] How to Record Minecraft Gameplay [Complete Guide] for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-how-to-create-an-instagram-business-account/"><u>[Updated] In 2024, How to Create an Instagram Business Account</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-pivot-to-popularity-mastering-video-flip-on-social/"><u>[Updated] In 2024, Pivot to Popularity  Mastering Video Flip on Social</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-iphone-xs-advanced-photography-tools/"><u>[Updated] Unveiling iPhone X's Advanced Photography Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-youtube-to-igtv-conversion-pro-tips-revealed/"><u>[Updated] YouTube-to-IGTV Conversion  Pro Tips Revealed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-essential-tips-for-storing-snapchat-videos-on-devices/"><u>2024 Approved  Essential Tips for Storing Snapchat Videos on Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/2024s-ddr5-master-cards-ranked/"><u>2024'S DDR5 Master Cards Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-open-a-games-directory-on-windows/"><u>3 Ways to Open a Game's Directory on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-how-win11-collects-your-personal-data/"><u>A Closer Look: How Win11 Collects Your Personal Data</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-success-must-haves-from-microsoft-store/"><u>Accelerated Success: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-the-ultimate-student-friendly-laptop/"><u>ASUS Vivobook S 15: The Ultimate Student-Friendly Laptop</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/compare-and-save-with-top-6-affordable-camera-picks-for-2024/"><u>Compare and Save with Top 6 Affordable Camera Picks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-firewall-defenses-in-5-easy-steps/"><u>Customizing Firewall Defenses in 5 Easy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-update-failure-code-0x80246007-windows-guide/"><u>Disabling Update Failure Code 0X80246007: Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-setup-google-play-store-on-win11/"><u>Easy Steps: Setup Google Play Store on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-secure-tcp-protocols-in-windows-os/"><u>Ensuring Secure TCP Protocols in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-ms-store-problem-fix-code-0x0-error-on-pcs/"><u>Eradicating MS Store Problem - Fix Code 0X0 Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-edges-unending-task-on-windows-11-pcs/"><u>Exploring Edge's Unending Task on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-screen-unresponsive-message-in-windows-1111/"><u>Fixing Screen Unresponsive Message in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-disabling-laptops-hardware-keys-on-windows-pc/"><u>Guide: Disabling Laptop's Hardware Keys on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-error-0x800704b3/"><u>How to Bypass Windows Error 0X800704B3</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-maximizing-conversions-with-targeted-snapad-strategies/"><u>In 2024, Maximizing Conversions with Targeted SnapAd Strategies</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-13-mini-passcode-without-a-computer-by-drfone-ios/"><u>In 2024, Unlocking iPhone 13 mini Passcode without a Computer</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-overlooked-window-11-styles/"><u>In-Depth Look at Overlooked Window 11 Styles</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-update-notifier-into-the-windows-ui-context-of-win11/"><u>Integrating Update Notifier Into the Windows UI Context of Win11</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-world-google-map-powerhouse/"><u>Microsoft World, Google Map Powerhouse</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-in-use-device-names-on-your-windows-system/"><u>Overcoming In-Use Device Names on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-display-after-power-on/"><u>Overcoming Missing Display After Power On</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-non-operational-ccleaner-on-win11/"><u>Overhauling Non-Operational CCleaner on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-gt-5-pro-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Realme GT 5 Pro Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-windows-secrets-to-handbrake-use/"><u>Reveal Windows' Secrets to HandBrake Use</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/seamless-screens-and-cameras-recording-methods/"><u>Seamless Screens & Cameras Recording Methods</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-cost-free-windows-password-gen-options-listed/"><u>Secure & Cost-Free Windows Password Gen Options Listed</u></a></li>
<li><a href="https://win11.techidaily.com/solving-failed-volume-shadow-copy-in-windows-os/"><u>Solving Failed Volume Shadow Copy in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-prevent-and-fix-winscombsvrdll-crashes-on-pcs/"><u>Steps to Prevent and Fix WinscombSvr.dll Crashes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-procedure-to-independently-update-windows/"><u>Stepwise Procedure to Independently Update Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-comic-file-access-in-modern-windows/"><u>Streamlining Comic File Access in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-cloud-using-microsoft-onedrive-offline/"><u>Taming the Cloud: Using Microsoft OneDrive Offline</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-nokia-g310-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/unleash-potential-rtx-ti-for-windows/"><u>Unleash Potential: RTX Ti for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-advanced-backup-capabilities/"><u>Unlock Advanced Backup Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-phone-link-microsofts-bluetooth-connectivity-app/"><u>Unveiling 'Phone Link': Microsoft’s Bluetooth Connectivity App</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-and-11-enable-endless-deletion-via-desktop-trash/"><u>Windows 11 & 11: Enable Endless Deletion via Desktop Trash</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
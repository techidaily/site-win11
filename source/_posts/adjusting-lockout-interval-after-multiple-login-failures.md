---
title: Adjusting Lockout Interval After Multiple Login Failures
date: 2024-07-13T11:18:52.764Z
updated: 2024-07-14T11:18:52.764Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Lockout Interval After Multiple Login Failures
excerpt: This Article Describes Adjusting Lockout Interval After Multiple Login Failures
keywords: Login Failure Adjustment,Lockout Interval Changes,Multi-Login Errors Fix,Failed Logins Management,Access Restriction Post-Failures,Security Settings Update,User Lockout Revision
thumbnail: https://thmb.techidaily.com/7111378cc0205319da99cc8db3992a3d311982c554186166a280e12ee8590487.png
---

## Adjusting Lockout Interval After Multiple Login Failures

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

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

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
<li><a href="https://win11.techidaily.com/addressing-device-access-problems-in-audacity-win/"><u>Addressing Device Access Problems in Audacity (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-realme-11x-5g-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Realme 11X 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-creative-commons-legalities-explained-simply/"><u>[Updated] Creative Commons Legalities Explained Simply</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/methods-for-restoring-full-display-in-youtube-videos-for-2024/"><u>Methods for Restoring Full Display in YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-printer-disconnection-on-windows-11-devices/"><u>Addressing Printer Disconnection on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-music-mastery-essentials-high-quality-dj-video-samples/"><u>[New] In 2024, Music Mastery Essentials  High-Quality DJ Video Samples</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-xiaomi-redmi-13c-5g-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Xiaomi Redmi 13C 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://extra-information.techidaily.com/breaking-barriers-in-drone-races-and-top-5-innovative-fpv-units-for-2024/"><u>Breaking Barriers in Drone Races & Top 5 Innovative FPV Units for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/additional-tips-about-sinnoh-stone-for-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-efficiency-strategies-for-effective-multitasking-with-windows-11/"><u>Amplify Efficiency: Strategies for Effective Multitasking with Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-best-noise-canceling-tools-top-choices-for-clean-audio-for-2024/"><u>New Best Noise-Canceling Tools Top Choices for Clean Audio for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/activating-emoji-15-support-in-windows-11/"><u>Activating Emoji 15 Support in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-mastering-music-creation-the-6-best-free-daw-choices-for-newcomers/"><u>New Mastering Music Creation The 6 Best Free DAW Choices for Newcomers</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-earnings-potential-essential-view-numbers/"><u>[Updated] Unlocking Earnings Potential  Essential View Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-looking-to-access-the-whole-spectrum-of-shared-media-by-contacts/"><u>[New] 2024 Approved  Looking to Access the Whole Spectrum of Shared Media by Contacts</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-motion-detection-made-easy-best-apps-for-mobile-devices/"><u>Updated 2024 Approved Motion Detection Made Easy Best Apps for Mobile Devices</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-collect-audio-files-from-fb-newsfeeds/"><u>2024 Approved  Collect Audio Files From FB Newsfeeds</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-transform-your-viewing-experience-activating-av1-on-youtube/"><u>[New] Transform Your Viewing Experience  Activating AV1 on YouTube</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-iphone-15-pro-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From iPhone 15 Pro in the Best Ways</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-chatbots-maintaining-security-in-your-windows-11-access/"><u>Avoiding Chatbots: Maintaining Security in Your Windows 11 Access</u></a></li>
<li><a href="https://win11.techidaily.com/age-friendly-features-in-pre-windows-10-systems/"><u>Age-Friendly Features in Pre-Windows 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-11-taskbar/"><u>Addressing Non-Operational Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/simple-steps-to-great-videos-crafting-10-basic-concepts-easily-for-2024/"><u>Simple Steps to Great Videos  Crafting 10 Basic Concepts Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-when-ipad-images-fault-during-transfer-to-windows/"><u>Actions to Take When iPad Images Fault During Transfer to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-time-whats-new-between-windows-10-and-11/"><u>Ahead of Time: What's New Between Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-connection-failure-error-of-mb-in-windows-11/"><u>Addressing the Connection Failure Error of MB in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-leading-tips-seamless-youtube-to-mpeg-conversion-guide/"><u>2024 Approved  Leading Tips  Seamless YouTube-to-MPEG Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-touch-of-nature-implementing-weather-icon-in-windows-11-status-bar/"><u>Adding a Touch of Nature: Implementing Weather Icon in Windows 11 Status Bar</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-reset-redmi-note-13-pro-5g-phone-screen-passcode-pattern-pin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset Redmi Note 13 Pro 5G Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://win11.techidaily.com/artistic-substitutes-to-procreate-windows-based/"><u>Artistic Substitutes to Procreate, Windows-Based</u></a></li>
</ul></div>

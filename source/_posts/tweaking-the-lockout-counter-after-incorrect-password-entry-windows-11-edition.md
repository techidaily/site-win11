---
title: Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
date: 2024-08-15T23:36:43.729Z
updated: 2024-08-16T23:36:43.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
excerpt: This Article Describes Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition
keywords: Win11 Password Error Fix,Lockout Counter Update Win11,Correct Pass Retry Options Win11,Preventing Incorrect Login Windows,Windows 11 Lockout Revision,Resetting Windows 11 Login Attempts,Adjusting Password Failures Win11
thumbnail: https://thmb.techidaily.com/a6de986a3fdb94c7142abb7e1738397c8994a30f493de897d20f957481bc1b83.jpg
---

## Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-incorporating-zoom-for-video-conferencing-a-guide-for-gmail-professionals/"><u>[New] 2024 Approved  Incorporating Zoom for Video Conferencing  A Guide for Gmail Professionals</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-insiders-approach-to-webinar-preservation/"><u>[New] 2024 Approved  Insider's Approach to Webinar Preservation</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-automatic-cycling-of-videos-on-iphone-ease/"><u>[New] In 2024, Automatic Cycling of Videos on iPhone Ease</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-secure-5-insta-story-watchers-selection-for-2024/"><u>[New] Secure 5 Insta Story-Watchers' Selection for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-supreme-sync-audio-player-android-flair/"><u>[New] Supreme Sync Audio Player, Android Flair</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-budget-friendly-broadcaster-gear-for-video-voyeurs/"><u>[Updated] In 2024, Budget-Friendly Broadcaster Gear for Video Voyeurs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-mobiledesktop-seamless-fb-video-downloading-2023/"><u>[Updated] In 2024, Mobile/Desktop  Seamless FB Video Downloading, 2023</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-next-level-cinema-selection-youtube-edition/"><u>[Updated] Next-Level Cinema Selection - YouTube Edition</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-avoid-monetization-mishaps-essential-youtube-checks/"><u>2024 Approved  Avoid Monetization Mishaps  Essential YouTube Checks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-making-the-most-of-virtual-reality-space/"><u>2024 Approved  Making the Most of Virtual Reality Space</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-mastering-screens-with-active-8-a-comparative-review/"><u>2024 Approved  Mastering Screens with Active 8 - A Comparative Review</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-top-10-text-manipulators-boosting-affects-craft/"><u>2024 Approved  Top 10 Text Manipulators Boosting Affects Craft</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-motorola-moto-g23-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Motorola Moto G23 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/5-ways-to-rewind-a-twitch-live-stream/"><u>5 Ways to Rewind A Twitch Live Stream</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-future-skies-top-weather-apps-for-pc/"><u>A Window Into Future Skies: Top Weather Apps for PC</u></a></li>
<li><a href="https://win11.techidaily.com/chocolatey-vs-windows-package-manager-which-is-the-better-tool-to-download-software-on-windows/"><u>Chocolatey Vs. Windows Package Manager: Which Is the Better Tool to Download Software on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/combat-windows-11-lags-top-strategies-to-boost-speed/"><u>Combat Windows 11 Lags: Top Strategies to Boost Speed</u></a></li>
<li><a href="https://screen-capture.techidaily.com/comprehensive-analysis-of-frozen-treat-screen-capture/"><u>Comprehensive Analysis of Frozen Treat Screen Capture</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-secure-boot-the-ultimate-rufus-guidebook/"><u>Conquering Secure Boot: The Ultimate Rufus Guidebook</u></a></li>
<li><a href="https://driver-install.techidaily.com/conquering-usbasp-driver-hurdles-on-widely-spanning-windows-oss/"><u>Conquering USBasp Driver Hurdles on Widely Spanning Windows OSs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-your-dell-latitude-e6420-drivers-fast-and-simple-steps/"><u>Download Your Dell Latitude E6420 Drivers: Fast and Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-vm-management-hosting-linux-on-a-windows-system-with-hyper-v/"><u>Efficient VM Management: Hosting Linux on a Windows System with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-digital-sketching-with-microsoft-paint-updates/"><u>Elevating Digital Sketching with Microsoft Paint Updates</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-not-enough-privileges-error-during-installation-on-windows/"><u>Eliminating Not Enough Privileges Error During Installation on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ethernet-efficiency-top-tips-to-test-your-networks-pace-on-windows/"><u>Ethernet Efficiency: Top Tips to Test Your Network's Pace on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/free-electronic-signatures-for-svd-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>Free electronic signatures for .svd file</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-realme-narzo-n53-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Realme Narzo N53 Devices</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-v29-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo V29 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-modify-calculators-color-scheme-dark/"><u>How To Modify Calculator's Color Scheme (Dark)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-battlenet-desktop-client-successfully/"><u>How to Reactivate Battle.net Desktop Client Successfully</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-v30-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo V30 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Realme C55 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-chronicle-conversations-on-google/"><u>In 2024, Chronicle Conversations on Google</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-essential-insight-the-most-efficient-snipping-software-for-windows/"><u>In 2024, Essential Insight  The Most Efficient Snipping Software for WINDOWS</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harmonizing-hues-the-filmmakers-palette-guide/"><u>In 2024, Harmonizing Hues  The Filmmaker's Palette Guide</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-analysis-of-the-linksys-ea9500-a-smart-and-mighty-networking-device/"><u>In-Depth Analysis of the Linksys EA9500: A Smart and Mighty Networking Device</u></a></li>
<li><a href="https://extra-tips.techidaily.com/innovative-approaches-to-video-voiceover-integration/"><u>Innovative Approaches to Video Voiceover Integration</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-track-windows-10-and-11-note-hacks/"><u>Keeping Track: Windows 10 & 11 Note Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microphone-settings-in-w11-systems/"><u>Mastering Microphone Settings in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-error-0x8007251d-windows-activation-demystified/"><u>Mastery over Error 0X8007251D: Windows Activation Demystified</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-prevalent-windows-rainmeter-troubles/"><u>Navigating Through Prevalent Windows Rainmeter Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-startup-options-a-comprehensive-guide/"><u>Navigating Win11 Startup Options: A Comprehensive Guide</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-a-quick-take-on-vn-video-editors-pc-performance/"><u>New A Quick Take on VN Video Editors PC Performance</u></a></li>
<li><a href="https://win11.techidaily.com/operating-unity-windows-rolls-out-across-apple-pc-mac-android-world/"><u>Operating Unity: Windows Rolls Out Across Apple, PC, Mac, Android World</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-15-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 15 Data From iTunes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-thermal-policy-in-windows-environment/"><u>Restoring Missing Thermal Policy in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-driver-not-running-error-in-windows-11/"><u>Solutions for Driver Not Running Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-choices-activating-filters-on-windows-11-files/"><u>Streamline Choices: Activating Filters on Windows 11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-all-inclusive-guide-to-the-feature-packed-budget-friendly-ambient-weather-station-the-ws-2902a-osprey/"><u>The All-Inclusive Guide to the Feature-Packed, Budget-Friendly Ambient Weather Station: The WS-2902A Osprey</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-5-online-titler-pros-unveiled-for-2024/"><u>Top 5 Online Titler Pros Unveiled for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-exception-breaking-point-achieved-in-windows/"><u>Troubleshooting Error: Exception Breaking Point Achieved in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-mail-issues-with-html-enhanced-emails/"><u>Troubleshooting Windows 11 Mail Issues with HTML-Enhanced Emails</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-guide-reactivate-disabled-slack-notifications/"><u>Win 11 Guide: Reactivate Disabled Slack Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-webp-saving-chrome-image-format-change-guide/"><u>Win Over WebP Saving: Chrome Image Format Change Guide</u></a></li>
</ul></div>

---
title: Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems
date: 2024-09-11T09:30:07.523Z
updated: 2024-09-12T09:30:07.523Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems
excerpt: This Article Describes Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems
keywords: Windows 11 Login Resets,Win11 Unauthorized Access,Increment Failed Login Counts,Enhancing Login Security,Password Lockout Mechanism,Preventing Brute Force Attacks,Managing Failed Logins Windows
thumbnail: https://thmb.techidaily.com/897a54d20c0fe274d0937962de97f84511515ba57539d3344fb75e1f209995c6.png
---

## Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-10-cheeky-tunes-turned-parodies/"><u>[New] 2024 Approved  10 Cheeky Tunes Turned Parodies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-phantom-gag-craftsman/"><u>[New] Phantom Gag Craftsman</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ecrets-of-content-creators-finding-free-music-for-2024/"><u>[New] Secrets of Content Creators  Finding Free Music for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-explore-tools-that-beat-sharex-performance/"><u>[Updated] 2024 Approved  Explore Tools That Beat ShareX Performance</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-discover-the-power-of-asus-proart-4k-the-pa-329q-review-for-2024/"><u>[Updated] Discover the Power of Asus ProArt 4K - The PA 329Q Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-to-filter-kids-web-activity/"><u>Configuring Windows 11 to Filter Kids' Web Activity</u></a></li>
<li><a href="https://win11.techidaily.com/cure-voice-command-issues-reactivation-techniques-for-win11/"><u>Cure Voice Command Issues: Reactivation Techniques for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-path-to-exceptional-windows-wallpapers/"><u>Decoding the Path to Exceptional Windows Wallpapers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exclusive-look-inside-the-ultimate-bambu-lab-mattress-for-double-sized-dreaming/"><u>Exclusive Look Inside the Ultimate Bambu Lab Mattress for Double-Sized Dreaming</u></a></li>
<li><a href="https://win11.techidaily.com/fast-focus-furious-fighting-efficient-gameplay-fixes-for-bf2/"><u>Fast Focus, Furious Fighting: Efficient Gameplay Fixes for BF2</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-your-windows-sleep-timer/"><u>Fine-Tune Your Window's Sleep Timer</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-external-monitor-not-detected-issue-in-windows/"><u>Fixing External Monitor Not Detected Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-notifications-from-phone-link-app-in-windows-environment/"><u>Fixing Inactive Notifications From Phone Link App in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/future-on-display-the-premium-laptops-at-ifa-2023/"><u>Future on Display: The Premium Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-roblox-error-code-403-on-pc/"><u>Guide to Fixing Roblox Error Code 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/hands-on-steps-for-buying-adobe-reader-in-microsoft-store/"><u>Hands-On Steps for Buying Adobe Reader in Microsoft Store</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-infinix-gt-10-pro-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Infinix GT 10 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-mini-to-other-iphone-13-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 mini To Other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/live-microphone-input-addressing-recording-issues-with-obs-w11-edition/"><u>Live Microphone Input: Addressing Recording Issues with OBS, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-or-minimize-windows-11-taskbar/"><u>Maximize or Minimize Windows 11 Taskbar</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-2024-approved-how-to-translate-tiktok-videos-top-5-auto-translate-tools/"><u>New 2024 Approved How to Translate TikTok Videos Top 5 Auto Translate Tools</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-without-installation-in-windows-11/"><u>Notetaking Without Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/old-meets-new-again-seven-core-windows-characteristics-evolving/"><u>Old Meets New Again: Seven Core Windows Characteristics Evolving</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Oppo Find X6 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-stay-connected-eight-ways-to-enhance-win11-point/"><u>Reconnect and Stay Connected: Eight Ways to Enhance Win11' Point</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-alerts-on-desktop-applets/"><u>Restoring Alerts on Desktop Applets</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-installation-blockers-for-effective-win-11-uninstalls/"><u>Sidestep Installation Blockers for Effective Win 11 Uninstalls</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/social-media-melody-ownership-laws-for-2024/"><u>Social Media Melody Ownership Laws for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frustrating-asana-issues-with-a-step-by-step-guide/"><u>Solving Frustrating Asana Issues with a Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stop-chromes-spontaneous-tab-triggers-on-windows-desktop/"><u>Stop Chrome's Spontaneous Tab Triggers on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-decrease-cpu-strain-from-tiworkerexe-processes/"><u>Strategies to Decrease CPU Strain From TiWorker.exe Processes</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unsupported-device-format-required-in-windows/"><u>Tackling Unsupported Device: Format Required in Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-guide-to-finding-and-restoring-erased-numbers-on-android-phones/"><u>The Ultimate Guide to Finding and Restoring Erased Numbers on Android Phones</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rotating-images-on-win11/"><u>The Ultimate Guide to Rotating Images on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-reactivating-lost-pin-access-in-windows-11/"><u>Troubleshooting: Reactivating Lost Pin Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-of-old-computers-without-windows/"><u>Unleash Potential of Old Computers Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-efficient-directory-creation-with-newest-windows-oses/"><u>Unleash the Power of Efficient Directory Creation with Newest Windows OSes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-whats-better-than-subtitle-edit-for-mac-explore-these-options-for-2024/"><u>Updated Whats Better Than Subtitle Edit for Mac? Explore These Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-wise-utorrent-speeding-up-downloads-made-simple/"><u>Win-Wise uTorrent: Speeding Up Downloads Made Simple</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
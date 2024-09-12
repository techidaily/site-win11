---
title: "Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
date: 2024-09-11T09:46:26.281Z
updated: 2024-09-12T09:46:26.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
excerpt: "This Article Describes Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11"
keywords: Lockout Management Guide,Failed Login Triggers Changes,Access Denied Resolution Steps,Unauthorized Sign-Out Adjustments,Post-Lockout System Tweaks,Security Protocols After Failures,Lockout Alterations Guidebook
thumbnail: https://thmb.techidaily.com/72178c55a17f02b5af426d7fce9f5984667c0f559291ba6b4b11d31fc14a8936.jpg
---

## Managing Lockout Counter: Alterations After Unsuccessful Sign-Ins W10/W11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

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

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115915/19272" target="_top" id="2115915">
  <img src="//a.impactradius-go.com/display-ad/19272-2115915" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115915/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/est-video-makers-with-music-and-photos-for-2024/"><u>[New] Best Video Makers with Music and Photos for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-how-to-record-google-meet-for-free-for-2024/"><u>[New] How to Record Google Meet for Free for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-step-by-step-how-to-conduct-real-time-calls-via-whatsapp-on-pc/"><u>[Updated] 2024 Approved Step by Step How to Conduct Real-Time Calls via WhatsApp on PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-learn-to-post-multimedia-video-edition-on-twitter-for-2024/"><u>[Updated] Learn to Post Multimedia Video Edition on Twitter for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-streaming-snapshots-for-facebook-2023-for-2024/"><u>[Updated] Streaming Snapshots for Facebook, 2023 for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-accessing-disguised-user-responses-on-yt/"><u>2024 Approved Accessing Disguised User Responses on YT</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-fashioning-small-homes-with-eastern-aesthetics/"><u>2024 Approved Fashioning Small Homes with Eastern Aesthetics</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-manage-srt-files-in-winmac-environments/"><u>2024 Approved Manage SRT Files in Win/Mac Environments</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-video-enhancement-ranking-the-superior-15-gopro-lut-tools/"><u>2024 Approved Pro Video Enhancement Ranking the Superior 15 GoPro LUT Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-picks-premium-and-economical-bdr-players-for-pcmac/"><u>2024 Approved Top Picks Premium & Economical BDR Players for PC/Mac</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-xiaomi-redmi-note-12-proplus-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Xiaomi Redmi Note 12 Pro+ 5G</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-production-value-with-free-sfx-libraries/"><u>Boost Production Value with Free SFX Libraries!</u></a></li>
<li><a href="https://solve-latest.techidaily.com/comprendre-le-processus-de-mining-benefices-et-applications-essentielles/"><u>Comprendre Le Processus De Mining : Benefices Et Applications Essentielles</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-0x0000011b-operation-errors/"><u>Correcting Windows' 0X0000011B Operation Errors</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/detailed-analysis-by-tom-on-latest-computer-hardware-innovations/"><u>Detailed Analysis by Tom on Latest Computer Hardware Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-show-internet-speed-using-desktop-widgets/"><u>Efficiently Show Internet Speed Using Desktop Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/enable-rgb-control-for-windows-11-display/"><u>Enable RGB Control for Windows 11 Display</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-and-efficiency-using-a-90-degree-display-shift/"><u>Enhance Visibility & Efficiency Using a 90-Degree Display Shift</u></a></li>
<li><a href="https://win11.techidaily.com/enriched-notepad-on-win11-with-tech-sage/"><u>Enriched Notepad on Win11 with Tech Sage</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/essential-techniques-for-effective-srt-file-creation-for-2024/"><u>Essential Techniques for Effective SRT File Creation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-mastering-your-workflow-with-mspcm-on-w11/"><u>Expert Techniques: Mastering Your Workflow with MSPCM on W11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-uninstall-issues-with-epic-games-hub-on-windows-11/"><u>Fix Uninstall Issues with Epic Games Hub on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/getting-rid-of-windows-11s-official-store/"><u>Getting Rid of Windows 11'S Official Store</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-assemble-your-facebook-album-in-seconds-for-2024/"><u>How to Assemble Your Facebook Album in Seconds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clean-install-windows-11/"><u>How to Clean Install Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-embed-command-prompt-bar-in-taskmgr-windows-11/"><u>How to Embed Command Prompt Bar in TaskMgr (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-websites-as-desktop-apps-on-windows/"><u>How to Install Websites as Desktop Apps on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 To Other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-iphone-se-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For iPhone SE?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-nokia-c300-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Nokia C300 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-self-expression-through-instacraze-100-captivating-captions/"><u>In 2024, Self-Expression Through #InstaCraze 100 Captivating Captions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-guide-uploading-vimeo-videos/"><u>Instagram Guide Uploading Vimeo Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/live-the-future-with-mycam-video-recording-revolution/"><u>Live the Future with MyCam Video Recording Revolution</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-efficiency-essential-windows-apps-for-peak-performance/"><u>Maximize Efficiency: Essential Windows Apps for Peak Performance</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-network-settings-unveiling-group-policies/"><u>Navigate to Network Settings: Unveiling Group Policies</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/navigating-language-varieties-with-ease-via-chatgpt/"><u>Navigating Language Varieties with Ease via ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-group-policies-a-proactive-compliance-strategy/"><u>Refreshing Group Policies: A Proactive Compliance Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/relaunch-ms-store-programs-efficiently-in-windows-1011/"><u>Relaunch MS Store Programs Efficiently in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/retro-to-revitalized-atlasos-for-old-pcs/"><u>Retro to Revitalized: AtlasOS for Old PCs</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-processes-for-word-file-transformations-on-win-11-os/"><u>Simplified Processes for Word File Transformations on Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-alleviate-wlanextexes-power-drain/"><u>Steps to Alleviate WLANEXT.EXE's Power Drain</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-development-github-desktop-and-windows-11-synergy/"><u>Streamlining Development: GitHub Desktop & Windows 11 Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-fix-for-windows-11-login-blunders/"><u>The Ultimate Fix for Windows 11 Login Blunders</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-your-windows-11s-5g-link/"><u>The Ultimate Guide to Restoring Your Windows 11’S 5G Link</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-windows-to-dos-compilation/"><u>The Ultimate Windows To-Dos Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-way-through-credential-manager/"><u>Unlock Your Way Through Credential Manager</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-future-key-upgrades-from-microsofts-feb-win11-patch/"><u>Unveiling the Future: Key Upgrades From Microsoft's Feb Win11 Patch</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-backup-functionality-details/"><u>Unveiling Windows 11'S Backup Functionality Details</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-9-methods-to-halt-system-functions/"><u>Windows 11: 9 Methods to Halt System Functions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
---
title: Modifying Password Reset Timeframe Post-Failure in Win 10/11
date: 2024-09-05T08:40:12.142Z
updated: 2024-09-06T08:40:12.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Password Reset Timeframe Post-Failure in Win 10/11
excerpt: This Article Describes Modifying Password Reset Timeframe Post-Failure in Win 10/11
keywords: Windows Password Reset,Delayed PassReset Time,PC Security Change,OS Update Failure Fix,Windows Login Adjustment,System Access Retry Period,Secure Credential Modification
thumbnail: https://thmb.techidaily.com/50a0e21454dc02c593e958f3f8488f7e3d42941b95d888cc2e5f79586c9b13d4.jpg
---

## Modifying Password Reset Timeframe Post-Failure in Win 10/11

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-navigating-full-hd-display-on-twitter-videos/"><u>[New] 2024 Approved  Navigating Full HD Display on Twitter Videos</u></a></li>
<li><a href="https://article-files.techidaily.com/new-adobes-photo-jiggle-decrease-enhancing-or-eliminating-in-2024/"><u>[New] Adobe's Photo Jiggle Decrease  Enhancing or Eliminating, In 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-discover-creative-ways-to-enhance-your-fb-video-ads-for-2024/"><u>[New] Discover Creative Ways to Enhance Your FB Video Ads for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-how-to-utilize-snap-camera-effectively-for-real-time-collaboration-in-meet/"><u>[New] In 2024, How to Utilize Snap Camera Effectively for Real-Time Collaboration in Meet</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-snapchats-best-practices-for-image-and-video-zooming/"><u>[New] Snapchat's Best Practices for Image and Video Zooming</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-elite-compilation-9-online-mic-recorders-ranked-for-2024/"><u>[New] The Elite Compilation  9 Online Mic Recorders Ranked for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-iphone-filmmaking-101-capturing-time-in-pixels-for-2024/"><u>[Updated] IPhone Filmmaking 101  Capturing Time in Pixels for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-2023s-samsung-bd-j5900-a-detailed-look/"><u>2024 Approved  2023'S Samsung BD-J5900  A Detailed Look</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premier-live-basketball-experience-at-home/"><u>2024 Approved  Premier Live Basketball Experience at Home</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streamlining-online-meetings-zoom-and-gmail-sync-strategies/"><u>2024 Approved  Streamlining Online Meetings  Zoom & Gmail Sync Strategies</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-cinematic-revolution-exploring-the-best-shots-and-lighting-tips-24-edition/"><u>2024 Approved  The Cinematic Revolution  Exploring the Best Shots & Lighting Tips - '24 Edition</u></a></li>
<li><a href="https://driver-download.techidaily.com/compatible-drivers-for-the-dell-inspiron-15-on-windows-11/"><u>Compatible Drivers for the Dell Inspiron 15 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/digital-dots-top-8-window-friendly-note-apps/"><u>Digital Dots: Top 8 Window-Friendly Note Apps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/echoes-expanse-a-compreshift-of-best-speech-to-text-applications/"><u>Echoes Expanse  A Compreshift of Best Speech-to-Text Applications</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-web-interaction-enable-mouse-gestures-in-microsofts-edge-browser/"><u>Elevate Your Web Interaction: Enable Mouse Gestures in Microsoft's Edge Browser</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhancing-screen-quality-fixes-for-outriders-blurry-image-problems/"><u>Enhancing Screen Quality: Fixes for Outriders' Blurry Image Problems</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fixed-cannot-insert-object-error-in-excel-2019-step-by-step-guide-stellar-by-stellar-guide/"><u>Fixed Cannot Insert Object Error in Excel 2019 | Step-by-Step Guide | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-nvidia-experience-on-windows-devices/"><u>Fixing Unresponsive NVIDIA Experience on Windows Devices</u></a></li>
<li><a href="https://youtube-help.techidaily.com/fresh-inspirations-for-streaming-topics-for-2024/"><u>Fresh Inspirations for Streaming Topics for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/from-scraps-to-stunning-a-photomontage-journey/"><u>From Scraps to Stunning  A Photomontage Journey</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unaltered-screenscape-in-windows-11/"><u>Guide to Unaltered Screenscape in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-oneplus-nord-n30-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on OnePlus Nord N30 5G</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-discord-installation-has-failed-error-on-windows-11-and-11/"><u>How to Fix the Discord “Installation Has Failed” Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-vmware-bsod-error-on-windows-11/"><u>How to Fix VMware BSOD Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-windows-error-code-1053-for-non-responsive-services/"><u>How to Handle Windows' Error Code 1053 for Non-Responsive Services</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revert-windows-11s-search-bar-to-a-search-icon/"><u>How to Revert Windows 11'S Search Bar to a Search Icon</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-atandt-iphone-14-plus-with-3-methods-by-drfone-ios/"><u>How to Unlock AT&T iPhone 14 Plus with 3 Methods</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-motorola-razr-40-ultra-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Motorola Razr 40 Ultra to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-6-plus-to-other-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 6 Plus to Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-iphone-13-pro-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud From your iPhone 13 Pro</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-is-ipogo-not-working-on-poco-f5-pro-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Poco F5 Pro 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-ed-inspired-visuals-to-windows/"><u>Introducing Ed-Inspired Visuals to Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/machine-learning-framespace-upscaling-for-improved-gameplay-fluidity-and-increased-frame-rates/"><u>Machine Learning Framespace Upscaling for Improved Gameplay Fluidity and Increased Frame Rates</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-books-unlocking-potential-with-7-top-study-methods-on-a-windowed-computer/"><u>Master the Books: Unlocking Potential with 7 Top Study Methods on a Windowed Computer</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-remedies-for-windows-app-issues-7-steps-to-success/"><u>Masterful Remedies for Windows App Issues, 7 Steps to Success</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-powertoys-in-win11-setup/"><u>Mastering Microsoft PowerToys in Win11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-excessive-heat-on-windows-11-devices/"><u>Mitigating Excessive Heat on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-new-era-of-interactive-technology-between-pc-and-galaxy/"><u>Navigating a New Era of Interactive Technology Between PC & Galaxy</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-error-0x80041015-in-ms-word-and-excel/"><u>Quick Fixes for Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-your-desktop-icon-order/"><u>Reclaiming Your Desktop Icon Order</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-fabricated-device-specification-error-in-win-11/"><u>Rectifying Fabricated Device Specification Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-access-fixing-frozen-windows-terminals-quickly/"><u>Regaining Access: Fixing Frozen Windows Terminals Quickly</u></a></li>
<li><a href="https://win-able.techidaily.com/resolution-guide-fixing-the-nvidia-geforce-experience-e0x0003-error/"><u>Resolution Guide: Fixing the NVIDIA GeForce Experience E_0x0003 Error</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-not-available-errors-on-your-windows-11-pc/"><u>Resolving 'Network Not Available' Errors on Your Windows 11 PC</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-non-functional-bluetooth-drivers-for-qualcomm-atheros-devices-on-windows-11/"><u>Resolving Non-Functional Bluetooth Drivers for Qualcomm Atheros Devices on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-uninstalls-that-fail/"><u>Resolving Windows 10/11 Uninstalls That Fail</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-your-corrupted-windows-11-trash/"><u>Restoring Functionality to Your Corrupted WIndows 11 Trash</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safeguarding-your-data-the-top-6-cybersecurity-issues-with-chatgpt/"><u>Safeguarding Your Data: The Top 6 Cybersecurity Issues with ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-a-unresponsive-discord-overlay-in-windows/"><u>Solving the Puzzle of a Unresponsive Discord Overlay in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-into-the-twilight-zone-paints-dark-mode-magic/"><u>Step Into the Twilight Zone: Paint's Dark Mode Magic</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-indexer-in-windows/"><u>Steps to Tweak Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-workflows-with-windows-11-multitasking-tips/"><u>Streamline Workflows with Windows 11 Multitasking Tips</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sign-in-with-windows-hello-biometrics/"><u>Streamlining Sign-In with Windows Hello Biometrics</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-hidden-taskbar-explorer-of-windows-11/"><u>Tapping Into Hidden Taskbar Explorer of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-factors-for-choosing-windows-10-over-the-latest-operating-system-win11/"><u>Top Factors for Choosing Windows 10 over the Latest Operating System - Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-mobile-hotspot-connectivity-on-windows-11/"><u>Troubleshooting Failed Mobile Hotspot Connectivity on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-app-execution-variants-and-usage/"><u>Understanding App Execution Variants & Usage</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
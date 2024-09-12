---
title: How to Re-Register Microsoft Store Apps on Windows 10 & 11
date: 2024-09-11T09:36:08.925Z
updated: 2024-09-12T09:36:08.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Re-Register Microsoft Store Apps on Windows 10 & 11
excerpt: This Article Describes How to Re-Register Microsoft Store Apps on Windows 10 & 11
keywords: Regain MS Store Access,Restore Windows Store Apps,Resetting MS Store License,Reinstate Microsoft Store,Redoing MS App Registration,Fixing MS Store on W10/W11,Unlocking MS Store for PC
thumbnail: https://thmb.techidaily.com/1da8846cbd836d9712f7b59a73630f863ec9ad2fa528ea4ddf23335f3fc8b9a6.png
---

## How to Re-Register Microsoft Store Apps on Windows 10 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128843/7443" target="_top" id="2128843">
  <img src="//a.impactradius-go.com/display-ad/7443-2128843" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128843/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/new-navigating-facebooks-automatic-video-features/"><u>[New] Navigating Facebook's Automatic Video Features</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-title-design-in-after-effects/"><u>[New] The Art of Title Design in After Effects</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-elevate-creativity-with-pro-editor-secrets-for-canva-for-2024/"><u>[Updated] Elevate Creativity with Pro Editor Secrets for Canva for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-in-depth-look-at-gecata-capture-tool/"><u>[Updated] In 2024, In-Depth Look at Gecata Capture Tool</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-elemental-concepts-in-kinetic-design-workflow/"><u>2024 Approved Elemental Concepts in Kinetic Design Workflow</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cracking-the-code-windows-versioning-insight/"><u>Cracking the Code: Windows Versioning Insight</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-copilot-key-in-windows-11-enhance-your-experience/"><u>Decoding Copilot Key in Windows 11 - Enhance Your Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-the-process-behind-xbox-cloud-games/"><u>Discovering the Process Behind Xbox Cloud Games</u></a></li>
<li><a href="https://win11.techidaily.com/electrical-use-analysis-for-windows-computers-unveiled/"><u>Electrical Use Analysis for Windows Computers Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/enable-missing-sd-card-view-on-file-explorer-platform/"><u>Enable Missing SD Card View on File Explorer Platform</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-windows-1111-ui-for-auto-check-updates/"><u>Enabling Windows 11/11 UI for Auto-Check Updates</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-oppo-reno-10-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Oppo Reno 10 5G Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-in-depth-investigating-windows-memory-integrity-breach/"><u>Ftdibus.sys in Depth: Investigating Windows Memory Integrity Breach</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-best-linux-features-with-windows-apps/"><u>How to Get the Best Linux Features With Windows Apps</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a15-4g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A15 4G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-inspire-dont-impose-the-art-of-attracting-subscribers/"><u>In 2024, Inspire, Don't Impose The Art of Attracting Subscribers</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-accessibility-must-know-tips/"><u>Intro to Windows Accessibility: Must-Know Tips</u></a></li>
<li><a href="https://win11.techidaily.com/kickstart-windows-11-help-and-support-mechanism/"><u>Kickstart Windows 11 Help & Support Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-explorer-top-errors-and-how-to-evade-them/"><u>Mastering File Explorer: Top Errors & How to Evade Them</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-xbox-mic-troubleshooting-in-windows-11-platforms/"><u>Mastering Xbox Mic Troubleshooting in Windows 11 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-game-potential-with-these-pro-gamers-top-tips-for-win-11/"><u>Maximize Game Potential with These Pro-Gamers' Top Tips for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-functional-adjustments-windows-1011-edition/"><u>Navigating Functional Adjustments: Windows 10/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-exe-opener-dilemmrances/"><u>Overcoming Windows Exe Opener Dilemmrances</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-ui-fidelity-on-newest-windows-release/"><u>Perfecting UI Fidelity on Newest Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/precision-tactics-for-perfect-window-updates/"><u>Precision Tactics for Perfect Window Updates</u></a></li>
<li><a href="https://win11.techidaily.com/purple-pandemonium-a-guide-to-regaining-your-pcs-true-colors/"><u>Purple Pandemonium? A Guide to Regaining Your PC's True Colors</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-visual-placement-on-windows-devices/"><u>Reversing Visual Placement on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-game-with-expert-multitasking-techniques-for-windows-11/"><u>Step Up Your Game with Expert Multitasking Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-geforce-nows-error-code-0xc0f1103f-in-windows/"><u>Steps to Fix GeForce Now's Error Code 0Xc0f1103f in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-error-e8024002e/"><u>Steps to Overcome Windows Error E:8024002E</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721463469996-struggling-with-delayed-messaging-on-your-iphone-try-these-9-quick-fixes/"><u>Struggling with Delayed Messaging on Your iPhone? Try These 9 Quick Fixes!</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-technique-to-design-personalized-lock-patterns-on-windows-11/"><u>The Complete Technique to Design Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-comprehensive-guide-to-10-best-meme-patterns/"><u>The Comprehensive Guide to #10 Best Meme Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-guide-to-disbanding-disk-divisions-in-win-os/"><u>The Comprehensive Guide to Disbanding Disk Divisions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-picks-of-drawing-apps-for-windows-11-enthusiasts/"><u>The Top 7 Picks of Drawing Apps for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-list-of-ios-tools-for-erasing-intrusive-images-for-2024/"><u>The Ultimate List of iOS Tools for Erasing Intrusive Images for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/time-tracker-tweaks-top-apps-to-modify-file-timestamps-on-pc/"><u>Time Tracker Tweaks: Top Apps to Modify File Timestamps on PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-oppo-reno-11f-5g-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Oppo Reno 11F 5G Device</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-5-premium-4k-ultra-hd-video-players-for-desktop-pcmac-downloads-and-detailed-reviews/"><u>Top 5 Premium 4K Ultra HD Video Players for Desktop (PC/Mac): Downloads and Detailed Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-your-digital-steps-in-windows-11/"><u>Tracing Your Digital Steps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-into-a-personalized-oasis-8-winbubble-upgrades/"><u>Transform Windows Into a Personalized Oasis: 8 WinBubble Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/turning-phones-into-windows-audio-input/"><u>Turning Phones Into Windows Audio Input</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-audacitys-windows-compatibility-issue-9999/"><u>Unlocking Audacity's Windows Compatibility Issue #9999</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-blue-screen-mysteries-where-are-the-logs/"><u>Unlocking Blue Screen Mysteries: Where Are the Logs?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/wheres-the-magic-explore-real-world-hidden-gems-through-location-services/"><u>Where's the Magic? Explore Real-World Hidden Gems Through Location Services</u></a></li>
<li><a href="https://win11.techidaily.com/win-pc-download-speedups-navigate-the-net-faster/"><u>Win-PC Download Speedups: Navigate the Net Faster</u></a></li>
<li><a href="https://win11.techidaily.com/winning-torrent-clients-the-best-of-windows-list/"><u>Winning Torrent Clients: The Best of Windows List</u></a></li>
</ul></div>


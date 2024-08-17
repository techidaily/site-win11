---
title: "Diving Into Shortened Terms: Alias & Application Lifecycle"
date: 2024-08-15T23:30:53.370Z
updated: 2024-08-16T23:30:53.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Diving Into Shortened Terms: Alias & Application Lifecycle"
excerpt: "This Article Describes Diving Into Shortened Terms: Alias & Application Lifecycle"
keywords: Dive Into Aliases,Term Lifecycles,Alias Impact,Appl. Lifecycle Insight,Shortened Keywords,Alias Usage Trends,Lifecycle Management
thumbnail: https://thmb.techidaily.com/4e339c0438a311f0739fe8dd767b8fe136567e49f78cba1047e1590ff1927d2b.png
---

## Diving Into Shortened Terms: Alias & Application Lifecycle

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://youtube-web.techidaily.com/024-approved-mastering-the-art-of-selecting-free-music-for-videos/"><u>[New] 2024 Approved  Mastering the Art of Selecting Free Music for Videos</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-mastering-video-caption-implementation-on-vimeo/"><u>[New] 2024 Approved  Mastering Video Caption Implementation on Vimeo</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-ultimate-ranking-the-leading-15-affordable-online-image-editors/"><u>[New] 2024 Approved  Ultimate Ranking  The Leading 15 Affordable Online Image Editors</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-superior-drones-at-your-fingertips/"><u>[New] In 2024, Superior Drones at Your Fingertips</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-independent-evaluation-the-3dr-solo-experience/"><u>[New] Independent Evaluation  The '3DR' Solo Experience</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-safe-sign-in-getting-back-into-facebook-for-2024/"><u>[New] Safe Sign-In  Getting Back Into Facebook for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-beyond-the-surface-10-under-the-radar-facts-about-reels/"><u>[Updated] 2024 Approved  Beyond the Surface  10 Under-the-Radar Facts About Reels</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-the-future-of-iptv-screening-and-preservation-techniques-for-2024/"><u>[Updated] The Future of IPTV Screening and Preservation Techniques for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-olympic-zenith-highlighting-snowboard-x-races/"><u>2024 Approved  Olympic Zenith  Highlighting Snowboard X Races</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-ranking-the-greats-top-15-stop-motion-masterpieces/"><u>2024 Approved  Ranking the Greats - Top 15 Stop Motion Masterpieces</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-drone-editors-toolkit-techniques-for-visual-excellence/"><u>2024 Approved  The Drone Editor's Toolkit  Techniques for Visual Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/3-key-steps-for-a-quick-return-to-desktop-in-wins-1011/"><u>3 Key Steps for a Quick Return to Desktop in Wins 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-open-the-appsfolder-in-windows-11/"><u>7 Ways to Open the AppsFolder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-0x87e00017-when-downloading-ms-games/"><u>Addressing Error 0X87e00017 When Downloading MS Games</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ntoskrnlexe-overload-issue/"><u>Addressing Ntoskrnl.exe Overload Issue</u></a></li>
<li><a href="https://win-blog.techidaily.com/assassins-creed-valhalla-speed-hack-top-tips-for-smooth-gaming/"><u>Assassin's Creed: Valhalla Speed Hack - Top Tips for Smooth Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/best-web-browsing-practices-minimizing-resources-across-platforms/"><u>Best Web Browsing Practices: Minimizing Resources Across Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/boundary-defying-tech-windows-for-apple-devices-breaks-new-ground/"><u>Boundary-Defying Tech: Windows for Apple Devices Breaks New Ground</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-100mbps-wired-internet-limit-in-windows/"><u>Break Free From 100Mbps Wired Internet Limit in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-dull-cursors-simple-steps/"><u>Brightening Dull Cursors: Simple Steps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/digital-dialogues-duo-chatgpt-vs-google-bard-showdown/"><u>Digital Dialogues Duo: ChatGPT Vs. Google Bard Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-explore-tab-clamor-in-windows-11/"><u>Diminish Explore Tab Clamor in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-corruption-errors-fixing-file-issues-code-0x80070570-on-windows-11/"><u>Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/edge-persistent-operation-on-win11/"><u>Edge: Persistent Operation on Win11?</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-obstacles-hindering-discord-setup-success/"><u>Eliminating Obstacles Hindering Discord Setup Success</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/enabling-autoplay-youtube-videos-in-social-media-network/"><u>Enabling Autoplay Youtube Videos in Social Media Network</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-gameplay-with-proper-amd-radeon-configuration/"><u>Enhance Gameplay with Proper AMD Radeon Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/erasing-email-on-windows-sign-in-a-guide/"><u>Erasing Email on Windows Sign-In: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/gaining-admin-access-in-command-prompt/"><u>Gaining Admin Access in Command Prompt</u></a></li>
<li><a href="https://data-wizards.techidaily.com/guide-mending-macs-kernel-crashes/"><u>Guide: Mending Mac's Kernel Crashes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-6s-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 6s</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-unsupported-devices-warning-when-upgrading-windows/"><u>How to Handle Unsupported Devices Warning When Upgrading Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/o-make-profitable-youtube-ads-for-free-in-2024/"><u>How To Make Profitable YouTube Ads for Free, In 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-apple-iphone-15-pro-activation-lock-by-drfone-ios/"><u>How to Remove Apple iPhone 15 Pro Activation Lock</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-windows-11s-help-interaction/"><u>How to Revive Windows 11'S Help Interaction</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-5-solutions-for-nubia-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Nubia Unlock Without Password</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-broadcasting-without-rts-video-tweeting-simplified/"><u>In 2024, Broadcasting Without RTs  Video Tweeting Simplified</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gopro-face-off-max-360-vs-hero-11/"><u>In 2024, GoPro Face-Off  Max 360 vs Hero 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-google-pixel-fold-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Google Pixel Fold to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-on-iphone-12-pro-by-drfone-ios/"><u>In 2024, How to Fix when Apple Account Locked On iPhone 12 Pro?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-inside-obs-alternatives-for-professional-streamers/"><u>In 2024, Inside OBS Alternatives for Professional Streamers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-mastering-the-art-of-locating-fb-lately-seen-videos/"><u>In 2024, Mastering the Art of Locating Fb Lately Seen Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-simplifying-screen-record-functions-on-iphone-7/"><u>In 2024, Simplifying Screen Record Functions on iPhone 7</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-taking-over-ig-monthly-strategies-to-hit-the-1k-follower-goal/"><u>In 2024, Taking Over IG  Monthly Strategies to Hit the 1K Follower Goal</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-nokia-abuse-review-stunning-display-and-imaging-capabilities-at-an-unbeatable-value/"><u>In-Depth Nokia Abuse Review - Stunning Display & Imaging Capabilities at an Unbeatable Value</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-icon-resolution-on-windows-11-taskbar/"><u>Mastering Icon Resolution on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-on-windows/"><u>Mastering the Art of CR2 to JPG Conversion on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-purging-partitions-on-your-win-os/"><u>Mastering the Art of Purging Partitions on Your Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-account-sign-in-troubleshooting/"><u>Mastering Windows 11 Account Sign-In Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-reboot-file-explorer-on-win1011/"><u>Methods to Reboot File Explorer on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fix-kit-conquering-error-code-0x80-cookies/"><u>Microsoft Store Fix Kit: Conquering Error Code 0X80 Cookies</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-video-driver-restart-woes-in-windows-1110/"><u>Navigating Through Video Driver Restart Woes in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-hurdles-for-epic-games/"><u>Overcoming Windows Login Hurdles for Epic Games</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-recovering-lost-access-to-launcher/"><u>Quick Fixes for Recovering Lost Access to Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-navigation-for-uwp-apps-with-windows-11-links/"><u>Rapid Navigation for UWP Apps with Windows 11 Links</u></a></li>
<li><a href="https://win11.techidaily.com/reinstalling-the-redundant-or-missing-windows-tools-and-add-ons/"><u>Reinstalling the Redundant or Missing Windows Tools & Add-Ons</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-err0r-x7e1-in-win1011/"><u>Remedying Err0r: X7E1 in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-device-sticky-note-integration-on-win11/"><u>Seamless Multi-Device Sticky Note Integration on WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-stuck-scrolling-in-excel-window-edition/"><u>Solutions for Stuck Scrolling in Excel, Window Edition</u></a></li>
<li><a href="https://win11.techidaily.com/speak-up-against-silence-fixes-to-free-your-spacebar/"><u>Speak Up Against Silence: Fixes to Free Your Spacebar</u></a></li>
<li><a href="https://win11.techidaily.com/stabilize-task-manager-app-placement-techniques/"><u>Stabilize Task Manager App Placement Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-smooth-directx-installation-on-pc/"><u>Step-by-Step Guide to Smooth DirectX Installation on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-11-ui/"><u>The Essentials of Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-counter-after-incorrect-password-entry-windows-11-edition/"><u>Tweaking the Lockout Counter After Incorrect Password Entry, Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/type-smartly-and-fast-typingaid-secrets/"><u>Type Smartly and Fast - TypingAid Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-assistive-center-in-five-moves/"><u>Unlock Windows' Assistive Center in Five Moves</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-strategies-for-eradicating-microsoft-defender-footprints/"><u>Win 11 Strategies for Eradicating Microsoft Defender Footprints</u></a></li>
</ul></div>

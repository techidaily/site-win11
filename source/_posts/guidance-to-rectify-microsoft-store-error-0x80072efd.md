---
title: Guidance to Rectify Microsoft Store Error 0X80072EFD
date: 2024-09-01T04:41:51.569Z
updated: 2024-09-02T04:41:51.569Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidance to Rectify Microsoft Store Error 0X80072EFD
excerpt: This Article Describes Guidance to Rectify Microsoft Store Error 0X80072EFD
keywords: Fixing Xbox Store Error,Microsoft Store Failure Troubleshoot,Solve Store Error Code 0X80072efd,Microsoft Store Correction Guide,Remedy Xbox Online Problems,MST Error 0X80072EFDC Resolution,Microsoft Store Issue Fix Tips
thumbnail: https://thmb.techidaily.com/053654aac9195ea45d1f77852c408a3b2770cc6c802ff6728e9e3d8c452deddb.jpg
---

## Guidance to Rectify Microsoft Store Error 0X80072EFD

 Users have reported a 0x80072EFD Microsoft Store error on support forums that can arise in Windows 11 or 10\. Those users see a "server stumbled" or "check your internet connection" message with a 0x80072EFD error code inside MS Store after launching that app. When this error pops up, users can't utilize the Microsoft Store.

 The 0x80072EFD error is often a connection-related one. However, it occurs even when users can surf the web in their browsers. If you need to fix the 0x80072EFD error, try fixing it with these potential resolutions.

## 1\. Run the Windows Store App Troubleshooter

 Running the Windows Store App troubleshooter is a straightforward potential resolution for the 0x80072EFD error to start with. That troubleshooting tool might detect issues and give you a fix. You can open and run the Windows Store App troubleshooter like this:

1. Press**Start** and click the menu shortcut to open Settings.
2. Select the**Troubleshoot** section of Settings.
3. Click on**Other trouble-shooters** to look through the troubleshooting tools.
4. Select Windows Store Apps'**Run** option to bring up that troubleshooting tool.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-list-in-windows-11.jpg)
5. Go through and apply any suggestions the troubleshooter offers.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-store-apps.jpg)

**Internet Connections** is another troubleshooter that may be useful for fixing the Microsoft Store's 0x80072EFD error. So, consider running that troubleshooter if the Windows Store Apps option doesn't help.

 Note that the troubleshooting tools are accessible in the**Update & Security** category in the Settings app if you use Windows 10\. Click the**Troubleshoot** tab and**Additional troubleshooters** option to access them from there. Then press the**Run this troubleshooter** buttons for Windows Store Apps or Internet Connections.

## 2\. Refresh the SoftwareDistribution Folder

 SoftwareDistribution is a folder for temporarily storing Windows update files. Sometimes refreshing that folder by renaming it can resolve error**0x80072EFD** . Rename the SoftwareDistribution folder like this:

1. Hold down the**Windows** key and press**S** to access a search utility.
2. Type in**cmd** to find a Command Prompt app.
3. Open Command Prompt with elevated permissions by clicking its**Run as administrator** option in the search tool.
4. Turn off some services by executing these separate commands:  
`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`
5. To rename SoftwareDistribution, type in the following and hit**Enter** :  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The rename SoftwareDistribution.old folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-softwaredistribution-old-folder.jpg)
6. Also, rename a catroot2 directory with this command:  
`ren C:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-catroot2-command.jpg)
7. Restart the turned-off services by inputting and executing the following commands:  
`net start wuaserv  
net start cryptSvcc  
net start bits  
net start msiserver`
8. Then bring up your Start menu to select**Restart** .

## 3\. Reset the Microsoft Store's Cache

 Microsoft store has a cache in which data accumulates. Resetting or clearing that cache's data is a reliable solution to various Microsoft Store issues. So, we recommend users try doing that when troubleshooting the 0x80072EFD error. You can clear that cache in Settings, as covered in our[guide for resetting apps](https://www.makeuseof.com/windows-reset-app/) in Windows 11 and Windows 10.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-button.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Turn Off Proxy Server

 Some users who've needed to fix error 0x80072EFD have confirmed they resolved that issue by turning off the proxy server setting. That's because a proxy server generated a Microsoft Store connection issue on those users' PCs. You can check if a proxy server is enabled on your PC and disable it in the following steps:

1. Start the Run dialogue by pressing**Win** +**R** .
2. Type**inetcpl.cpl** inside Run's command box and click**OK** to open Internet Options.
3. Select**Connections** \>**LAN settings** to reach a**Use a proxy server** setting.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-tab.jpg)
4. Uncheck the checkbox for**Use a proxy server** if it's selected.
5. Click the**Automatically detect settings** option to select it.  
![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/use-a-proxy-server-option.jpg)
6. Select the Local Area Network window's**OK** option.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

## 5\. Double-Check the Time Settings in Windows

 An incorrect region time on your PC is another potential cause for error 0x80072EFD. Users have confirmed they've fixed error 0x80072EF by adjusting time settings on their PCs. The Microsoft Store's time tracking needs to sync with the PC's set regional time. So, have a look through your time settings as follows:

1. [Open up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and click that app's**Time & language** tab.
2. Click**Date & time** to view those settings.  
![The Date & time navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/date-time-tab.jpg)
3. Select to turn off the**Set time zone** option there.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Make sure the correct time zone for your location is selected in the**Time Zone** drop-down menu.  
![The Set the time zone automatically option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-the-time-automatically-option.jpg)
5. Then press the**Sync now** button.  
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sync-now-button.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 Alternatively, you can manually set the time by disabling the Set the time automatically option. Press the**Change** button for the**Set the date and time manually** option. Check the date and exact time for your location via online sources, and then enter it inside the**Change date & time** box.

## 6\. Enable TLS Protocols

 TLS is an encryption protocol that ensures your data privacy online. It's widely used and is essential for security when your computer communicates with internet servers.

1. Open Internet Options as specified in the first two steps for the fourth resolution.
2. Then select**Advanced** inside the Internet Options window.
3. Scroll down to the**Security** section on the**Advanced** tab.
4. Select the**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The Advanced tab in Internet Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-advanced-tab.jpg)
5. Click**Apply** to set the protocol options.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
6. Select**OK** to exit the Internet Options window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 7\. Reregister Microsoft Store

 You can't reinstall Microsoft Store like other apps. However, reregistering it with PowerShell is similar to reinstalling. If other potential solutions don't fix the 0x80072EFD error, reregistering MS Store is worth a try. This is how you can register that app:

1. Activate the**Type here to search** box with that tool's**Windows** +**S** hotkey.
2. Enter**PowerShell** within that tool's search box.
3. Launch Windows PowerShell with elevated permissions by clicking that search result's**Run as administrator** option.
4. Input this command for reregistering MS Store and hit**Return** to execute:  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reregister MS Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reregister-ms-store-command.jpg)
5. Wait until you're sure the command has finished.
6. Then exit PowerShell, and select the**Restart** option.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 8\. Reset Your Network

 Resetting network settings in Windows is another 0x80072EFD error fix that's worked for some users. Note that this measure will erase Wi-Fi and Ethernet connection details, so you'll need to re-establish your connection after applying it. You can apply this potential fix as covered in our[how-to reset networks in Windows 11](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button for networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-now-network-option.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## Get Shopping in Microsoft Store Again

 The 0x80072EFD error isn't always easy to fix, and you may have to try applying quite a few potential resolutions to get it sorted. However, many Microsoft Store users have fixed the 0x80072EFD error with the solutions in this guide. So, maybe one of those potential fixes will also work on your PC.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-demystifying-youtube-seo-terminology-and-tactics-for-2024/"><u>[New] Demystifying YouTube SEO Terminology and Tactics for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-novice-to-vlogger-professional-video-making-on-mobile-devices-for-2024/"><u>[New] From Novice to Vlogger  Professional Video Making on Mobile Devices for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-earning-potential-for-creators-in-youtube-ads-for-2024/"><u>[Updated] Earning Potential for Creators in YouTube Ads for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-finding-the-right-mic-a-guide-for-multifaceted-yt-channels-for-2024/"><u>[Updated] Finding the Right Mic  A Guide for Multifaceted YT Channels for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-selection-the-top-11-kid-friendly-waterproof-camcorders/"><u>2024 Approved  Expert Selection  The Top 11 Kid-Friendly, Waterproof Camcorders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-key-10-efficient-online-subtitle-editors/"><u>2024 Approved  Key 10 Efficient Online Subtitle Editors</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-top-6-tools-for-saving-linkedin-videos-effortlessly/"><u>2024 Approved  Top 6 Tools for Saving LinkedIn Videos Effortlessly</u></a></li>
<li><a href="https://win-dash.techidaily.com/a-guide-to-updated-and-secure-mouse-drivers-maintaining-hid-compliance-on-your-pc/"><u>A Guide to Updated and Secure Mouse Drivers: Maintaining HID Compliance on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-the-non-start-issue-for-windows-speech-recognition/"><u>Correcting the Non-Start Issue for Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-error-code-0xc00000f-in-windows/"><u>Deciphering and Resolving Error Code 0xC00000F in Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/dissecting-instagrams-per-post-video-quota/"><u>Dissecting Instagram's Per-Post Video Quota</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-battlenet-application-on-windows-pc/"><u>Fixing Unresponsive Battle.net Application on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11-anydesk-errors/"><u>Fixing Windows 11 AnyDesk Errors</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-most-out-of-windows-11-essential-settings-for-upgraded-speed/"><u>Get the Most Out of Windows 11: Essential Settings for Upgraded Speed</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-conceal-dim-display-feature-in-win-os-control-panel/"><u>Guide to Conceal Dim Display Feature in Win OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-parent-controls-on-microsoft-windows-11/"><u>Guide to Parent Controls on Microsoft Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/how-to-capture-your-iphones-screen-seamlessly/"><u>How to Capture Your iPhone's Screen Seamlessly</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-lock-apps-on-oppo-find-x6-pro-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Oppo Find X6 Pro to Protect Your Individual Information</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-random-console-window-flashes/"><u>How to Prevent Random Console Window Flashes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-12-pro-max-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your iPhone 12 Pro Max?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-complete-guide-to-recording-live-tv-on-your-windows-pc/"><u>In 2024, Complete Guide to Recording Live TV on Your Windows PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-lava-blaze-pro-5g-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Lava Blaze Pro 5G Phone with Broken Screen</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-tasks-with-these-excellent-8-windows-timer-apps/"><u>Master Your Tasks with These Excellent 8 Windows Timer Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-barriers-on-windows-11/"><u>Overcoming File Access Barriers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/premium-choices-top-windows-platforms-for-dsswitch-experience/"><u>Premium Choices: Top Windows Platforms for DS/Switch Experience</u></a></li>
<li><a href="https://win11.techidaily.com/rediscover-lost-control-panel-configurations-in-win11/"><u>Rediscover Lost Control Panel Configurations in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-non-existent-camera-issue-in-windows-device-hub/"><u>Resolve Non-Existent Camera Issue in Windows Device Hub</u></a></li>
<li><a href="https://facebook.techidaily.com/1719153977821-secure-communication-grows-facebook-rolls-out-encrypted-chat-for-messenger-and-dms/"><u>Secure Communication Grows: Facebook Rolls Out Encrypted Chat for Messenger and DMs</u></a></li>
<li><a href="https://win-blog.techidaily.com/solution-for-black-display-error-when-playing-resident-evil-village-on-pcs/"><u>Solution for Black Display Error When Playing Resident Evil Village on PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/spanish-starts-small-from-preschoolers-to-fifth-graders/"><u>Spanish Starts Small: From Preschoolers To Fifth Graders</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-your-clock-and-dates-windows-1011-guide/"><u>Tailor Your Clock and Dates: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-mind-maps-organizing-notes-using-obsidian-canvas/"><u>The Art of Mind Maps: Organizing Notes Using Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-for-efficient-browsing-ram-friendly-windows-applications-ranked/"><u>The Quest for Efficient Browsing: RAM-Friendly Windows Applications Ranked</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-networks-exploring-facebook-twitter-instagram-and-youtube/"><u>Top Social Networks - Exploring Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/track-down-and-fix-gone-data-devices-on-pc/"><u>Track Down and Fix Gone Data Devices on PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915329256-trouble-with-starting-programs-heres-how-you-can-fix-it-on-pc/"><u>Trouble with Starting Programs? Here's How You Can Fix It on PC!</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-xboxs-game-fairness-system/"><u>Understanding Xbox's Game Fairness System</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-your-win11-status-key-indicators-and-checks-for-uptime/"><u>Understanding Your Win11 Status: Key Indicators and Checks for Uptime</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-fixed-recovering-non-functional-win-apps/"><u>Unleash the Power of Fixed: Recovering Non-Functional Win-Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-webcam-visibility-alerts-in-win11/"><u>Unlocking Webcam Visibility Alerts in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/utorrent-media-player-seamless-streaming-for-2024/"><u>UTorrent Media Player  Seamless Streaming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-canary-explained-start-your-journey/"><u>Windows Canary Explained: Start Your Journey</u></a></li>
</ul></div>

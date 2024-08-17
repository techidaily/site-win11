---
title: Mastering the Resolution of Win11/10 Store Issue 0X80072EFD
date: 2024-08-16T00:50:38.736Z
updated: 2024-08-17T00:50:38.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Resolution of Win11/10 Store Issue 0X80072EFD
excerpt: This Article Describes Mastering the Resolution of Win11/10 Store Issue 0X80072EFD
keywords: Fix Win11 Error Code 0X80072efd,Win10/Win11 Resolution Problem,XeFd Store Issue Troubleshooting,Windows Update Failure Fixing,Solve WinX Error 0X80072EFD,Microsoft Store Crash Solution,Overcoming Win11/Win10 Errors
thumbnail: https://thmb.techidaily.com/88d3ccdcb9182fe6ab85d78619b5ff79c9f842144c7f0589af82188a3ec75add.jpg
---

## Mastering the Resolution of Win11/10 Store Issue 0X80072EFD

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

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Turn Off Proxy Server

 Some users who've needed to fix error 0x80072EFD have confirmed they resolved that issue by turning off the proxy server setting. That's because a proxy server generated a Microsoft Store connection issue on those users' PCs. You can check if a proxy server is enabled on your PC and disable it in the following steps:

1. Start the Run dialogue by pressing**Win** +**R** .
2. Type**inetcpl.cpl** inside Run's command box and click**OK** to open Internet Options.
3. Select**Connections** \>**LAN settings** to reach a**Use a proxy server** setting.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
4. Uncheck the checkbox for**Use a proxy server** if it's selected.
5. Click the**Automatically detect settings** option to select it.  
![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/use-a-proxy-server-option.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the Local Area Network window's**OK** option.

## 5\. Double-Check the Time Settings in Windows

 An incorrect region time on your PC is another potential cause for error 0x80072EFD. Users have confirmed they've fixed error 0x80072EF by adjusting time settings on their PCs. The Microsoft Store's time tracking needs to sync with the PC's set regional time. So, have a look through your time settings as follows:

1. [Open up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and click that app's**Time & language** tab.
2. Click**Date & time** to view those settings.  
![The Date & time navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/date-time-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
3. Select to turn off the**Set time zone** option there.
4. Make sure the correct time zone for your location is selected in the**Time Zone** drop-down menu.  
![The Set the time zone automatically option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-the-time-automatically-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Then press the**Sync now** button.  
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sync-now-button.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Alternatively, you can manually set the time by disabling the Set the time automatically option. Press the**Change** button for the**Set the date and time manually** option. Check the date and exact time for your location via online sources, and then enter it inside the**Change date & time** box.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Enable TLS Protocols

 TLS is an encryption protocol that ensures your data privacy online. It's widely used and is essential for security when your computer communicates with internet servers.

1. Open Internet Options as specified in the first two steps for the fourth resolution.
2. Then select**Advanced** inside the Internet Options window.
3. Scroll down to the**Security** section on the**Advanced** tab.
4. Select the**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The Advanced tab in Internet Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-advanced-tab.jpg)
5. Click**Apply** to set the protocol options.
6. Select**OK** to exit the Internet Options window.

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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 8\. Reset Your Network

 Resetting network settings in Windows is another 0x80072EFD error fix that's worked for some users. Note that this measure will erase Wi-Fi and Ethernet connection details, so you'll need to re-establish your connection after applying it. You can apply this potential fix as covered in our[how-to reset networks in Windows 11](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button for networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-now-network-option.jpg)

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-exciting-ios-applications-for-playing-psp-titles-1-5/"><u>[New] In 2024, Exciting iOS Applications for Playing PSP Titles #1-5</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ptimizing-channel-branding-to-skyrocket-subscriber-numbers/"><u>[New] Optimizing Channel Branding to Skyrocket Subscriber Numbers</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-vertiginous-views-unveiling-gopro-karma-capabilities/"><u>[New] Vertiginous Views  Unveiling GoPro Karma Capabilities</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-high-revenue-video-visionaries/"><u>[Updated] In 2024, High-Revenue Video Visionaries</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instamagic-weaving-your-story-with-every-posts-caption/"><u>[Updated] In 2024, Instamagic  Weaving Your Story with Every Post's Caption</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-obstacles-when-installing-java/"><u>Addressing Common Obstacles When Installing Java</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-windows-11s-misaligned-html-emails/"><u>Deciphering and Dismantling Windows 11'S Misaligned HTML Emails</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-the-distinctions-between-gpt-4-gpt-4xturbo-and-gpt-4o-models/"><u>Decoding the Distinctions Between GPT-4, GPT-4xTurbo, and GPT-4o Models</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-edge-and-keep-your-system-clean-w11/"><u>Eliminate Edge and Keep Your System Clean (W11)</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-write-unavailable-issue-in-windows/"><u>Eradicating 'Write Unavailable' Issue in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-logitech-cams-optimal-performance-with-a-free-windows-driver-download/"><u>Get Your Logitech Cam's Optimal Performance with a Free Windows Driver Download</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-or-removing-wi-fi-cost-tracking-in-win11/"><u>Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Xiaomi Mix Fold 3? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-tecno-pova-6-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-xiaomi-redmi-note-12r-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Xiaomi Redmi Note 12R Quickly? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-samsung-galaxy-z-fold-5-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Samsung Galaxy Z Fold 5</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-iphone-14-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From iPhone 14 Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-concurrent-wi-fi-and-ethernet-on-windows-pcs/"><u>Mastering Concurrent Wi-Fi and Ethernet on Windows PCs</u></a></li>
<li><a href="https://fox-helps.techidaily.com/mastering-easy-hdr-a-step-by-step-guide-for-2024/"><u>Mastering Easy HDR  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-radeon-driver-updates-in-windows-11-step-by-step-guide/"><u>Mastering Radeon Driver Updates in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-computing-10-top-alternatives-to-windows-defaults/"><u>Redefining Computing: 10 Top Alternatives to Windows' Defaults</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-memory-efficiency-for-device-interaction-windows/"><u>Streamlining Memory Efficiency for Device Interaction Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unblocked-windows-reviving-context-menus-swiftly/"><u>Unblocked Windows: Reviving Context Menus Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-mechanics-of-ai-transfer-learning-explained/"><u>Unveiling the Mechanics of AI Transfer Learning Explained</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-quick-solutions-for-cursor-on-black-screen/"><u>Win10/11: Quick Solutions for Cursor on Black Screen</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-adjustment-the-six-essential-techniques/"><u>Windows 11 Image Adjustment: The Six Essential Techniques</u></a></li>
</ul></div>

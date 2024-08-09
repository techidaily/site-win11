---
title: Addressing 'No Qt Platform Support' Error for App Starts
date: 2024-08-08T13:14:35.634Z
updated: 2024-08-09T13:14:35.634Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing 'No Qt Platform Support' Error for App Starts
excerpt: This Article Describes Addressing 'No Qt Platform Support' Error for App Starts
keywords: Fix Qt No Support Error,Qt Startup Troubleshoot,Resolve Qt Platform Error,Qt Application Launch Issue,Overcome Qt Non-Compatibility,Qt SDK Start Problems,Qt Integration Failure Fix
thumbnail: https://thmb.techidaily.com/27ed488072176012a10baf6e8c8b898cb859756da493550354750054c99fba0b.jpg
---

## Addressing 'No Qt Platform Support' Error for App Starts

 Have you recently run into the “Application failed to start because no Qt platform plugin could be initialized” error? QT is a cross-platform app that is used to generate graphical user interfaces. Even if QT support for Windows platforms is extensive, your system might display the error message when you try to open OneDrive, OBS Studio, Python, or even video games.

 While this isn’t one of the common errors on Windows, you can still fix it using the tips below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 1\. Change the QT Files Location

 Sometimes, a simple trick such as changing the QT files location is enough to get rid of the error. Here’s how you can do it:

1. Launch File Explorer and open**This PC** .
2. Using the**Search** field, search for**pyqt5\_tools** .
3. When Windows finishes the search, right-click the**pyqt5\_tools** and head to**Open folder location** .
4. Head to**PyQt5 > Qt > bin** . Copy the**platforms** folder.  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
![Fix qt error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/platforms-folder-1.jpg)
5. Make a new search for**site-packages** and open the folder.
6. There, paste the**platforms** folder.
7. Windows will warn you there’s already a folder with the same name. Click**Replace the files in the destination** .

## 2\. Run an SFC Scan

 There’s a chance Windows display the “Application failed because no QT platform plugin could be initialized” error due to corrupt system files. Fortunately, Windows has a built-in tool to help you fix the problem.

 In the Start menu search bar, search for**command prompt** and select**Run as administrator** . Then, run the**sfc /scannow** command line. Windows will scan and automatically replace any corrupted system file.

![sfc-scan-1-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-1.jpg)

 If the System File Checker didn’t fix the problem, there are [more built-in tools to repair corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Perform a Clean Boot

 One of the installed third-party apps might be the reason why you get the “Application failed because no QT platform plugin could be initialized” error. To test it,[perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) , which will force it to boot with a minimal list of programs and drivers.

 If Windows stops displaying the error, it means something you've installed on your PC is causing the problem. Take a look at your installed apps, and remove any software that might be causing the problem. If you're unsure as to what might be doing it, slowly re-enable apps through the clean boot until the issue reappears.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Update the Malfunctioning App

 An outdated version of the app you're trying to use might be the reason for the QT error. In this case, simply updating the app should solve the issue.

 If you’ve downloaded the app from Microsoft Store, launch it and head to**Library** . There, you’ll see a list of available updates. You can update the apps individually, or click**Get updates** to update them all.

![Update Microsoft Store apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mcirosoft-store-1.jpg)

## 5\. Reinstall the Troublesome App

 As the error message hints, reinstalling the app might fix the problem. When reinstalling the app, make sure you get it from its official website, to avoid any future problems.

 If you're having issues getting rid of the app, check out [how to fix Windows when it won't allow you to uninstall a program](https://www.makeuseof.com/windows-cant-uninstall-program-fix/) .

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 6\. Uninstall Any Recent Windows Updates

 Sometimes, Windows display the “Application failed because no QT platform plugin could be initialized” error after a system update. In this case, you can load a restore point to undo the change and get rid of the error.

 But if there’s no restore point available, you can manually uninstall Windows updates.

1. Launch Windows Settings by pressing**Win + I** .
2. From the left pane, click**Windows Update > Update History** .
3. Head to**Related Settings** and click**Uninstall updates** .
4. Right-click the latest update and select**Uninstall** .

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstall recent Windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-updates-1.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of the QT Error on Windows

 Hopefully, one or more of the above solutions helped you fix the “Application failed to start because no Qt platform plugin could be initialized” error.

 Sometimes, it’s difficult to figure out the exact cause of a Windows error, and reinstalling the app every time might not be the most efficient solution. To speed up the troubleshooting process, you should use one of the many Windows repair tools.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-blitz-30-second-guide-to-fast-thumbnails/"><u>[New] In 2024, Blitz  30-Second Guide to Fast Thumbnails</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-navigating-voice-logging-on-apples-facetime-service/"><u>[New] Navigating Voice Logging on Apple's FaceTime Service</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optimizing-footage-variety-in-your-video-production/"><u>[New] Optimizing Footage Variety in Your Video Production</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-laughing-moments-crafting-with-adobe/"><u>2024 Approved  Laughing Moments  Crafting with Adobe</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-techniques-for-outstanding-gopro-vlogs/"><u>2024 Approved  Top Techniques for Outstanding GoPro Vlogs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-signal-failures-windows-steam-fix-guide/"><u>Addressing Signal Failures: Windows Steam Fix Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-addressing-system-call-failed-on-pcs/"><u>Best Practices for Addressing System Call Failed on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-performance-trimming-high-memorycpu-usage-by-news-and-interests-apps-on-windows/"><u>Boosting Performance: Trimming High Memory/CPU Usage by News & Interests Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-your-dormant-device-speakers/"><u>Breathe Life Into Your Dormant Device Speakers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ing-engaging-music-reactions-the-youtube-enthusiasts-blueprint/"><u>Crafting Engaging Music Reactions  The YouTube Enthusiast's Blueprint</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-video-reset-error-on-windows-systems/"><u>Dealing with Video Reset Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-walkthrough-restoring-default-search-features-in-windows-11/"><u>Detailed Walkthrough: Restoring Default Search Features in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-experience-with-these-ultimate-strategies-for-win-11/"><u>Elevate Your Gaming Experience with These Ultimate Strategies for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-to-troubleshoot-function-keys-in-win-11/"><u>Fix: Guide to Troubleshoot Function Keys in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://win-dash.techidaily.com/improve-your-printers-functionality-freshly-updated-canon-pixma-ts3322-drivers-ready-for-download/"><u>Improve Your Printer's Functionality: Freshly Updated Canon PIXMA TS3322 Drivers Ready for Download</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-configuring-multimonitors-in-win11/"><u>Maximize Productivity: Configuring Multimonitors in Win11</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-through-dns-cache-flush-processes-for-both-windows-10-and-windows-11-users/"><u>Navigating Through DNS Cache Flush Processes for Both Windows 10 and Windows 11 Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/openais-executive-shakeup-what-does-ceo-sam-altmans-exit-mean-for-chatgpt-developments/"><u>OpenAI's Executive Shakeup: What Does CEO Sam Altman's Exit Mean for ChatGPT Developments?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-save-errors-in-windows/"><u>Overcoming Unauthorized Save Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-everlasting-deactivation-of-microsoft-defender/"><u>Secrets to Everlasting Deactivation of Microsoft Defender</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-windows-1011-automatic-file-deletion/"><u>Streamlining Storage: Windows 10/11 Automatic File Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-tasks-with-the-magic-of-flow-launcher/"><u>Supercharge Your Tasks with the Magic of Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-encryption-apps-for-windows/"><u>The 7 Best Encryption Apps for Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-definitive-guide-to-removing-persistent-youtube-channels-on-all-screens-for-2024/"><u>The Definitive Guide to Removing Persistent Youtube Channels on All Screens for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-utilizing-apples-messaging-service-on-pc/"><u>Understanding and Utilizing Apple's Messaging Service on PC</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-why-excel-opens-fail-in-notepad/"><u>Understanding Why Excel Opens Fail in Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-gateway-command-windows-11s-appsunlocked/"><u>Unlock the Gateway: Command Windows 11'S AppsUnlocked</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-now-how-to-easily-get-the-newest-driver-for-your-logitech-keyboard-on-windows-11-systems/"><u>Update Now: How to Easily Get the Newest Driver for Your Logitech Keyboard on Windows 11 Systems</u></a></li>
</ul></div>

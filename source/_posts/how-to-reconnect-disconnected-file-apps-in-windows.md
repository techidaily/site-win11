---
title: How to Reconnect Disconnected File Apps in Windows
date: 2024-08-16T00:55:24.529Z
updated: 2024-08-17T00:55:24.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reconnect Disconnected File Apps in Windows
excerpt: This Article Describes How to Reconnect Disconnected File Apps in Windows
keywords: Reconnect Files Windows,Fixing App Connectivity,Restore File Links PC,Unite Disconnected Files,Recover Data Connections,Enhance File Integrity,Harmonize App Relationships
thumbnail: https://thmb.techidaily.com/1f78d2fb13516bc942d880b1ed451501538b368f9a6b178eea0c04126c8f2280.jpg
---

## How to Reconnect Disconnected File Apps in Windows

 The error "this file does not have an app associated with it" mainly occurs when Windows can't find a compatible app for opening a specific file type. If you have the relevant app installed, it might not be set as default to open files of that format, or the app or file itself could be corrupted or damaged.

 The error can also occur when opening folders, mainly from Windows Search, and even when running apps and games. Here are some solutions you can apply to resolve this error regardless of where you get it.

## 1\. Ensure You Have an App Installed That Can Open Such Files

 Windows presents this error primarily when it fails to find the appropriate app to open files. Therefore, first, you should check whether you have the right app installed to open files in this particular format. There are several ways to check this, but here is one of the easiest:

1. Navigate to the file that is displaying this error when you open it.
2. Right-click the file and select**Properties** .
3. Navigate to the**General** tab and look for the file format next to**Type of file** .  
![Check the File Format in Properties Window of File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-1.jpg)

 If it's a commonly used file format, such as PDF, JPEG, PNG, Docx, etc., for which you have the appropriate app installed, move on directly to heading #2\. However, if you see an unusual file format here—something you haven't seen before, make sure you have the appropriate app installed.

 To confirm this, right-click the file and navigate to**Open with > Choose another app** .

![Click on Choose Another App by Right-clicking on the File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-1.jpg)

 If you have a relevant app installed, Windows will suggest you select it to open the file. If you don't see any app suggestions here, you probably don't have any apps installed capable of opening this file type.

![Windows Suggesting Some Apps to Open the Image File in PNG Format](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-suggesting-some-apps-to-open-the-image-file-in-png-format.jpg)

 If that's the case, simply go to any of your browsers, search for Windows apps that can run files in that format, and download them. After downloading the appropriate app, make it the default for opening this file type.

## 2\. Set the Default Application for the File Type

 The error message states that if the app is already installed, you need to create an association in the Default Programs. If you already had the compatible app installed or have just downloaded it, your next step should be to set it as default for files having that file type or format. Setting the compatible application as default may solve this problem right away.

 If you haven't changed a default app before, check out our article on[Windows 11 default apps](https://www.makeuseof.com/change-windows-11-default-apps/) . The article discusses various ways to change the default app, but we recommend using the second method, which is using the Settings app. That's because this method lets you search for specific file formats and choose a default app for them.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Is the Default App Already Selected? Repair or Change It

 If the app you intend to set as default for a particular file format is already selected as a default application, but Windows still displays this error, the app has likely become corrupt, thus causing the error.

 To rule out this possibility, you should run the App troubleshooter, update the problematic app, reset its cache, or repair and reset it. You can find instructions for performing these steps in our[g](https://www.makeuseof.com/apps-arent-working-properly-windows/) uide for[fixing apps that don't work on Windows](https://www.makeuseof.com/apps-arent-working-properly-windows/) .

 Try these steps to see if they fix the problem. If the issue persists after that, we recommend you reinstall the app or select a different one as the default. If you don't have a different app installed on your device that supports these files, install one that does.

## 4\. Check for Specific File Issues

 If you're opening the file in a compatible app, it's working normally, and you've already set it as default, but you're still encountering the error, verify the file itself isn't corrupt. To confirm that, open any other file having the same file format and see if it returns the same error.

 If other files open without error, but the issue persists with one file, it's likely that the file is corrupt. If that's the case, follow our[guide on using Windows built-in tools to fix corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) . If that doesn't fix the problem, try using one of the[dedicated tools for repairing corrupted files](https://www.makeuseof.com/tag/best-tools-repair-corrupted-damaged-files-windows/) .

 Misconfiguring the Registry settings can result in undesirable outcomes and even render your device unbootable. Before you try the next fix, create a[backup of the Windows Registry so you can restore it](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if something goes wrong.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 5\. Use the Registry

 If none of the above fixes have been successful, try this registry tweak as a last resort:

1. Type**"regedit"** in Windows Search and open the**Registry Editor** .  
![Open Registry Editor App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-1.jpg)
2. Paste the path below into the address bar of Registry Editor.  
Computer\HKEY_CLASSES_ROOT\lnkfile
3. Select the**Inkfile** key. Then, look in the right pane and see if there is a string value called**"IsShortcut** .**"**  
![Locate the IsShortcut String Value in the Inkfile Key of Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  
![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. If the string value is already there, right-click on it and select**Delete** .  
![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.
7. Restart your device once after that.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see[how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

## Do You Encounter the Error When Opening Apps or Games? Try These Tips

 If you get the "This file does not have an app associated with it" error when opening an app or game, perform the following checks:

* If you're using a shortcut to open games, especially the ones installed in a gaming client, open them from the gaming client or the installation directory.
* In case the game launcher requires you to log in before playing any of the installed games, ensure you do so.
* If you're experiencing this error in a specific game or app, ensure its files haven't been corrupted.

## Easily Open Your Apps, Files, and Folders Again on Windows

 Seeing the error "this file does not have an app associated with it" when opening a file, folder, or app can be frustrating. If the file or folder isn't corrupt, the above fixes will help you identify and resolve the issue's root cause. If nothing works, you can reinstall the app or restore the older version of the file or folder from your backup.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-optimize-your-gaming-by-learning-ps3-video-capture-techniques-for-2024/"><u>[New] Optimize Your Gaming by Learning PS3 Video Capture Techniques for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pazera-free-extractor-analysis-the-ultimate-guide-to-2024-sound-freedom/"><u>[New] Pazera Free Extractor Analysis  The Ultimate Guide to 2024 Sound Freedom</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-crafting-unique-valorant-thumbnails-with-style-and-flair/"><u>[Updated] 2024 Approved  Crafting Unique Valorant Thumbnails with Style and Flair</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-apex-legends-cross-play-how-to-turn-off-cross-play-and-best-platforms/"><u>[Updated] Apex Legends Cross-Play  How to Turn Off Cross-Play and Best Platforms</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-the-mi-drone-4k-review-drones-vs-landscape-photography-for-2024/"><u>[Updated] The Mi Drone 4K Review  Drones vs Landscape Photography for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/10-hidden-gem-free-mobile-games-pure-fun/"><u>10 Hidden Gem Free Mobile Games - Pure Fun!</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-hangout-history-top-4-strategies/"><u>2024 Approved  Hangout History  Top 4 Strategies</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-lose-yourself-to-laughter-best-10-jokes/"><u>2024 Approved  Lose Yourself to Laughter  Best 10 Jokes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-path-not-found-on-pc-networks/"><u>Addressing Path Not Found on PC Networks</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-read-only-shackles-of-windows-11/"><u>Breaking Free From the Read-Only Shackles of Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722996183893-call-of-duty-bokw-frozen-glitch-heres-how-to-thaw-out-the-performance-issues/"><u>Call of Duty: BOKW Frozen Glitch? Here’s How to Thaw Out the Performance Issues</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-workspace-incorporating-sketches-into-windows-11/"><u>Customize Your Workspace: Incorporating Sketches Into Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/economical-essentials-for-assembling-a-budget-friendly-home-theatre/"><u>Economical Essentials for Assembling a Budget-Friendly Home Theatre</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-to-dial-down-memorycpu-in-windows/"><u>Effective Strategies to Dial Down Memory/CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-inspecting-and-cleansing-windows-trail/"><u>Efficient Techniques for Inspecting & Cleansing Windows Trail</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-rgb-customization-on-your-win11-device/"><u>Enabling RGB Customization on Your Win11 Device</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-reliability-automatic-updates-plus-graphics-card-swap/"><u>Enhance System Reliability: Automatic Updates + Graphics Card Swap</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exclusive-discoveries-prime-websites-and-methods-to-download-tamil-ringtone-files-for-2024/"><u>Exclusive Discoveries  Prime Websites & Methods to Download Tamil Ringtone Files for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/freedomgpt-for-pc-running-ai-conversation-tools/"><u>FreedomGPT for PC: Running AI Conversation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-access-your-iphone-xs-max-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>How to Access Your iPhone XS Max When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-achieve-a-seamless-experience-less-latency-more-fps/"><u>How to Achieve a Seamless Experience: Less Latency, More FPS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-strategically-use-tags-for-youtube-success-for-2024/"><u>How to Strategically Use Tags for YouTube Success for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-note-50-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Realme Note 50 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-efficient-use-of-snap-features-to-boost-online-collaboration/"><u>In 2024, Efficient Use of Snap Features to Boost Online Collaboration</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-singing-alerts-crafting-and-configuring-customizable-sounds-and-ringtones-on-android/"><u>In 2024, Singing Alerts  Crafting and Configuring Customizable Sounds & Ringtones on Android</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-on-apple-iphone-14-pro-5-tips-you-must-know-by-drfone-ios/"><u>In 2024, Turning Off Two Factor Authentication On Apple iPhone 14 Pro? 5 Tips You Must Know</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-vct-pro-capture-assessment-full-review/"><u>In 2024, VCT Pro Capture Assessment  Full Review</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mapping-out-gpo-landscape-a-gpresult-perspective/"><u>Mapping Out GPO Landscape: A GPResult Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-effortless-data-purging-in-windows-1011/"><u>Master the Art of Effortless Data Purging in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-microsoft-powerpoint-prints-on-windows/"><u>Navigating the Maze of Microsoft PowerPoint Prints on Windows</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/quick-fixes-to-fasten-tiktok-video-speed-for-2024/"><u>Quick Fixes to Fasten TikTok Video Speed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-closed-caption-mishaps-in-windows-10/"><u>Resolving Closed Caption Mishaps in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-files-navigate-smaller-with-windows-explorer/"><u>Simplifying Files: Navigate Smaller with Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-task-of-updating-administrator-name-on-windows-11/"><u>Simplifying the Task of Updating Administrator Name on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-enhance-text-via-snip-tool-features/"><u>Step-by-Step: Enhance Text via Snip Tool Features</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://sound-issues.techidaily.com/steps-to-restore-functionality-of-your-steelseries-arctis-7-audio-input/"><u>Steps to Restore Functionality of Your SteelSeries Arctis 7 Audio Input</u></a></li>
<li><a href="https://win11.techidaily.com/system-rescue-in-13-easy-to-follow-tips/"><u>System Rescue in 13 Easy-to-Follow Tips</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-using-github-desktop-for-windows-11-dev-teams/"><u>Tailored Guide to Using GitHub Desktop for Windows 11 Dev Teams</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-snipit-try-these-top-tips-for-repairing/"><u>Trouble with SnipIt? Try These Top Tips for Repairing</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-success-removing-0x800700e9-from-your-xbox-game-pass-windows-11-setup/"><u>Unlocking Success: Removing 0X800700E9 From Your Xbox Game Pass, Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
</ul></div>

---
title: 3 Ways to Clear the Wallpaper History on Windows
date: 2024-08-15T23:27:46.072Z
updated: 2024-08-16T23:27:46.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Clear the Wallpaper History on Windows
excerpt: This Article Describes 3 Ways to Clear the Wallpaper History on Windows
keywords: Clear Win History,Wallpaper Hide,Wipe Screen Logs,Remove PNG Files,Delete Photo Cache,Erase Display Data,Reset Windows Screens
thumbnail: https://thmb.techidaily.com/a2ba2cec543d3cb7d73549581bf87f628b1caa22c3c615e97abca1f75e16831c.jpg
---

## 3 Ways to Clear the Wallpaper History on Windows

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## 1\. How to Clear the Wallpaper History via the Registry Editor

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Registry Editor is a fantastic tool that allows you to configure some PC settings or troubleshoot system issues. But before you edit the Registry keys, always ensure to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. This will ensure that you have something to revert back to if something goes wrong.

 Now, let’s explore how you can clear your wallpaper history using the Registry Editor:

1. Type **Registry Editor** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Copy and paste the following command into the address bar:

Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers

 You should see the following five background history paths on the right-hand side:

* BackgroundHistoryPath0
* BackgroundHistoryPath1
* BackgroundHistoryPath2
* BackgroundHistoryPath3
* BackgroundHistoryPath4

![Clicking the BackgroundHistoryPath4 value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-backgroundhistorypath4-value-in-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In this case, **Path0** represents the first image, while **Path4** represents the fifth image in the "wallpaper history" section.

 If you’d like to remove the first image from your wallpaper history, right-click on the **BackgroundHistoryPath0** option and select **Delete**. From there, apply the same steps to delete the other images from the "wallpaper history" section.

 Want to delete all the images simultaneously? Click on the **BackgroundHistoryPath0** option, press **Shift**, and then click on **BackgroundHistoryPath4** (this will highlight all the options). From there, press the **Delete** button.

 Finally, close the Registry Editor and restart your PC to save these changes.

## 2\. Clear Wallpaper History By Using a Registry File

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00 [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

 Now, navigate to the **File** tab and select the **Save As** option. Next, select the folder in which you'd like to save the file. From there, type **ClearMyWallpaperHistory.reg** in the **File name** section

 To use the Registry file, simply double-click on it. This should automatically clear your wallpaper history.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Overwrite the Previous Wallpaper History

 Struggling to clear your wallpaper history? Overwriting the Windows wallpaper history could help. To do that, you'd have to use five new different pictures—one at a time—as your background.

 In this case, this will only show your most recently used pictures. That way, you can indirectly "clear" any sensitive images from the wallpaper history and only display what you're comfortable with.

 Here’s how to overwrite your wallpaper history:

1. Press **Win + I** to open the system settings. Alternatively, check out [the different ways to access the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**.
4. Scroll down and click the **Browse** button. Finally, select a new image.

![Clicking the Browse button in the Background settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-browse-button-in-the-background-settings.jpg)

 Repeat this process five times. From there, you should start seeing different images in the "wallpaper history" section.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Your Previous Wallpapers Are Nowhere to Be Found

 Windows allows you to personalize your device to your liking. But then the system often keeps track of the changes you make on your PC. Fortunately, you can easily prevent others from seeing the changes you make on your device. For example, you can remove your wallpaper history using any of the methods we’ve covered.


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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-remove-pending-videos-from-your-youtube-history/"><u>[New] 2024 Approved  How to Remove Pending Videos From Your YouTube History</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-avoid-monetization-mishaps-essential-youtube-checks/"><u>[New] In 2024, Avoid Monetization Mishaps  Essential YouTube Checks</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-mastering-the-art-of-captivating-vimeo-staff-picks/"><u>[New] In 2024, Mastering the Art of Captivating Vimeo Staff Picks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nnovating-content-approaches-to-stand-out-in-shorts-arenas/"><u>[New] Innovating Content Approaches to Stand Out in Shorts Arenas</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-optimize-viewing-the-finest-html5-video-solutions/"><u>[New] Optimize Viewing  The Finest HTML5 Video Solutions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-secrets-to-flawless-game-recording-in-windows-11-for-2024/"><u>[New] Secrets to Flawless Game Recording in Windows 11 for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-unlock-zooms-full-power-with-share-screen-expertise/"><u>[Updated] 2024 Approved  Unlock Zoom’s Full Power with Share Screen Expertise</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-your-essential-guide-to-unmissable-gaming-adventures/"><u>[Updated] 2024 Approved  Your Essential Guide to Unmissable Gaming Adventures</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-best-practices-in-converting-videos-for-twitter/"><u>[Updated] Best Practices in Converting Videos for Twitter</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-primes-peak-performers-highest-tweets-and-viewing-numbers/"><u>[Updated] Prime’s Peak Performers  Highest Tweets & Viewing Numbers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-visual-vocabulary-complimentary-youtube-art-tools/"><u>[Updated] Visual Vocabulary  Complimentary YouTube Art Tools</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-mouse-properties-on-windows-11/"><u>10 Ways to Open Mouse Properties on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/11-fresh-features-in-windows-11-post-update-milestone/"><u>11 Fresh Features in Windows 11, Post-Update Milestone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-xiaomi-redmi-note-13-pro-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Xiaomi Redmi Note 13 Pro 5G Activity | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-how-to-embed-a-youtube-playlist-on-a-website/"><u>2024 Approved  How to Embed A YouTube Playlist On a Website</u></a></li>
<li><a href="https://win11.techidaily.com/6-simple-time-management-and-productivity-apps-for-windows/"><u>6 Simple Time Management and Productivity Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-methods-to-mend-your-obs-studio-connection-on-windows-pcs/"><u>7 Methods to Mend Your OBS Studio Connection on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-inaccessible-screen-resolution-settings-on-windows/"><u>8 Ways to Fix Inaccessible Screen Resolution Settings on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-accessing-windows-fix/"><u>A Comprehensible Guide to Accessing Windows Fix</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-quickly-opens-sticky-notes-in-windows-11/"><u>A Guide to Quickly Opens Sticky Notes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-windows-11-task-managers-search-functionality/"><u>Activate Windows 11 Task Manager's Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connection-dropouts-with-steam-remote/"><u>Addressing Connection Dropouts with Steam Remote</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-limited-usb-interface-on-pcs/"><u>Addressing Limited USB Interface on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inkpad-functionality-woes/"><u>Addressing Windows Inkpad Functionality Woes</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-ntfs-compression-in-win11-systems/"><u>Advanced Tips for NTFS Compression in Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/app-and-browser-domination-on-windows-os/"><u>App & Browser Domination on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/audio-enhancement-for-windows-step-by-step-driver-instructions/"><u>Audio Enhancement for Windows: Step-by-Step Driver Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-app-guard-features-with-graphical-upgrades-on-edge/"><u>Augmenting App Guard Features with Graphical Upgrades on Edge</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-strategies-keeping-epic-launcher-non-freezing/"><u>Avoidance Strategies: Keeping Epic Launcher Non-Freezing</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-hot-zone-tips-to-prevent-pc-overheating-during-games/"><u>Avoiding the Hot Zone: Tips to Prevent PC Overheating During Games</u></a></li>
<li><a href="https://win11.techidaily.com/baffling-taskers-display-with-edge-and-others/"><u>Baffling Tasker's Display with Edge & Others</u></a></li>
<li><a href="https://win11.techidaily.com/best-6-to-do-list-programs-tailored-for-windows-11-enthusiasts/"><u>Best 6 To-Do List Programs Tailored for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/boost-input-speed-learn-from-typingaid/"><u>Boost Input Speed: Learn From TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-visual-quality-enable-win11s-color-adjustment/"><u>Boosting Visual Quality: Enable Win11's Color Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-monitors-brightness-with-top-software-select/"><u>Boosting Windows Monitors' Brightness with Top Software Select</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-13-mini-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>Complete Fixes To Solve Apple iPhone 13 mini Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>Dose Life360 Notify Me When Someone Checks My Location On Apple iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-monetization-strategies-for-gamers/"><u>In 2024, Monetization Strategies for Gamers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-oppo-k11x-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Oppo K11x</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-motorola-moto-g14-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Motorola Moto G14 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/insert-soundtracks-for-dynamic-presentations-for-2024/"><u>Insert Soundtracks for Dynamic Presentations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719254078043-navigating-through-windows-issues-made-simple/"><u>Navigating Through Windows Issues Made Simple</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/premier-editing-software-for-vimeo-streams/"><u>Premier Editing Software for Vimeo Streams</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premier-seminar-title-inventor-suite/"><u>Premier Seminar Title Inventor Suite</u></a></li>
<li><a href="https://win11.techidaily.com/1719334307866-skip-wsl-save-time/"><u>Skip WSL, Save Time</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unraveling-the-code-behind-instagrams-video-glitch/"><u>Unraveling the Code Behind Instagram's Video Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/1719277126929-windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back</u></a></li>
<li><a href="https://win11.techidaily.com/1719320743244-windows-users-run-a-cost-free-locally-operated-gpt-model/"><u>Windows Users: Run a Cost-Free, Locally Operated GPT Model</u></a></li>
</ul></div>

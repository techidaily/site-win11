---
title: Hiding or Showing Windows 11'S Time and Date
date: 2024-08-15T23:48:38.932Z
updated: 2024-08-16T23:48:38.932Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hiding or Showing Windows 11'S Time and Date
excerpt: This Article Describes Hiding or Showing Windows 11'S Time and Date
keywords: Win11 Time Display,Hide Date in Win11,Win11 Date Visibility,Date/Time Change Win11,Windows Time Update,Show/Hide Win11 Date,Date & Time Settings Win11
thumbnail: https://thmb.techidaily.com/62017b9a75f2be738008dfd82e88e32736119212be885f48835d0be5b0d3459a.jpg
---

## Hiding or Showing Windows 11'S Time and Date

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
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
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://eaxpv-info.techidaily.com/new-harness-freedom-with-top-rated-android-editing-apps-for-2024/"><u>[New] Harness Freedom with Top-Rated Android Editing Apps for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-cultivate-classics-essential-farming-game-lists/"><u>[New] In 2024, Cultivate Classics  Essential Farming Game Lists</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-digital-companion-fb-stories-collector/"><u>[New] In 2024, Digital Companion - FB Stories Collector</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-visual-vocabulary-expansion-apps-for-crafting-text-on-images-for-2024/"><u>[New] Visual Vocabulary Expansion  Apps for Crafting Text on Images for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unlocking-creativity-top-10-insider-canva-tricks/"><u>[Updated] 2024 Approved  Unlocking Creativity  Top 10 Insider Canva Tricks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-earn-with-each-screen-capture/"><u>[Updated] In 2024, Earn With Each Screen Capture</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-approach-nullifying-onedrive-presence-on-explore/"><u>Efficient Approach: Nullifying OneDrive Presence on Explore</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-navigation-in-files-windows-11s-tab-system/"><u>Effortless Navigation in Files: Windows 11'S Tab System</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-coding-workflow-with-these-6-essential-chatgpt-add-ons-for-visual-studio-code/"><u>Elevate Your Coding Workflow with These 6 Essential ChatGPT Add-Ons for Visual Studio Code</u></a></li>
<li><a href="https://network-issues.techidaily.com/enabling-supported-mode-for-amd-freesync-monitor/"><u>Enabling Supported Mode for AMD FreeSync Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-real-time-performance-of-yuzu-emulator/"><u>Enhance Real-Time Performance of Yuzu Emulator</u></a></li>
<li><a href="https://extra-hints.techidaily.com/enhancing-film-aesthetics-with-luts-technology/"><u>Enhancing Film Aesthetics with Luts Technology</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-winning-video-coders-for-editing/"><u>Expert Tips: Winning Video Coders for Editing</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-itel-p55-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Itel P55 Pattern Lock Screen</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-apple-iphone-15-pro-easily-and-safely-drfone-by-drfone-virtual-ios/"><u>How to Change GPS Location on Apple iPhone 15 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-poco-c55-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Poco C55 Without Password | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Huawei Phone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/immersive-odyssey-the-most-exciting-psvr-games-on-the-way-for-2024/"><u>Immersive Odyssey  The Most Exciting PSVR Games on the Way for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-an-overview-of-youtube-short-content-basics/"><u>In 2024, An Overview of YouTube Short Content Basics</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-from-iphone-6-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even From iPhone 6 If Youve Tried Everything</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-v27-pro-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Vivo V27 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-the-account-lockout-threshold-post-failed-attempts-win-11/"><u>Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-systemtray-to-showcase-number-keys/"><u>Personalizing SystemTray to Showcase Number Keys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-opening-mouse-properties-in-win11/"><u>Quick and Easy: Opening Mouse Properties in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-missing-file-updates-on-windows-error-code-0x80070003/"><u>Quick Fix for Missing File Updates on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-error-262-in-roblox-games/"><u>Quick-Fix Strategies for Error 262 in Roblox Games</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-onedrive-access-issue-in-windows-os-quickly/"><u>Resolve OneDrive Access Issue in Windows OS Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-windows-camera-loss-of-media/"><u>Strategies to Combat Windows Camera Loss of Media</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-failed-task-execution-in-windows-with-error-0x8007000f/"><u>Tackling Failed Task Execution in Windows with Error 0X8007000f</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-shortcuts-for-rapid-insertion-of-pre-defined-text-snippets/"><u>Tailored Shortcuts for Rapid Insertion of Pre-Defined Text Snippets</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-for-resolving-widespread-rainmeter-challenges/"><u>The Ultimate Guide for Resolving Widespread Rainmeter Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/transform-data-handling-visual-analyzer-for-disk-storage-on-windows/"><u>Transform Data Handling: Visual Analyzer for Disk Storage on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-dealing-with-unyielding-power-controls-in-windows-11/"><u>Tricks for Dealing with Unyielding Power Controls in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11-sefx-archive-techniques/"><u>Unlocking Win11 SEFx Archive Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/visualizing-data-footprint-in-windows-os/"><u>Visualizing Data Footprint in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-control-panel-customizing-made-simple/"><u>Win11's Control Panel: Customizing Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10s-best-encryption-software-compared-153-chars/"><u>Windows 10'S Best Encryption Software, Compared (153 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-explore-these-8-great-video-editors/"><u>Windows Users, Explore These 8 Great Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/your-way-your-window-customize-windows-11-today/"><u>Your Way, Your Window: Customize Windows 11 Today</u></a></li>
</ul></div>

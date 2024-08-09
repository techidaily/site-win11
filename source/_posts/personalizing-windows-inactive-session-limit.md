---
title: Personalizing Windows Inactive Session Limit
date: 2024-08-08T13:23:15.641Z
updated: 2024-08-09T13:23:15.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalizing Windows Inactive Session Limit
excerpt: This Article Describes Personalizing Windows Inactive Session Limit
keywords: Customize Active Time,Session Lifetime Control,Personal Window Limits,Tailored Session Timer,Individual Sync Pause,User Activity Hours,Dynamic Login Periods
thumbnail: https://thmb.techidaily.com/bcb4dab5fca23c5552c696b1f9621ccec9d5240a378ece9f04f489b258c09834.jpg
---

## Personalizing Windows Inactive Session Limit

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-top-choice-for-fb-vids-mp4-download-toolkit/"><u>[New] 2024 Approved  Top Choice for FB Vids – MP4 Download Toolkit</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-exclusive-guide-to-priceless-cam-screen-recorders/"><u>[New] In 2024, Exclusive Guide to Priceless Cam Screen Recorders</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-who-are-tiktoks-most-influential-gaming-bloggers/"><u>[New] Who Are TikTok’s Most Influential Gaming Bloggers?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-scrutinizing-the-functionality-of-pixelrecorder-12/"><u>[Updated] 2024 Approved  Scrutinizing the Functionality of PixelRecorder 12</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-which-is-the-ultimate-ios-video-editor-cameo-vs-filmorago-for-2024/"><u>[Updated] Which Is the Ultimate iOS Video Editor? Cameo Vs. FilmoraGo for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-high-def-mastery-the-leading-blu-ray-devs/"><u>2024 Approved  High-Def Mastery  The Leading Blu-Ray Devs</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://games-able.techidaily.com/asuss-visionary-docking-stations-the-premier-rog-ally-models-of-2024/"><u>Asus's Visionary Docking Stations - The Premier RoG Ally Models of 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-accessing-the-fax-editor-in-win11/"><u>Essential Tips: Accessing the Fax Editor in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-11-tackling-lag-and-delay/"><u>Fast-Track Windows 11: Tackling Lag and Delay</u></a></li>
<li><a href="https://win11.techidaily.com/1719334729837-fix-unusable-compatibility-center-on-vista7-pcs-fast/"><u>Fix Unusable Compatibility Center on Vista/7 PCs Fast</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-printer-on-windows-11-step-by-step/"><u>Fixing Your Printer on Windows 11: Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-from-iphone-6-without-password-by-drfone-ios/"><u>How to Delete iCloud Account From iPhone 6 without Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-signing-you-in-with-a-temporary-profile/"><u>How to Fix Windows Signing You In With a Temporary Profile</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-vivo-y02t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-xiaomi-13t-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Xiaomi 13T to iPod | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/humor-and-heartbreak-the-vhs-story-of-goofy-movie/"><u>Humor and Heartbreak  The VHS Story of Goofy Movie</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-your-infinix-hot-40i-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Infinix Hot 40i Lock Screen Password</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-a15-5g-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transformative-video-creation-harness-the-trio-of-windows-photos-and-storyremix/"><u>In 2024, Transformative Video Creation  Harness the Trio of Windows, Photos, and StoryRemix</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-running-intel-unison-correctly-in-windows-11/"><u>Mastering the Art of Running Intel Unison Correctly in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/moment-update-windows-11-unpacks-future-looking-features/"><u>Moment Update: Windows 11 Unpacks Future-Looking Features</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-tray-interface-with-numeric-and-caps-indicators/"><u>Personalize Tray Interface with Numeric and Caps Indicators</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-original-directory-display-preferences/"><u>Regaining Original Directory Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-windows-update-error-code-0xc1900101/"><u>Swift Resolution to Windows Update Error Code 0xC1900101</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-best-ways-to-convert-mp4-videos-to-mp3-audio-files/"><u>Updated 2024 Approved Best Ways to Convert MP4 Videos to MP3 Audio Files</u></a></li>
</ul></div>

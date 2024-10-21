---
title: Personalizing Taskbar Time Displays in Win 11
date: 2024-10-20T03:39:04.704Z
updated: 2024-10-21T06:19:52.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Personalizing Taskbar Time Displays in Win 11
excerpt: This Article Describes Personalizing Taskbar Time Displays in Win 11
keywords: Win11 Time Customization,Taskbar Timing Personalize,Windows Time Displayer,PC Time Bar Layout,Win11 Timer Settings,Taskbar Hour Change,Date & Time Formatter
thumbnail: https://thmb.techidaily.com/104fcc0c1e7ba0020bac11684b73c47c97661f3e4742e08d1374a286a48bed4c.jpg
---

## Personalizing Taskbar Time Displays in Win 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/effortlessly-enhanced-images-learn-the-insider-snapchat-tactics-for-2024/"><u>Effortlessly Enhanced Images Learn the Insider Snapchat Tactics for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-v27e-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo V27e Quickly | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-tick-tock-sync-your-clock/"><u>Fixing Windows' Tick-Tock: Sync Your Clock</u></a></li>
<li><a href="https://win11.techidaily.com/frame-perfecting-eliminating-lags-with-these-9-windows-strategies/"><u>Frame Perfecting: Eliminating Lags with These 9 Windows Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-switch-off-cortana-functionality/"><u>Guide to Switch Off Cortana Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-xbox-app-update-failures/"><u>How to Correct Xbox App Update Failures</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-xiaomi-redmi-note-12-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Xiaomi Redmi Note 12 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-windows-defender-error-0x80004004-instantly/"><u>How to Solve Windows Defender Error 0X80004004 Instantly</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigating-the-world-of-electronics-tips-from-toms-hardware-hub/"><u>Navigating the World of Electronics: Tips From Tom's Hardware Hub</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-file-navigation-on-windows-implementing-movecopy-actions/"><u>Optimizing File Navigation on Windows: Implementing 'Move'/'Copy' Actions</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/recuperacion-de-datos-tras-un-formateo-accidental-del-disco-duro-externo-seagate/"><u>Recuperación De Datos Tras Un Formateo Accidental Del Disco Duro Externo Seagate</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hidden-wi-fi-in-the-realm-of-windows-11/"><u>Resurrecting Hidden Wi-Fi in the Realm of Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-critical-take-on-sharex-expert-evaluations-and-alternates/"><u>The Critical Take on ShareX Expert Evaluations & Alternates</u></a></li>
<li><a href="https://facebook.techidaily.com/the-ideal-time-frame-for-fb-campaigns/"><u>The Ideal Time Frame for Fb Campaigns</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-picks-in-depth-review-of-best-macos-screenshot-apps-for-2024/"><u>Top Picks In-Depth Review of Best macOS Screenshot Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turning-off-google-chrome-alerts-windows-edition/"><u>Turning Off Google Chrome Alerts, Windows Edition</u></a></li>
</ul></div>


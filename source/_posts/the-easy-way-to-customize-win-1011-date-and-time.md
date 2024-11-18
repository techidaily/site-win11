---
title: The Easy Way to Customize Win 10/11 Date & Time
date: 2024-11-11T00:46:54.484Z
updated: 2024-11-18T09:03:25.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Easy Way to Customize Win 10/11 Date & Time
excerpt: This Article Describes The Easy Way to Customize Win 10/11 Date & Time
keywords: Win 10 Setup,Win 11 Personalization,Windows Date Change,Adjust Windows Time,Customize OS Dates,Time Settings Update,Personalized Windows
thumbnail: https://thmb.techidaily.com/3f74865abe3cde83f5178213b8f2028e6688a23ca37959ec467d0c79369ad79b.jpg
---

## The Easy Way to Customize Win 10/11 Date & Time

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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
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
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

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
<li><a href="https://some-techniques.techidaily.com/new-guidelines-for-selecting-an-engaging-movie-trailer-song/"><u>[New] Guidelines for Selecting an Engaging Movie Trailer Song</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflicting-apps-camera-use-windows-error-0xa00f4243/"><u>Addressing Conflicting Apps' Camera Use: Windows Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-revamp-for-windows-11-status-area-include-a-chosen-weather-symbol/"><u>Aesthetic Revamp for Windows 11 Status Area: Include a Chosen Weather Symbol</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-you-trust-chatgpt-to-check-your-writing-errors/"><u>Can You Trust ChatGPT to Check Your Writing Errors?</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-jamboree-discovering-5-entertaining-techniques/"><u>Command Prompt Jamboree: Discovering 5 Entertaining Techniques</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-the-implications-of-apples-tandem-oled-screen-on-upcoming-tablet-displays-insights/"><u>Exploring the Implications of Apple's Tandem OLED Screen on Upcoming Tablet Displays - Insights</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-lava-blaze-2-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Lava Blaze 2</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-honor-x50iplus-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Honor X50i+</u></a></li>
<li><a href="https://games-able.techidaily.com/prepare-for-fun-dive-into-chatgpts-favorite-6-games/"><u>Prepare For Fun: Dive Into ChatGPT’s Favorite 6 Games</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/request-for-full-media-sharing-viewability-via-messaging-platforms/"><u>Request for Full Media Sharing Viewability via Messaging Platforms</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-troubleshooting-how-to-handle-wininetdll-errors-effectively/"><u>Step-by-Step Troubleshooting: How to Handle Wininet.dll Errors Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-audio-configuration-for-spatiality/"><u>Windows 11 Audio Configuration for Spatiality</u></a></li>
</ul></div>


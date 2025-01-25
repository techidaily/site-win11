---
title: Hiding or Showing Time & Date on Win 11 UI Bar
date: 2025-01-23T06:26:10.447Z
updated: 2025-01-25T09:12:55.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hiding or Showing Time & Date on Win 11 UI Bar
excerpt: This Article Describes Hiding or Showing Time & Date on Win 11 UI Bar
keywords: Win 11 UI Date Display,Windows 11 Timebar Adjust,Hide TimeBar Windows 11,Set Windows 11 Clock View,Customize Win 11 DateTime,Windows Bar Time Control,Update Win 11 TimeDisplay
thumbnail: https://thmb.techidaily.com/718d1853d85918e9d3b7531d3e7e5d446b8b2d7ecc9512a603cf6d88a4e79188.jpg
---

## Hiding or Showing Time & Date on Win 11 UI Bar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-knowledge.techidaily.com/updated-fast-and-easy-photovideo-exchange-between-ios-gear/"><u>[Updated] Fast & Easy Photo/Video Exchange Between iOS Gear</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-chromes-glitch-enabling-flawless-filesync-on-windows/"><u>Bypass Chrome’s Glitch: Enabling Flawless Filesync on Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/capturing-the-skies-an-in-depth-look-at-the-cutting-edge-dji-mavic-3-technology/"><u>Capturing the Skies: An In-Depth Look at the Cutting-Edge DJI Mavic 3 Technology</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-your-cortana-story-in-windows-files/"><u>Capturing Your Cortana Story in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-your-preferred-package-manager-for-windows-devices/"><u>Choosing Your Preferred Package Manager for Window's Devices</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-and-resolving-the-mystery-of-error-0x8007251d-in-windows/"><u>Clarifying and Resolving the Mystery of Error 0X8007251d in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-ui-redesign-for-file-explorer-in-w11/"><u>Classic UI Redesign for File Explorer in W11</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-reset-user-permissions-to-basics-in-windows-11/"><u>Clean Slate: Reset User Permissions to Basics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-windows-bluetooth-connectivity-issues/"><u>Clearing Up Windows Bluetooth Connectivity Issues</u></a></li>
<li><a href="https://win-webster.techidaily.com/configure-your-pcs-static-ip-with-ease-expert-advice-by-yl-software-solutions/"><u>Configure Your PC's Static IP with Ease - Expert Advice by YL Software Solutions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-correcting-errors-in-the-interaction-of-chatgpt-with-plugin-services/"><u>Guide: Correcting Errors in the Interaction of ChatGPT with Plugin Services</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-t-mobile-apple-iphone-11-pro-max-online-without-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock T-Mobile Apple iPhone 11 Pro Max online without SIM Card?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/triple-tactic-for-tracking-youtube-income-a-step-by-step-approach-for-2024/"><u>Triple Tactic for Tracking YouTube Income A Step-by-Step Approach for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-connections-enhanced-ethernet-for-gamers/"><u>Ultimate Connections: Enhanced Ethernet For Gamers</u></a></li>
<li><a href="https://win-workspace.techidaily.com/44ov44o844kv44ov44kp44or44oa44gu6ieq5yuv5zcm5pyf5pa55rovic0g44k544og44od44ox44oq44kk44k544og44od44ox44ks44kk44oj/"><u>ワークフォルダの自動同期方法 - ステップバイステップガイド</u></a></li>
</ul></div>


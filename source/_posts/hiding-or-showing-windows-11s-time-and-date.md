---
title: Hiding or Showing Windows 11'S Time and Date
date: 2024-07-13T10:46:28.616Z
updated: 2024-07-14T10:46:28.616Z
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
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

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
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://win11.techidaily.com/8-microsoft-apps-you-must-install-on-android-if-you-have-a-windows-pc/"><u>8 Microsoft Apps You Must Install on Android if You Have a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-11-arm-installation-via-iso-download/"><u>Seamless Windows 11 ARM Installation via ISO Download</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlock-a-million-eyes-engaging-content-strategy/"><u>Unlock a Million Eyes  Engaging Content Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-ceasing-wired-pc-keyboard-on-windows/"><u>Tutorial: Ceasing Wired PC Keyboard on Windows</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-navigating-nearby-areas-for-an-immersive-roblox-experience/"><u>[New] In 2024, Navigating Nearby Areas for an Immersive Roblox Experience</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-menu-unlocking-ancestral-functions/"><u>Windows 11'S Menu: Unlocking Ancestral Functions</u></a></li>
<li><a href="https://win11.techidaily.com/secure-app-locations-in-windows-task-management/"><u>Secure App Locations in Windows Task Management</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-interactive-stories-in-real-time-with-fb-screen-features/"><u>[Updated] In 2024, Interactive Stories in Real-Time with FB Screen Features</u></a></li>
<li><a href="https://win11.techidaily.com/system-fixes-for-error-0x800700e1-in-windows-11/"><u>System Fixes for Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-auto-clickers-with-hotkeys-for-windows/"><u>The 5 Best Auto Clickers With Hotkeys for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/trick-to-invoke-admin-level-powershell-on-your-win11-pc/"><u>Trick to Invoke Admin-Level PowerShell on Your Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/1719374785731-unlock-additional-space-on-your-windows-system-for-free/"><u>Unlock Additional Space on Your Windows System, For Free!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/excellence-in-efficiency-top-5-chromes-for-vids-from-fb-for-2024/"><u>Excellence in Efficiency  Top 5 Chromes for Vids From FB for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/closing-chapter-on-instagram-how-to-discard-account-permanently-for-2024/"><u>Closing Chapter on Instagram  How to Discard Account Permanently for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-solutions-for-stuck-pin-locks-on-windows/"><u>10 Solutions for Stuck PIN Locks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-unlock-windows-defense-against-admins-choice/"><u>Techniques to Unlock Windows Defense Against Admins' Choice</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-display-management-in-windows-11/"><u>Understanding Display Management in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-satire-software-studio/"><u>[Updated] Satire Software Studio</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlock-your-youtube-personality-top-6-creator-categories/"><u>[Updated] Unlock Your YouTube Personality  Top 6 Creator Categories</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-detailed-breakdown-of-camstudio-screencapture-pro-for-2024/"><u>[Updated] Detailed Breakdown of CamStudio ScreenCapture Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/switching-notepad-to-dark-mode-on-windows-11plus/"><u>Switching Notepad to Dark Mode on Windows 11+</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-audience-captivation-technique-how-to-personalize-your-speech-with-audacitys-vocal-effects/"><u>New 2024 Approved Audience Captivation Technique How to Personalize Your Speech with Audacitys Vocal Effects</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-null-space-in-your-system-drive/"><u>Step-by-Step Guide: Removing Null Space in Your System Drive</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-from-basics-to-advanced-crafting-powerful-instagram-hashtags/"><u>[Updated] In 2024, From Basics to Advanced  Crafting Powerful Instagram Hashtags</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-e84-glitches-on-windows-systems/"><u>Overcoming Steam E84 Glitches on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-tackle-zeroxc000003e-application-errors-in-win1011/"><u>Strategies to Tackle ZeroXc000003e Application Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-financial-backbone-of-microsofts-windows-11/"><u>The Financial Backbone of Microsoft's Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elite-streaming-sensations-worlds-most-popular-video-content-makers/"><u>2024 Approved  Elite Streaming Sensations  World's Most Popular Video Content Makers</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-way-for-printer-use-by-one-pc-only/"><u>Clearing the Way for Printer Use by One PC Only</u></a></li>
<li><a href="https://driver-install.techidaily.com/speed-up-your-pc-with-gb-mb-software/"><u>Speed Up Your PC With GB MB Software</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-immersive-surround-sound-incorporating-atmos-into-win-1011/"><u>Achieve Immersive Surround Sound: Incorporating Atmos Into Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-booster-issues-windows-repair-guide/"><u>Skyrim Booster Issues: Windows Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-void-recovering-startups-on-windows/"><u>Bridging the Void: Recovering Startups on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-interruptions-during-steam-video-streaming/"><u>Preventing Interruptions During Steam Video Streaming</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-gain-momentum-with-these-strategies-for-trending-youtubers/"><u>[Updated] Gain Momentum with These Strategies for Trending YouTubers</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-mac-users-install-lumafusion-or-find-equivalent-video-editors/"><u>In 2024, Mac Users Install Lumafusion or Find Equivalent Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-nonexistent-devices-in-os-windows-1011/"><u>Overcoming Erroneous Nonexistent Devices in OS: Windows 10/11</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-meizu-21-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-premiere-pro-slow-playback-issues-finding-the-best-solutions/"><u>Updated In 2024, Premiere Pro Slow Playback Issues Finding The Best Solutions</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unlocking-slow-motion-magic-in-instagram-reels/"><u>2024 Approved  Unlocking Slow Motion Magic in Instagram Reels</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagrams-filter-arsenal-for-revamping-your-archive-for-2024/"><u>[Updated] Instagram's Filter Arsenal for Revamping Your Archive for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restart-windows-paper-processor/"><u>Restart Windows' Paper Processor</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-playable-media-error-xc10100bf/"><u>Overcoming Non-Playable Media Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-settings-error-in-nvidias-geforce-app-windows-11/"><u>Steps to Overcome 'Settings Error' In NVIDIA's GeForce App (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-0x0001-in-windows-1011-environment/"><u>Addressing GeForce 0X0001 in Windows 10/11 Environment</u></a></li>
</ul></div>

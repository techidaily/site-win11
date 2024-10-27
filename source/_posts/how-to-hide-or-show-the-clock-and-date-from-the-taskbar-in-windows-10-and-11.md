---
title: How to Hide or Show the Clock and Date From the Taskbar in Windows 10 and 11
date: 2024-10-25T22:24:13.821Z
updated: 2024-10-27T07:15:10.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Hide or Show the Clock and Date From the Taskbar in Windows 10 and 11
excerpt: This Article Describes How to Hide or Show the Clock and Date From the Taskbar in Windows 10 and 11
keywords: Hide Clock Window,Show Date Bar,Taskbar Time Control,Manage Windows Time,Disable DateTime,Set Taskbar Info,Adjust Clock Display
thumbnail: https://thmb.techidaily.com/5ef4b9be2cc03e1f5bba8134aa6b00b2355f4bf8946df71748d869f7b05769b2.jpg
---

## How to Hide or Show the Clock and Date From the Taskbar in Windows 10 and 11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2049364/7443" target="_top" id="2049364">
  <img src="//a.impactradius-go.com/display-ad/7443-2049364" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049364/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-obs-full-screen-no-more-problem/"><u>[New] In 2024, Obs Full-Screen No More Problem</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-techniques-for-live-broadcasting-recorded-videographies-on-fb-for-2024/"><u>[New] Techniques for Live Broadcasting Recorded Videographies on FB for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-improve-your-videography-the-itunes-way/"><u>[Updated] Improve Your Videography The iTunes Way</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-bland-to-breatited-the-ultimate-video-title-guide/"><u>2024 Approved From Bland to Breatited The Ultimate Video Title Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-turning-on-windows-11s-high-dynamic-range-mode/"><u>2024 Approved Step-by-Step Turning On Windows 11'S High Dynamic Range Mode</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-heimvision-sunrise-alarm-clock-model-a8n-brighten-your-mornings-with-gentle-light-therapy/"><u>Comprehensive HeimVision Sunrise Alarm Clock Model A8n - Brighten Your Mornings with Gentle Light Therapy</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-common-windows-11-troubles-quickly/"><u>Conquering Common WINDOWS 11 Troubles Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/curb-the-vibrant-contrast-in-windows-os/"><u>Curb the Vibrant Contrast in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-bluescreenview-functions/"><u>Demystifying BlueScreenView Functions</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/detailed-official-winxvideo-ai-features-and-technical-specifications/"><u>Detailed Official WinXVideo AI Features and Technical Specifications</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11-help-application-crash/"><u>Fixing Windows 11 Help Application Crash</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-disconnected-windows-printers/"><u>Methods To Revive Disconnected Windows Printers</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-windows-11-interface-accessible-tabs/"><u>Navigating the Windows 11 Interface: Accessible Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-with-the-help-of-alomware-toolbox/"><u>Optimizing Windows with the Help of AlomWare Toolbox</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-email-issue-0x800713f-fix-guide/"><u>Overcoming Windows Email Issue: 0X800713F Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-tasks-with-bar-tools-in-mspcm-for-w11/"><u>Perfecting Tasks with Bar Tools in MSPCM for W11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/slash-length-amplify-impact-youtube-video-editing-for-2024/"><u>Slash Length, Amplify Impact YouTube Video Editing for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/smooth-media-transfer-twitvideos-to-whatsapp-guide-for-2024/"><u>Smooth Media Transfer TwitVideos to WhatsApp Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-brightening-your-windows-11-cursor/"><u>Step-by-Step: Brightening Your Windows 11 Cursor</u></a></li>
</ul></div>


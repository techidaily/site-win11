---
title: Time Customization in Windows Desktop Toolbars
date: 2024-10-19T19:54:04.332Z
updated: 2024-10-27T04:53:09.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Time Customization in Windows Desktop Toolbars
excerpt: This Article Describes Time Customization in Windows Desktop Toolbars
keywords: Time Bar Customize Windows,Desktop Toolbar Time Controls,Adjust Time Display Windows,Personalize Window Timer,Time Settings Windows Desktoppl,Set Custom Time WindowsBar,Change Time In WindowsToolbars
thumbnail: https://thmb.techidaily.com/f78a12d6fa260b60593d7d84df0572fbc03e543ca8c86ab396fe09af56299ebf.jpg
---

## Time Customization in Windows Desktop Toolbars

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-audiences-choice-in-drama-writings-for-2024/"><u>[New] Audience's Choice in Drama Writings for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-electoral-enthusiasm-top-5-political-game-experiences-for-2024/"><u>[New] Electoral Enthusiasm Top 5 Political Game Experiences for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-c-span-content-for-the-bold-freewatcher/"><u>2024 Approved C-Span Content for the Bold Freewatcher</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/advancing-smart-multimodal-transit-solutions-the-insights-from-abbyys-perspective/"><u>Advancing Smart Multimodal Transit Solutions - The Insights From ABBYY's Perspective</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581197529-be-a-polyglot-in-minutes-enjoy-a-staggering-95-savings/"><u>Be a Polyglot in Minutes - Enjoy a Staggering 95% Savings</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/beginning-with-the-meta-headset-how-to-set-up-an-oculus-questquest-2-profile/"><u>Beginning with the Meta Headset: How to Set Up an Oculus Quest/Quest 2 Profile</u></a></li>
<li><a href="https://blog-min.techidaily.com/enhance-your-livestreams-discover-the-power-of-manycams-video-editing-suite-and-digital-webcams/"><u>Enhance Your Livestreams: Discover the Power of ManyCam's Video Editing Suite and Digital Webcams</u></a></li>
<li><a href="https://fox-direct.techidaily.com/final-flair-free-and-paid-templates-to-express-thanks-for-2024/"><u>Final Flair Free & Paid Templates to Express Thanks for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/gopros-top-5-subaquatic-filter-choices/"><u>GoPro's Top 5 Subaquatic Filter Choices</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-legacy-keyboard-triggers-for-narrator/"><u>Mastering Legacy Keyboard Triggers for Narrator</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-settings-transfer-guide-for-new-users/"><u>PowerToys Settings Transfer Guide for New Users</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-recovery-from-crushing-windows-c0000022-error/"><u>Steps to Recovery From Crushing Window's C0000022 Error</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-grouping-files-into-windows-11-directories/"><u>The Ultimate Guide to Grouping Files Into Windows 11 Directories</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-unblocking-screen-settings-on-pcs/"><u>The Ultimate Guide to Unblocking Screen Settings on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-google-chromes-colors-in-windows/"><u>Unlocking Google Chrome's Colors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/visual-clarity-and-efficiency-in-notetaking-via-obsidian-framework/"><u>Visual Clarity and Efficiency in Notetaking via Obsidian Framework</u></a></li>
</ul></div>


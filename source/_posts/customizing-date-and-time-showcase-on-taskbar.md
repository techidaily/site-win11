---
title: Customizing Date and Time Showcase on Taskbar
date: 2024-09-30T19:35:57.204Z
updated: 2024-10-03T19:37:23.472Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Date and Time Showcase on Taskbar
excerpt: This Article Describes Customizing Date and Time Showcase on Taskbar
keywords: DateBar Customization,TimeTaskbar Personalize,Taskbar Display Dates,Onscreen Clock Adjust,Dynamic DateTime Bar,ScheduleShowcase Widget,TimeConfigure Controls
thumbnail: https://thmb.techidaily.com/8f5cadb41c029899508ca6efd6723f50f45c76c5999800100c8f4f1fd518b7be.jpg
---

## Customizing Date and Time Showcase on Taskbar

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
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-expert-review-of-the-leading-no-cost-cam-software-options-for-2024/"><u>[New] Expert Review of the Leading No-Cost Cam Software Options for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-step-by-step-guide-to-perfect-voice-recording/"><u>[Updated] A Step-by-Step Guide to Perfect Voice Recording</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-game-hall-fame-celebrating-top-10-action-adventure-favorites-for-2024/"><u>[Updated] Game Hall Fame Celebrating Top 10 Action-Adventure Favorites for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-revisiting-youtubes-archive-two-proven-watch-strategies/"><u>[Updated] In 2024, Revisiting Youtube's Archive Two Proven Watch Strategies</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/a-guide-to-the-top-12-most-captivating-pc-clickers-for-2024/"><u>A Guide to the Top 12 Most Captivating PC Clickers for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-review-of-nokia-31-your-gateway-to-modern-communication/"><u>Expert Review of Nokia 3.1 - Your Gateway to Modern Communication</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-browser-blockage-by-windows-firewall-for-chrome-usage/"><u>Fixing Browser Blockage by Windows Firewall for Chrome Usage</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-new-mail-notifications/"><u>Fixing Unresponsive New Mail Notifications</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-motorola-razr-40-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Motorola Razr 40 Bootloader Easily</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-full-network-connectivity-on-windows/"><u>Regaining Full Network Connectivity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/separate-your-onedrive-and-microsoft-account-on-pc/"><u>Separate Your OneDrive & Microsoft Account on PC</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-resolving-windows-update-error-0x80070003/"><u>Taming the Beast: Resolving Windows Update Error 0X80070003</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10-basics-first-steps-in-enhancing-access/"><u>Windows 10 Basics: First Steps in Enhancing Access</u></a></li>
</ul></div>


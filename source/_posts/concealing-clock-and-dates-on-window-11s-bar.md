---
title: Concealing Clock & Dates on Window 11'S Bar
date: 2024-10-20T06:00:35.340Z
updated: 2024-10-27T00:43:31.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Concealing Clock & Dates on Window 11'S Bar
excerpt: This Article Describes Concealing Clock & Dates on Window 11'S Bar
keywords: Hide Windows Clocks,Datebar Blindness,Windows 11 Timecloak,Eliminate Dates in Win Bar,Mask Win11 Date Display,Clock & Date Hiding Win 11,Conceal Timebar Win 11
thumbnail: https://thmb.techidaily.com/daf5ba2a8491ccb029544c33871dfddf8c00a96e763bab0af0faf409f9f29c9c.jpg
---

## Concealing Clock & Dates on Window 11'S Bar

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
<a href="https://aligracehair.sjv.io/c/5597632/1934254/19272" target="_top" id="1934254">
  <img src="//a.impactradius-go.com/display-ad/19272-1934254" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934254/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-prime-10-live-streaming-networks-revealed-and-compared/"><u>[New] Prime 10 Live Streaming Networks Revealed and Compared</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-novices-path-to-effective-telegram-advertising/"><u>[Updated] The Novice’s Path to Effective Telegram Advertising</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-blueprint-for-social-success-six-proven-steps-toward-verification-and-growth/"><u>2024 Approved The Blueprint for Social Success Six Proven Steps Toward Verification and Growth</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/best-free-video-editors-for-windows-10-users/"><u>Best Free Video Editors for Windows 10 Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-edge-40-neo-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Edge 40 Neo.</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-apples-new-vision-pro-spatial-persona-features-a-detailed-guide/"><u>Discover Apple's New Vision Pro Spatial Persona Features - A Detailed Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-window-11-security-context-menu-filter-integration/"><u>Enhancing Window 11 Security: Context Menu Filter Integration</u></a></li>
<li><a href="https://win11.techidaily.com/handling-common-internal-networking-errors-in-win-1011/"><u>Handling Common Internal Networking Errors in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-fix-guide-overcoming-workspace-malfunctions-in-windows-os/"><u>Immediate Fix Guide: Overcoming Workspace Malfunctions in Windows OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/instagram-tips-uploading-and-sharing-youtube-content/"><u>Instagram Tips Uploading & Sharing YouTube Content</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-finding-lost-files-on-pc/"><u>Mastering the Art of Finding Lost Files on PC</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/optimized-with-advanced-web-tracker-technology/"><u>Optimized with Advanced Web Tracker Technology</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-updating-your-dells-speaker-software-online/"><u>Step-by-Step Guide: Updating Your Dell's Speaker Software Online</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-for-effortless-installation-of-msixbundle-and-appx-packages/"><u>Ultimate Guide for Effortless Installation of MSixbundle & Appx Packages</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-locating-windows-component-services-tool/"><u>Understanding & Locating Windows Component Services Tool</u></a></li>
</ul></div>


---
title: Conceal or Reveal the Taskbar's Time Display
date: 2024-10-10T17:56:34.165Z
updated: 2024-10-15T19:13:48.721Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Conceal or Reveal the Taskbar's Time Display
excerpt: This Article Describes Conceal or Reveal the Taskbar's Time Display
keywords: Hide Taskbar Clock,Show Taskbar Time,Disable Time Bar,Enable Clock Visibility,Taskbar Timer Control,Manage Time Display,Adjust Taskbar Clock
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## Conceal or Reveal the Taskbar's Time Display

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
<a href="https://appsumo.8odi.net/c/5597632/2049363/7443" target="_top" id="2049363">
  <img src="//a.impactradius-go.com/display-ad/7443-2049363" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049363/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557742/17382" target="_top" id="1557742">
  <img src="//a.impactradius-go.com/display-ad/17382-1557742" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557742/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
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

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unleash-creativity-in-snaps-15-innovative-posting-techniques/"><u>[New] In 2024, Unleash Creativity in Snaps 15 Innovative Posting Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-master-your-screen-time-top-10-in-depth-guide-to-excellent-offline-ios-gaming-for-2024/"><u>[Updated] Master Your Screen Time - Top 10 In-Depth Guide to Excellent Offline iOS Gaming for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-unlocking-the-power-of-blur-in-virtual-meetings/"><u>2024 Approved Unlocking the Power of Blur in Virtual Meetings</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-fatal-javascript-issue-in-discord-on-w10w11-pcs/"><u>Eliminating Fatal Javascript Issue in Discord on W10/W11 PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/enhancing-visual-storytelling-with-impeccable-voice-over/"><u>Enhancing Visual Storytelling with Impeccable Voice Over</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-game-latency-problems-on-the-naraka-bladepoint-platform/"><u>Fixing Game Latency Problems on the Naraka Bladepoint Platform</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-e-book-sources-a-comprehensive-guide-for-filling-your-kobo-library/"><u>Free E-Book Sources: A Comprehensive Guide for Filling Your Kobo Library</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-tecno-camon-20-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-realme-c55-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Realme C55</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-disable-windows-11s-hyper-v-feature/"><u>Quick Guide: Disable Windows 11'S Hyper-V Feature</u></a></li>
<li><a href="https://win11.techidaily.com/solving-access-denied-issues-in-windows-11-a-top-5-approach/"><u>Solving Access Denied Issues in Windows 11: A Top 5 Approach</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-locating-your-gpu-model-on-windows-11/"><u>Speed Up: Locating Your GPU Model on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steadfast-safety-quick-fixed-strategies-for-family-protection/"><u>Steadfast Safety: Quick Fixed Strategies for Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-utilizing-github-desktop-in-windows/"><u>Step-By-Step Guide to Utilizing GitHub Desktop in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charge-your-pcs-readying-with-win11-speed-fixes/"><u>Turbo Charge Your PC’s Readying with Win11 Speed Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Vivo X90S | Dr.fone</u></a></li>
</ul></div>


---
title: Hide Time, Show Dates - Taskbar Settings Insight
date: 2024-10-14T21:06:19.342Z
updated: 2024-10-15T18:34:25.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hide Time, Show Dates - Taskbar Settings Insight
excerpt: This Article Describes Hide Time, Show Dates - Taskbar Settings Insight
keywords: Hide Date Bar,Date Display Controls,Taskbar Date Adjustment,Change Taskbar Layout,Remove Date Indicator,Customize TimeBar,Modify Windows Dates
thumbnail: https://thmb.techidaily.com/0c63aae4422094d29361ca7d174981f6a34db77ad2868353babe77ecee3079bf.jpg
---

## Hide Time, Show Dates - Taskbar Settings Insight

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
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/n-2024-easy-and-fast-convert-youtube-music-into-mp3-mac-version/"><u>[New] In 2024, Easy & Fast Convert YouTube Music Into MP3, Mac Version</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-sharing-the-spotlight-involving-viewers-in-your-journey/"><u>[New] In 2024, Sharing the Spotlight Involving Viewers in Your Journey</u></a></li>
<li><a href="https://fox-links.techidaily.com/capturing-the-future-an-overview-of-iphone-xs-camera-innovations/"><u>Capturing the Future An Overview of iPhone X's Camera Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-connectivity-with-telnet-ways-3/"><u>Enhance Windows Connectivity with Telnet (Ways 3)</u></a></li>
<li><a href="https://win11.techidaily.com/essential-to-do-list-software-for-windows-users/"><u>Essential To-Do List Software for Windows Users</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-for-picking-out-every-message-in-your-gmail-inbox-instantly/"><u>Expert Tips for Picking Out Every Message in Your Gmail Inbox Instantly</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-lava-storm-5g-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Lava Storm 5G Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-honor-magic-6-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Honor Magic 6 Phone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-file-isnt-playable-error-0xc10100bf-in-windows/"><u>How to Fix the This File Isn’t Playable Error 0Xc10100bf in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-11-expert-tactics-for-dominating-fb-video-marketing/"><u>In 2024, 11 Expert Tactics for Dominating FB Video Marketing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-unleashing-creativity-in-education-making-amazing-videography-a-reality-on-youtube/"><u>In 2024, Unleashing Creativity in Education Making Amazing Videography a Reality on YouTube</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/navigating-facebooks-video-evolution-for-2024/"><u>Navigating Facebook’s Video Evolution for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-x7217-at-microsoft-store/"><u>Troubleshooting Error Code X7217 at Microsoft Store</u></a></li>
</ul></div>


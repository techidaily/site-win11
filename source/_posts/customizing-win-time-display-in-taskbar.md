---
title: Customizing Win Time Display in Taskbar
date: 2024-09-30T17:01:43.669Z
updated: 2024-10-04T03:31:42.052Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Win Time Display in Taskbar
excerpt: This Article Describes Customizing Win Time Display in Taskbar
keywords: Custom Taskbar Time View,Win Time Display Settings,Adjusting WinBar Clock,Personalized Taskbar Timer,Manage Windows Time Bar,Set Taskbar Time Format,WinBar Time Configurations
thumbnail: https://thmb.techidaily.com/f74f161f0523579dd71e4de3d10404ac967ce66d01905429c873797c52e328b9.jpg
---

## Customizing Win Time Display in Taskbar

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
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-utilizing-obs-in-android-setups-a-beginners-manual/"><u>[New] 2024 Approved Utilizing OBS in Android Setups A Beginner's Manual</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-leading-10-video-editing-programs-for-instagram-reels-enthusiasts/"><u>[New] In 2024, Leading 10 Video Editing Programs for Instagram Reels Enthusiasts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-iphones-premier-video-tools-pick-cameo-over-filmorago/"><u>[Updated] 2024 Approved IPhone's Premier Video Tools Pick Cameo Over FilmoraGo?</u></a></li>
<li><a href="https://win11.techidaily.com/guide-disable-hyber-v-service-in-windows-11/"><u>Guide: Disable Hyber-V Service in Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-poco-c51-frp-bypass-by-drfone-android/"><u>In 2024, About Poco C51 FRP Bypass</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-8-plus-by-drfone-ios/"><u>iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-usb-regulation-in-windows-environment/"><u>Mastering USB Regulation in Windows Environment</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maximizing-energy-the-impressive-beatit-bt-d11-jump-starter-examined/"><u>Maximizing Energy: The Impressive Beatit BT-D11 Jump Starter Examined</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-pioneering-artificial-intelligence-hub/"><u>Microsoft’s Pioneering Artificial Intelligence Hub</u></a></li>
<li><a href="https://win11.techidaily.com/modernizing-windows-11-essential-modifications-and-improvements-for-the-taskbar/"><u>Modernizing Windows 11: Essential Modifications and Improvements for the Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-complexities-of-disabling-non-critical-windows-11-services/"><u>Navigating the Complexities of Disabling Non-Critical Windows 11 Services</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-403-in-roblox/"><u>Navigating Windows Error 403 in Roblox</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-onedrive-login-issues-in-windows/"><u>Overcoming Common OneDrive Login Issues in Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/persona-email-protected-solved-how-to-resolve-pc-gaming-issues/"><u>Persona ([Email Protected]) Solved - How to Resolve PC Gaming Issues</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-chrono-errors-in-chrome-for-windows-users/"><u>Rectifying Chrono-Errors in Chrome for Windows Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-economical-path-to-skype-calls-as-mp3-files-for-2024/"><u>The Economical Path to Skype Calls as MP3 Files for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-evolution-of-my-language-mastery-with-mondly-the-10-key-factors/"><u>The Evolution of My Language Mastery with Mondly - The 10 Key Factors</u></a></li>
</ul></div>


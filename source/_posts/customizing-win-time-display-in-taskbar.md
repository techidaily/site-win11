---
title: Customizing Win Time Display in Taskbar
date: 2024-10-07T07:51:48.535Z
updated: 2024-10-09T12:18:12.985Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-pixels-of-reality-navigating-the-world-of-instagram-authenticity/"><u>[New] In 2024, Pixels of Reality Navigating the World of Instagram Authenticity</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-social-media-savvy-unlock-the-secrets-of-crafting-winning-bios-on-facebook/"><u>[New] In 2024, Social Media Savvy Unlock the Secrets of Crafting Winning Bios on Facebook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-androids-leading-collage-tools-the-ultimate-list/"><u>[Updated] Android's Leading Collage Tools The Ultimate List</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-boundless-playlist-public-domain-music-for-games/"><u>2024 Approved Boundless Playlist Public Domain Music for Games</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-victory-in-original-diablo/"><u>Beginner’s Blueprint to Victory in Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/boost-safety-measures-include-trusted-sites-on-windows-11/"><u>Boost Safety Measures: Include Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-linking-win-prefixes-and-ms-logins/"><u>Enhancing User Experience: Linking Win Prefixes & MS Logins</u></a></li>
<li><a href="https://win11.techidaily.com/explore-versatility-the-best-10-uses-for-windows-powertoys-tools/"><u>Explore Versatility: The Best 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-vivo-s17t-by-drfone-android/"><u>Full Guide to Unlock Your Vivo S17t</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-nokia-c300-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/professional-insights-top-5-cloud-based-videographer-tools/"><u>Professional Insights Top 5 Cloud-Based Videographer Tools</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-honor-magic-5-pro-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Honor Magic 5 Pro Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-version-numbering-in-windows/"><u>The Essence of Version Numbering in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-digital-gateway-easy-desktop-connectivity-with-win-11/"><u>Unlocking the Digital Gateway: Easy Desktop Connectivity with Win 11</u></a></li>
</ul></div>


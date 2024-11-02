---
title: Shut Down Windows' Auto-Update Notifications
date: 2024-10-31T23:16:13.635Z
updated: 2024-11-01T22:15:59.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shut Down Windows' Auto-Update Notifications
excerpt: This Article Describes Shut Down Windows' Auto-Update Notifications
keywords: Stop Windows Update Alerts,Mute Auto-Updates Windows,Halt Windows Notification Updates,Quiet Windows Auto-Update,Turn Off Windows Update Notifications,Disable Windows Update Messages,Silence Windows Update Tone
thumbnail: https://thmb.techidaily.com/05031c348e3a8b265ca81d9de600b6d3876929f7748d63bf7bb6a077bd78b2a6.jpg
---

## Shut Down Windows' Auto-Update Notifications

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.

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
<li><a href="https://facebook-videos.techidaily.com/updated-crafting-success-in-fb-video-advertising-a-collection-of-20-essentials-for-2024/"><u>[Updated] Crafting Success in FB Video Advertising – A Collection of 20 Essentials for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-maximize-your-impact-knowledge-of-instagrams-video-time-policy-for-2024/"><u>[Updated] Maximize Your Impact Knowledge of Instagram's Video Time Policy for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oneplus-nord-n30-se-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your OnePlus Nord N30 SE? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-executables-from-batch-files-in-windows/"><u>Crafting Executables From Batch Files in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-resolving-elevation-needed-errors/"><u>Decoding and Resolving 'Elevation Needed' Errors</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-timely-updates-adding-an-efficient-checkup-toolbar-to-win11/"><u>Ensuring Timely Updates: Adding an Efficient Checkup Toolbar to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/four-hacks-stopping-automatic-windows-and-office-updates/"><u>Four Hacks: Stopping Automatic Windows & Office Updates</u></a></li>
<li><a href="https://win11.techidaily.com/go-direct-to-linux-with-no-wsl/"><u>Go Direct to Linux with No WSL</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-physical-security-measures/"><u>In 2024, Physical Security Measures</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-11-pro-drfone-by-drfone-ios/"><u>iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/kratos-kinks-cured-for-combat/"><u>Kratos Kinks Cured for Combat</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-system-streamlined-windows-autoupdate-and-driver-change/"><u>Optimize System: Streamlined Windows Autoupdate & Driver Change</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-world-effortless-windows-factory-techniques/"><u>Reboot Your World: Effortless Windows Factory Techniques</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-thriving-amidst-the-world-of-podcasts/"><u>The Ultimate Guide to Thriving Amidst the World of Podcasts</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-motorola-moto-g73-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Motorola Moto G73 5G Phone Pattern Lock</u></a></li>
<li><a href="https://win11.techidaily.com/win-strategies-accelerating-valorants-sluggish-downloads/"><u>Win Strategies: Accelerating Valorant's Sluggish Downloads</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/bes-monetary-system-monthly-or-quarterly-for-2024/"><u>YouTube's Monetary System Monthly or Quarterly for 2024</u></a></li>
</ul></div>


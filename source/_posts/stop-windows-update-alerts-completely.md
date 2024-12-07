---
title: Stop Windows Update Alerts Completely
date: 2024-12-02T07:11:13.413Z
updated: 2024-12-07T02:23:20.466Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows Update Alerts Completely
excerpt: This Article Describes Stop Windows Update Alerts Completely
keywords: Stop UWA Alerts,Block UWA Popups,No More Update Warnings,Silence UWA Notices,Halt UWA Interruptions,End UWA Prompts,Disable Windows Updates
thumbnail: https://thmb.techidaily.com/f8511b1b508552460f630419c51d2d616ebcbf19dbd124bdf2e50582d197ea31.jpg
---

## Stop Windows Update Alerts Completely

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/updated-best-free-cloud-options-get-unlimited-storage-1tbplus/"><u>[Updated] Best Free Cloud Options Get Unlimited Storage (1TB+)</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-remote-ratio-reformation-online-calculation/"><u>[Updated] Remote Ratio Reformation Online Calculation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1726027996685-dvd/"><u>信頼性の高い最強DVDコピーツール：プレミアムバージョンをお薦め</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-data-transfer-using-a-python-server-on-windows/"><u>Cross-Platform Data Transfer Using a Python Server on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-no-running-scripts-blockade-in-powershell/"><u>Demystifying the 'No Running Scripts' Blockade in PowerShell</u></a></li>
<li><a href="https://techtrends.techidaily.com/explore-the-highest-quality-ceiling-soundbars-your-definitive-guide/"><u>Explore the Highest Quality Ceiling Soundbars - Your Definitive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-win11-outclasses-macos-in-essential-areas/"><u>How Win11 Outclasses MacOS in Essential Areas</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-crystalvision-pro-screen-capturing-101/"><u>In 2024, CrystalVision Pro Screen Capturing 101</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-why-apple-account-disabled-from-your-apple-iphone-se-2020-how-to-fix-by-drfone-ios/"><u>In 2024, Why Apple Account Disabled From your Apple iPhone SE (2020)? How to Fix</u></a></li>
<li><a href="https://win11.techidaily.com/rewiring-wireless-lan-link-on-windows/"><u>Rewiring Wireless LAN Link on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/triggers-for-restarting-windows-explorer/"><u>Triggers for Restarting Windows Explorer</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/yahoo-implements-new-dmarc-policies-in-depth-analysis-with-massmail-software/"><u>Yahoo Implements New DMARC Policies: In-Depth Analysis with MassMail Software</u></a></li>
</ul></div>


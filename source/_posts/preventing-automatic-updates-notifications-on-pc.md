---
title: Preventing Automatic Updates Notifications on PC
date: 2024-10-20T05:42:36.412Z
updated: 2024-10-26T20:21:03.984Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Automatic Updates Notifications on PC
excerpt: This Article Describes Preventing Automatic Updates Notifications on PC
keywords: Block Update Alerts PC,Turn Off Auto-Update Notify,Disable Windows Update Popups,Stop Notification Updates PC,Halt Automatic Update Announcements,Prevent System Update Warnings,Cease PC Update Alerts
thumbnail: https://thmb.techidaily.com/ce2b50426ded5a960fb87586d9bc144c1e1a55defefae42789a30b646b9173fc.jpeg
---

## Preventing Automatic Updates Notifications on PC

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
<a href="https://aligracehair.sjv.io/c/5597632/1868586/19272" target="_top" id="1868586">
  <img src="//a.impactradius-go.com/display-ad/19272-1868586" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868586/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-lessons.techidaily.com/new-comprehensive-report-on-djis-inspire-1/"><u>[New] Comprehensive Report on DJI's Inspire 1</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-android-and-iphones-leading-tools-for-enhanced-fb-likes/"><u>[Updated] 2024 Approved Android & iPhone's Leading Tools for Enhanced FB Likes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-bridging-scripts-with-voices-turning-xmlttml-into-srt/"><u>[Updated] Bridging Scripts with Voices Turning XML/TTML Into SRT</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-expert-techniques-for-effective-social-sharing-via-pins/"><u>[Updated] Expert Techniques for Effective Social Sharing via Pins</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-mix-fold-3-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://win11.techidaily.com/essential-window-11-icons-to-maximize-efficiency/"><u>Essential Window 11 Icons to Maximize Efficiency</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-pci-serial-port-driver-issues-on-windows/"><u>Fix PCI Serial Port Driver Issues on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transforming-simple-sessions-into-high-end-audacity-recordings/"><u>In 2024, Transforming Simple Sessions Into High-End Audacity Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-opening-spotify-autoplay/"><u>Prevent Windows From Opening Spotify Autoplay</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-success-9-essential-steps-for-flawless-windows-media-views/"><u>Streamline Success: 9 Essential Steps for Flawless Windows Media Views</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-file-management-using-text-actions-in-snip/"><u>Streamline Windows 11 File Management Using Text Actions in Snip</u></a></li>
<li><a href="https://youtube-web.techidaily.com/mlining-content-delivery-the-definitive-youtube-video-upload-guide/"><u>Streamlining Content Delivery The Definitive YouTube Video Upload Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-endless-scroll-problems-with-excel-on-windows/"><u>Tackle Endless Scroll Problems with Excel on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-pros-guide-to-hidden-power-ups-in-vlc-playback-for-2024/"><u>The Pro's Guide to Hidden Power-Ups in VLC Playback for 2024</u></a></li>
</ul></div>


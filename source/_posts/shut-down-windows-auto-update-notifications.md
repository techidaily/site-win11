---
title: Shut Down Windows' Auto-Update Notifications
date: 2024-11-06T19:49:07.486Z
updated: 2024-11-07T18:23:51.024Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

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
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-enhancing-call-clarity-silencing-distractions/"><u>[New] Enhancing Call Clarity Silencing Distractions</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-linked-insight-merging-instagram-and-tiktok/"><u>[New] Linked Insight Merging Instagram & TikTok</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-decoding-the-vertical-video-enigma-on-insta-for-2024/"><u>[Updated] Decoding the Vertical Video Enigma on Insta for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-top-10-affordable-and-easy-online-passport-pics-tools/"><u>[Updated] In 2024, Top 10 Affordable & Easy Online Passport Pics Tools</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-vanguards-choice-top-7-fps-wonders/"><u>2024 Approved Vanguard's Choice Top 7 FPS Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-for-starting-a-system-restore-on-windows-11/"><u>Essential Techniques for Starting a System Restore on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-tecno-pova-6-pro-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Tecno Pova 6 Pro 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-microsoft-store-issue-x800704cf-on-pcs/"><u>Guide to Correcting Microsoft Store Issue X800704CF on PCs</u></a></li>
<li><a href="https://fox-direct.techidaily.com/holiday-memories-revisited-summertimes-best-vacation-flicks-for-2024/"><u>Holiday Memories Revisited Summertime’s Best Vacation Flicks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-flip-your-pcs-two-screens/"><u>How to Flip Your PC's Two Screens</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-optimized-orchestration-top-5-chrome-vids-from-fb/"><u>In 2024, Optimized Orchestration Top 5 Chrome Vids From FB</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/japans-alphabet-unveiled-a-linguistic-journey/"><u>Japan's Alphabet Unveiled: A Linguistic Journey</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-sandbox-initialization-guide/"><u>Mastering Windows 11 Sandbox: Initialization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-overcoming-white-out-screens-in-win1011/"><u>Tactics for Overcoming White Out Screens in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-made-winterral-ambiance/"><u>Tailor-Made WinTerral Ambiance</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-menu-how-to-reduce-extra-options-displayed/"><u>Windows 11 Menu: How to Reduce Extra Options Displayed</u></a></li>
</ul></div>


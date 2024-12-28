---
title: Tailored Instructions for Microsoft Office to Handle Email Content in Reading Mode
date: 2024-12-22T02:09:53.692Z
updated: 2024-12-27T16:37:00.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailored Instructions for Microsoft Office to Handle Email Content in Reading Mode
excerpt: This Article Describes Tailored Instructions for Microsoft Office to Handle Email Content in Reading Mode
keywords: Office Reading Mode,Excel Readability,Word Email Guide,Outlook Accessibility,Mailbox Display Tips,PowerPoint PDF Formatting,VBA Scripting for EMail
thumbnail: https://thmb.techidaily.com/41e7c10c6afe154b3744b08a21830239b330cdc09fe1222610e43f6045480d9b.jpg
---

## Tailored Instructions for Microsoft Office to Handle Email Content in Reading Mode

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.

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
<li><a href="https://buynow-reviews.techidaily.com/1722584432842-can-the-samsung-cf591-deliver-an-exceptional-gaming-experience-an-experts-insight/"><u>Can the Samsung CF591 Deliver an Exceptional Gaming Experience? An Expert's Insight.</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-power-within-wintoys-an-in-depth-user-friendly-guide-for-windows-os-users/"><u>Discover the Power Within WinToys: An In-Depth, User-Friendly Guide for Windows OS Users</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-notifications-from-phone-link-app-in-windows-environment/"><u>Fixing Inactive Notifications From Phone Link App in Windows Environment</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/game-time-capture-essential-tips-for-recording-sports-for-2024/"><u>Game-Time Capture Essential Tips for Recording Sports for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-roblox-error-code-403-on-pc/"><u>Guide to Fixing Roblox Error Code 403 on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-xiaomi-13t-by-fonelab-android-recover-photos/"><u>How To Restore Missing Photos Files from Xiaomi 13T.</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-best-of-breed-capture-card-for-switch/"><u>In 2024, Best of Breed Capture Card for Switch</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-essential-gopro-video-editor-companies/"><u>In 2024, Essential GoPro Video Editor Companies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-oppo-reno-8t-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Oppo Reno 8T to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/live-microphone-input-addressing-recording-issues-with-obs-w11-edition/"><u>Live Microphone Input: Addressing Recording Issues with OBS, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-without-installation-in-windows-11/"><u>Notetaking Without Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11s-narrator-command-efficiency/"><u>Unlocking Win11's Narrator Command Efficiency</u></a></li>
<li><a href="https://facebook.techidaily.com/unveiling-ray-ban-stories-on-facebook-what-can-you-expect/"><u>Unveiling Ray-Ban Stories on Facebook - What Can You Expect?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-ultimate-guide-to-free-online-glitch-effect-creators/"><u>Updated The Ultimate Guide to Free Online Glitch Effect Creators</u></a></li>
<li><a href="https://win11.techidaily.com/win11-icons-how-to-ditch-the-focused-wallpaper-symbol/"><u>Win11 Icons: How to Ditch the Focused Wallpaper Symbol</u></a></li>
</ul></div>


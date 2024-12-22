---
title: Make Office Automatically Open Attached Files as Text Only
date: 2024-12-19T17:41:33.761Z
updated: 2024-12-22T16:20:14.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Make Office Automatically Open Attached Files as Text Only
excerpt: This Article Describes Make Office Automatically Open Attached Files as Text Only
keywords: Auto Office File Opener,Text-Only Opening,Filter Attachment Content,Convert PDF to Text,Exclude Images in Files,Save as Plain Text,Remove Image Data
thumbnail: https://thmb.techidaily.com/d8e6435243e7bdae68e29ae66158699a00161b12482bc1fecd3d439c888dea97.png
---

## Make Office Automatically Open Attached Files as Text Only

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-files.techidaily.com/new-in-2024-how-to-shoot-underwater-video-easily-with-7-tips/"><u>[New] In 2024, How to Shoot Underwater Video Easily (with 7 Tips)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-audience-experience-top-cameras-to-capture-live-music/"><u>[Updated] Audience Experience Top Cameras to Capture Live Music</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-immaculate-window-display-on-w11/"><u>A Guide to Immaculate Window Display on W11</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-maintaining-perpetual-ps4-windows-tether/"><u>A Guide to Maintaining Perpetual PS4-Windows Tether</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-network-not-reachable-issues-on-windows-11-computers/"><u>Addressing 'Network Not Reachable' Issues on Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-glitches-a-guide-for-fixing-windows-office-issues/"><u>Addressing Failure Glitches: A Guide for Fixing Windows Office Issues</u></a></li>
<li><a href="https://win11.techidaily.com/airplane-mode-heres-your-guide-for-win11/"><u>Airplane Mode? Here's Your Guide for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-stability-fixing-high-memory-usage-of-services/"><u>Boosting System Stability: Fixing High Memory Usage of Services</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-itel-a60-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Itel A60 Location | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premier-recommendations-the-top-10-sports-apps-for-live-tennis-games-for-2024/"><u>Premier Recommendations The Top 10 Sports Apps for Live Tennis Games for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-motorola-moto-g13-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Motorola Moto G13 IMEI without Root A Comprehensive Guide</u></a></li>
</ul></div>


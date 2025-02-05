---
title: Tailored Instructions for Microsoft Office to Handle Email Content in Reading Mode
date: 2025-01-29T17:03:26.288Z
updated: 2025-02-04T04:16:00.993Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-zoom-like-a-pro-avoiding-common-snaps-mistakes/"><u>[New] In 2024, Zoom Like a Pro Avoiding Common Snaps Mistakes</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-affordable-high-quality-asmr-recording-devices-revealed/"><u>[Updated] Affordable, High-Quality ASMR Recording Devices Revealed</u></a></li>
<li><a href="https://screen-recording.techidaily.com/15-best-tools-to-capture-classroom-learning-moments-for-2024/"><u>15 Best Tools to Capture Classroom Learning Moments for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-unleash-flawless-footage-overcome-instagram-video-hurdles/"><u>2024 Approved Unleash Flawless Footage Overcome Instagram Video Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-m365-error-30015-26-in-windows-environment/"><u>Disabling M365 Error 30015-26 in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/go-above-and-beyond-with-these-non-windows-applications/"><u>Go Above and Beyond With These Non-Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fix-windows-operation-failure-x709/"><u>Guide to Fix Windows Operation Failure X709</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-device-is-unreachable-error-0x80070141-on-windows/"><u>How to Fix the “Device Is Unreachable” Error 0X80070141 on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-samsung-galaxy-f54-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Samsung Galaxy F54 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-broadcom-bluetooth-software-on-windows-10-8-and-7-systems/"><u>Installing Broadcom Bluetooth Software on Windows 10, 8 & 7 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/retroarc-mastery-shader-techniques-to-restore-classic-games/"><u>RetroArc Mastery: Shader Techniques to Restore Classic Games</u></a></li>
<li><a href="https://win11.techidaily.com/revive-missing-file-images-in-windows-11s-user-interface/"><u>Revive Missing File Images in Windows 11’S User Interface</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-infinix-hot-30-5g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Infinix Hot 30 5G Location | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-recommended-netgear-router-models/"><u>Top Recommended Netgear Router Models</u></a></li>
<li><a href="https://win11.techidaily.com/win11-fixing-the-printer-offline-conundrum/"><u>Win11: Fixing the 'Printer Offline' Conundrum</u></a></li>
</ul></div>


---
title: Tips to Keep Word Reading Mode Active When Handling Email Attachments
date: 2024-06-25T11:33:08.771Z
updated: 2024-06-26T11:33:08.771Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Keep Word Reading Mode Active When Handling Email Attachments
excerpt: This Article Describes Tips to Keep Word Reading Mode Active When Handling Email Attachments
keywords: Active Email Reading,Word Optimize View,Handling Attachments Tips,Maintain Readability,Email Alert Mode,Attachment Management,Enhance Word Display
thumbnail: https://thmb.techidaily.com/dbe86ec4eee57de28307f7a87e5d2dc26b222d4d704a45568094d723e05d6df4.jpg
---

## Tips to Keep Word Reading Mode Active When Handling Email Attachments

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

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
<li><a href="https://win11.techidaily.com/mastery-over-warhammer-40k-boltgun-stopping-stutter-issues-on-pc/"><u>Mastery Over Warhammer 40K Boltgun: Stopping Stutter Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-error-0x800704b3/"><u>How to Bypass Windows Error 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-system-call-failed-error-on-windows-10-and-11/"><u>How to Fix the “System Call Failed” Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-new-folders-into-windows-11s-menu/"><u>Integrating New Folders Into Windows 11'S Menu</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-revamp-for-windows-11-status-area-include-a-chosen-weather-symbol/"><u>Aesthetic Revamp for Windows 11 Status Area: Include a Chosen Weather Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-using-windows-11-snap-features/"><u>Essential Tips for Using Windows 11 Snap Features</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-address-winget-malfunctioning-in-windows-11/"><u>Easy Steps to Address Winget Malfunctioning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transform-spending-habits-with-premium-windows-11-pro-key/"><u>Transform Spending Habits with Premium Windows 11 Pro Key</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-silent-spectator-of-social-media-snippets/"><u>[Updated] In 2024, Silent Spectator of Social Media Snippets</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-chordcapture-studio-free-download-and-evaluate/"><u>2024 Approved  ChordCapture Studio  Free, Download & Evaluate</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/critically-acclaimed-phone-and-desktop-video-calls-list-for-2024/"><u>Critically Acclaimed Phone and Desktop Video Calls List for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/instant-adjustment-match-youtube-to-mac-aspects-for-2024/"><u>Instant Adjustment  Match YouTube to Mac Aspects for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/top-online-resources-for-blurring-image-backgrounds/"><u>Top Online Resources for Blurring Image Backgrounds</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/trouble-with-apple-iphone-se-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>Trouble with Apple iPhone SE Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-ethereal-solution-for-digital-realities/"><u>2024 Approved  Ethereal Solution for Digital Realities</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unveiling-the-secrets-of-video-editing-on-youtube/"><u>[Updated] Unveiling the Secrets of Video Editing on YouTube</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-xiaomi-redmi-12-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Xiaomi Redmi 12</u></a></li>
</ul></div>

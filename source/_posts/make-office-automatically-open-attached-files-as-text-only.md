---
title: Make Office Automatically Open Attached Files as Text Only
date: 2025-01-04T20:52:51.303Z
updated: 2025-01-06T18:22:20.262Z
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

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-efficiently-recording-your-xbox-adventures/"><u>[New] In 2024, Efficiently Recording Your Xbox Adventures</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-androids-technique-for-retroactive-viewing/"><u>2024 Approved Android's Technique for Retroactive Viewing</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-elite-recording-tech-premium-podcast-mics/"><u>2024 Approved Elite Recording Tech Premium Podcast Mics</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-ideal-video-intros-selecting-from-top-15-youtube-sets/"><u>2024 Approved Ideal Video Intros Selecting From Top 15 YouTube Sets</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-win11s-protection-measures-with-rufus/"><u>Disabling Win11's Protection Measures with Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-update-group-policy-on-pcs/"><u>Essential Steps to Update Group Policy on PCs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hand-tracking-deciphered-a-users-guide-for-2024/"><u>Hand Tracking Deciphered A User's Guide for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-x9b-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Honor X9b | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-xiaomi-civi-3-disney-100th-anniversary-edition-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Xiaomi Civi 3 Disney 100th Anniversary Edition Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-task-management-on-windows-platforms/"><u>Pinnacle Task Management on Windows Platforms</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/selecting-the-top-cameras-for-smooth-twitch-broadcasts-for-2024/"><u>Selecting the Top Cameras for Smooth Twitch Broadcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-ease-windows-11-license-soon-to-end-stress/"><u>Solutions to Ease Windows 11 License 'Soon-to-End' Stress</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-tutorial-correcting-the-corrupt-disk-error-for-smooth-steam-gaming/"><u>Step-by-Step Tutorial: Correcting the 'Corrupt Disk' Error for Smooth Steam Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-dismissing-essential-component-alert-on-windows-1011/"><u>Steps for Dismissing Essential Component Alert on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-drawing-apps-for-windows-11/"><u>The 7 Best Drawing Apps for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-the-no-sync-option-on-steam-for-windows/"><u>Winning Over the No Sync Option on Steam for Windows</u></a></li>
</ul></div>


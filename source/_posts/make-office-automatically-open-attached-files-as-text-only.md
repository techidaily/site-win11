---
title: Make Office Automatically Open Attached Files as Text Only
date: 2025-01-11T23:22:48.892Z
updated: 2025-01-12T21:11:47.338Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-blog.techidaily.com/n-2024-stay-steady-with-the-right-tripod-techniques-for-top-notch-video-content/"><u>[New] In 2024, Stay Steady with the Right Tripod Techniques for Top-Notch Video Content</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-make-the-most-of-your-tunes-top-5-tools-for-converting-spotify-to-youtube-playlists/"><u>[New] Make the Most of Your Tunes Top 5 Tools for Converting Spotify to YouTube Playlists</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-boost-your-content-reach-the-expert-guide-to-youtubes-featured-channels/"><u>[Updated] In 2024, Boost Your Content Reach The Expert Guide to Youtube's Featured Channels</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-maximizing-engagement-with-dual-screen-broadcasting-techniques-in-facebook/"><u>2024 Approved Maximizing Engagement with Dual-Screen Broadcasting Techniques in Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/chorus-closet-capture-download-and-listen-to-tunes-for-2024/"><u>Chorus Closet Capture, Download & Listen to Tunes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-upgrade-opt-for-cleaner-win11/"><u>Effortless Upgrade: Opt for Cleaner Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-with-simple-key-filter-adjustments/"><u>Enhance Accessibility with Simple Key Filter Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/hide-and-seek-discreet-start-menu-controls/"><u>Hide and Seek: Discreet Start Menu Controls</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-nokia-c12-pro-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Nokia C12 Pro</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-path-to-success-integrating-past-recordings-in-real-time-on-social-media/"><u>In 2024, The Path to Success Integrating Past Recordings in Real Time on Social Media</u></a></li>
<li><a href="https://win11.techidaily.com/opening-disk-management-in-windows-1011-with-ease/"><u>Opening Disk Management in Windows 10/11 with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-typing-mastery-through-typingaid/"><u>Rapid Typing Mastery Through TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-resource-occupancy-issues-in-windows-1011-153-chars/"><u>Tackling Resource Occupancy Issues in Windows 10/11 (153 Chars)</u></a></li>
<li><a href="https://win-docs.techidaily.com/1728508699350-windows-server/"><u>ネットワーク上の共有ディレクトリへのWindows Serverセグメントバックアップ: ステップバイステップガイド</u></a></li>
</ul></div>


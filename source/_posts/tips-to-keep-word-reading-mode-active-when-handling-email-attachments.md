---
title: Tips to Keep Word Reading Mode Active When Handling Email Attachments
date: 2024-06-25T10:16:50.690Z
updated: 2024-06-26T10:16:50.690Z
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
<li><a href="https://win11.techidaily.com/how-to-reverse-error-0x7e1-on-win1011/"><u>How to Reverse Error 0X7E1 on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-windows-experience-adding-contextual-items/"><u>Upgrading Your Windows Experience: Adding Contextual Items</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-non-windows-sniping-tools-for-quick-screen-capture/"><u>Top 5 Non-Windows Sniping Tools for Quick Screen Capture</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/breach-the-barrier-opening-credential-store/"><u>Breach the Barrier: Opening Credential Store</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-esd-format-to-compatible-windows-isos/"><u>Transforming ESD Format to Compatible Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/harness-windows-11s-netstat-power-for-traffic-observation/"><u>Harness Windows 11'S Netstat Power for Traffic Observation</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-agricultural-adventures-with-allies-top-10-farmers-titles/"><u>In 2024, Agricultural Adventures with Allies  Top 10 Farmer's Titles</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-spys-guide-to-unearthing-hidden-youtube-videos/"><u>2024 Approved  The Spy's Guide to Unearthing Hidden YouTube Videos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-meizu-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Meizu Phone and Remove Locked Screen</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-leading-audio-recording-apps-ranking-the-best-mp3-recorders-for-pc-and-mac-platforms/"><u>Updated In 2024, Leading Audio Recording Apps Ranking the Best MP3 Recorders for PC & Mac Platforms</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-crafters-guide-to-crafting-a-unique-tiktok-keyphrase/"><u>[Updated] 2024 Approved  Crafters' Guide to Crafting a Unique TikTok Keyphrase</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-11-pro-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue From Apple iPhone 11 Pro</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-remove-distractions-in-webcam-captures/"><u>[Updated] Remove Distractions in Webcam Captures</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-hear-the-difference-a-step-by-step-approach-to-cleaning-up-sound-tracks-in-adobe-audition/"><u>2024 Approved Hear the Difference A Step-by-Step Approach to Cleaning Up Sound Tracks in Adobe Audition</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-mastering-podcast-accessibility-10-exemplary-cost-free-ios-apps/"><u>In 2024, Mastering Podcast Accessibility 10 Exemplary Cost-Free iOS Apps</u></a></li>
</ul></div>

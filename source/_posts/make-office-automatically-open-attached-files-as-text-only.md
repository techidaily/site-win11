---
title: Make Office Automatically Open Attached Files as Text Only
date: 2025-02-02T10:01:58.038Z
updated: 2025-02-03T16:44:36.770Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-navigating-the-world-of-unfollowed-instagrams/"><u>[New] 2024 Approved Navigating the World of Unfollowed Instagrams</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-how-to-make-your-solitary-voice-resonate/"><u>[New] In 2024, How To Make Your Solitary Voice Resonate</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-unlocking-youtube-potential-expert-tips-for-wirecast-streaming/"><u>2024 Approved Unlocking YouTube Potential Expert Tips for WireCast Streaming</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/a-week-with-an-ergonomic-split-keyboard-how-one-change-transformed-my-workstation-setup-techadvisor/"><u>A Week with an Ergonomic Split Keyboard: How One Change Transformed My Workstation Setup | TechAdvisor</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amazons-social-stardom-liking-and-viewing-leaderships-for-2024/"><u>Amazon's Social Stardom Liking and Viewing Leaderships for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ending-recurring-edge-icon-placement/"><u>Ending Recurring Edge Icon Placement</u></a></li>
<li><a href="https://win11.techidaily.com/host-free-windows-based-gpt-clones-using-gpt4all/"><u>Host Free Windows-Based GPT Clones Using GPT4All</u></a></li>
<li><a href="https://some-tips.techidaily.com/how-apples-on-device-ai-system-realm-outshines-microsofts-gpt-4-unveiling-the-details-with-zdnet/"><u>How Apple's On-Device AI System, ReaLM, Outshines Microsoft's GPT-4: Unveiling the Details with ZDNet</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-poco-c50-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Poco C50 Phone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-microsoft-store-error-code-0-in-windows-11/"><u>How to Eliminate Microsoft Store Error Code 0 in Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-htc-u23-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve HTC U23 Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-gpresult-for-dynamic-group-policy-reports/"><u>Leveraging GPResult for Dynamic Group Policy Reports</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-eradicating-freezing-issues-with-steam-on-win-11/"><u>Mastering Fixes: Eradicating Freezing Issues with Steam on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-403-in-roblox/"><u>Navigating Windows Error 403 in Roblox</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-gopro-quik-for-computer-top-picks-and-alternatives-for-2024/"><u>New GoPro Quik for Computer Top Picks and Alternatives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/sprint-past-slow-spots-enhance-win-outlook/"><u>Sprint Past Slow Spots: Enhance WIN Outlook</u></a></li>
</ul></div>


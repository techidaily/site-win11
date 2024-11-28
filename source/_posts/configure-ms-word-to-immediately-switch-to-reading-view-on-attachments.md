---
title: Configure MS Word to Immediately Switch to Reading View on Attachments
date: 2024-11-22T00:19:09.221Z
updated: 2024-11-27T17:42:35.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configure MS Word to Immediately Switch to Reading View on Attachments
excerpt: This Article Describes Configure MS Word to Immediately Switch to Reading View on Attachments
keywords: Word Read Mode On Attach,Auto Reading View Word,Attachments Default Read,Word Set Reading Atk,Instant Reading MS Word,Quick Read Word Attachment,Switch to Reading in Word
thumbnail: https://thmb.techidaily.com/445acff3cb96c7fdb86bf94a45c03c504df7c348a8d93fea013a39cba2a1ab43.jpg
---

## Configure MS Word to Immediately Switch to Reading View on Attachments

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

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-free-vecto-art-and-graphic-sites-compared-whos-the-best/"><u>[New] In 2024, Free Vecto Art & Graphic Sites Compared – Who's the Best?</u></a></li>
<li><a href="https://youtube-web.techidaily.com/rofessional-thumbnails-from-your-phone-for-youtube-for-2024/"><u>[New] Professional Thumbnails From Your Phone for YouTube for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-laughters-playground-top-15-youtube-hits-for-fun/"><u>[Updated] In 2024, Laughter's Playground Top 15 YouTube Hits for Fun</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-x-transcription-software-pc-for-2024/"><u>[Updated] X-Transcription Software PC for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-narrative-blueprint-a-basic-overview/"><u>2024 Approved Narrative Blueprint A Basic Overview</u></a></li>
<li><a href="https://blog-min.techidaily.com/explore-manycams-capabilities-in-real-time-broadcasting-and-digital-webcams-for-seamless-livestreaming-experience/"><u>Explore ManyCam's Capabilities in Real-Time Broadcasting and Digital Webcams for Seamless Livestreaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-chromes-failed-virus-detected-error-on-windows/"><u>How to Fix Chrome's Failed - Virus Detected Error on Windows</u></a></li>
<li><a href="https://techidaily.com/how-windows-11-integrates-with-android-phones-through-onedrive/"><u>How Windows 11 Integrates with Android Phones Through OneDrive</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-advanced-methods-save-vimeo-content/"><u>In 2024, Advanced Methods Save Vimeo Content</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-blue-screen-errors/"><u>Navigating Through the Maze of Blue Screen Errors</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-microphone-and-xbox-app-on-1011-pcs/"><u>Reconciling Microphone and Xbox App on 10/11 PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/solutions-when-humanity-adventure-pc-doesnt-open-properly/"><u>Solutions When Humanity Adventure Pc Doesn’t Open Properly</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-cmd-appearance-without-prior-notice/"><u>Stopping CMD Appearance Without Prior Notice</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-eradicating-onedrive-from-explorer-window/"><u>Techniques for Eradicating OneDrive From Explorer Window</u></a></li>
<li><a href="https://win11.techidaily.com/the-ins-and-outs-of-socket-programming-with-python-servers-on-pcs/"><u>The Ins and Outs of Socket Programming with Python Servers on PCs</u></a></li>
</ul></div>


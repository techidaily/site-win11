---
title: Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing
date: 2024-06-25T11:25:01.260Z
updated: 2024-06-26T11:25:01.260Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing
excerpt: This Article Describes Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing
keywords: MS Word Default View,Reading Pane Emails,Reading Pane Only,Email Attachment Display,Avoid Editing PDFs,Quick Access Attachments,No Editing Feature,Word Default Reading Pane Email,Use Reading Pane Attachments,No Editing MS Word PDFs,Quick Access Attachments Only,Reading Pane Email View,Directly Show Attachments,Avoid Editing in MS Word
thumbnail: https://thmb.techidaily.com/fa0f0d9aa480a84d4958b92625d7efd743147dd9e7afea427f137746eefc2011.png
---

## Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing

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
<li><a href="https://win11.techidaily.com/overcoming-obstacles-with-windows-printmanagement-msc-errors/"><u>Overcoming Obstacles with Windows 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-login-after-windows-errors/"><u>How to Reactivate Login After Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-code-e1-in-w10w11-devices/"><u>Tackling Error Code: E1 in W10/W11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-file-viewer-rights-in-windows-1011/"><u>How to Regain File Viewer Rights in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-tracking-and-managing-network-data-using-netstat-in-win11/"><u>Master the Art of Tracking and Managing Network Data Using Netstat in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-and-mitigating-windows-pause-problems/"><u>Uncovering and Mitigating Windows Pause Problems</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-best-5-twitter-alternatives-for-2024/"><u>[New] Best 5 Twitter Alternatives for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-ultimate-guide-to-stunning-ig-video-creation-for-2024/"><u>The Ultimate Guide to Stunning IG Video Creation for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-poco-c51-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Poco C51 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-achieve-high-rankings-on-youtube-with-top-seo-tips-1-11/"><u>[Updated] 2024 Approved  Achieve High Rankings on YouTube with Top SEO Tips (1-11)</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-2-ways-to-monitor-apple-iphone-8-activity-drfone-by-drfone-virtual-ios/"><u>In 2024, 2 Ways to Monitor Apple iPhone 8 Activity | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-oneplus-by-drfone-android/"><u>How to Bypass FRP on OnePlus?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unraveling-the-mysteries-of-instagram-saved-stories-for-2024/"><u>[New] Unraveling the Mysteries of Instagram Saved Stories for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-honor-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Honor</u></a></li>
</ul></div>

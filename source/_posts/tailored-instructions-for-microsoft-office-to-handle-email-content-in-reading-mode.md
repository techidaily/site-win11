---
title: Tailored Instructions for Microsoft Office to Handle Email Content in Reading Mode
date: 2025-01-05T18:29:15.332Z
updated: 2025-01-06T17:39:58.491Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-soundscape-adjustments-fading-volume-with-precision-in-logic-pro/"><u>[New] 2024 Approved Soundscape Adjustments Fading Volume with Precision in Logic Pro</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-uncover-the-art-of-participating-in-tiktok-live-shows/"><u>[New] Uncover the Art of Participating in TikTok Live Shows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-swinging-sparrow-suites/"><u>[Updated] Swinging Sparrow Suites</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ai-powered-assistants-transforming-the-editors-workspace/"><u>AI-Powered Assistants Transforming the Editor's Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-win11s-power-button-for-swift-access/"><u>Customizing Win11's Power Button for Swift Access</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-onedrive-sign-in-error-0x8004dec5-on-windows-11/"><u>How to Fix the OneDrive Sign In Error 0X8004dec5 on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-14-to-other-iphone-14-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 14 to other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/in-depth-analysis-of-cutting-edge-pc-components-by-toms-team/"><u>In-Depth Analysis of Cutting-Edge PC Components by Tom's Team</u></a></li>
<li><a href="https://win11.techidaily.com/master-device-performance-analysis-through-windows-panels/"><u>Master Device Performance Analysis Through Windows Panels</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-tasks-5-top-tier-windows-car-drivers/"><u>Optimize Tasks: 5 Top-Tier Windows Car Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-microsofts-companion-functionality-in-windows-via-vivetool/"><u>Streamline Microsoft's Companion Functionality in Windows via ViveTool</u></a></li>
<li><a href="https://win11.techidaily.com/switching-from-modern-search-bar-design-back-to-icons-in-win11/"><u>Switching From Modern Search Bar Design Back to Icons in Win11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-definitive-take-on-the-thin-and-agile-lenovo-thinkpad-x1-nano-notebook-a-critical-review/"><u>The Definitive Take on the Thin & Agile Lenovo ThinkPad X1 Nano Notebook - A Critical Review</u></a></li>
<li><a href="https://win11.techidaily.com/the-experts-approach-to-adjusting-window-11s-text-appearance/"><u>The Expert's Approach to Adjusting Window 11'S Text Appearance</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-ultimate-guide-to-enhancing-your-airpods-pro-experience-expert-insights-from-zdnet/"><u>The Ultimate Guide to Enhancing Your AirPods Pro Experience | Expert Insights From ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-the-root-of-dxgierror-in-windows-11/"><u>Uncover the Root of DXGI_ERROR in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-windows-headsets-communication-channel/"><u>Unfreezing Windows Headset's Communication Channel</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlocking-windows-11s-visual-capabilities-with-auto-hdr-mode-activation-for-2024/"><u>Unlocking Windows 11'S Visual Capabilities with Auto HDR Mode Activation for 2024</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/1728493027722-windows-112/"><u>Windows 11で空き領域をクリアするためのベストプラクティス№2</u></a></li>
</ul></div>


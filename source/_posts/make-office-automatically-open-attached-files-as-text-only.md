---
title: Make Office Automatically Open Attached Files as Text Only
date: 2025-01-23T16:40:44.975Z
updated: 2025-01-24T18:48:41.503Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-hints.techidaily.com/new-craft-your-own-multitasking-masterpiece-with-these-15-tips/"><u>[New] Craft Your Own Multitasking Masterpiece with These 15 Tips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-art-of-background-elimination-in-graphic-designs/"><u>2024 Approved The Art of Background Elimination in Graphic Designs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/choosing-between-the-latest-flagships-iphone-15-pro-max-and-samsung-s24-ultra-reviewed/"><u>Choosing Between the Latest Flagships: IPhone 15 Pro Max and Samsung S24 Ultra Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-context-menu-for-a-cleaner-win-11-experience/"><u>Customize Your Context Menu for a Cleaner Win 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/differences-spotlighted-microsoft-account-vs-non-microsoft-windows-logins/"><u>Differences Spotlighted: Microsoft Account vs Non-Microsoft Windows Logins</u></a></li>
<li><a href="https://win-online.techidaily.com/guide-complet-pour-transferer-and-recreer-votre-image-windows-11-sur-un-disque-solide-ssd-migration-du-sys-op/"><u>Guide Complet Pour Transférer & Recréer Votre Image Windows 11 Sur Un Disque Solide (SSD) : Migration Du Sys Op</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-inclusion-of-emoji-15-in-windows-11-systems/"><u>Seamless Inclusion of Emoji 15 in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-prevent-autostarted-microsoft-marketplace/"><u>Techniques to Prevent Autostarted Microsoft Marketplace</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/transforming-ultra-hd-footage-into-high-definition-a-step-by-step-guide/"><u>Transforming Ultra-HD Footage Into High Definition: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-update-failure-code-0x80246007-on-1011/"><u>Troubleshooting: Windows Update Failure Code 0X80246007 on 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/virtual-box-upgrade-unleashed-migrating-to-version-70-on-windows-11-pcs/"><u>Virtual Box Upgrade Unleashed: Migrating to Version 7.0 on Windows 11 PCs</u></a></li>
</ul></div>


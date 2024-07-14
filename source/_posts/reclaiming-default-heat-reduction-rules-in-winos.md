---
title: Reclaiming Default Heat Reduction Rules in WinOS
date: 2024-07-13T10:51:41.703Z
updated: 2024-07-14T10:51:41.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Default Heat Reduction Rules in WinOS
excerpt: This Article Describes Reclaiming Default Heat Reduction Rules in WinOS
keywords: Windows Heat Rule Reclamation,Optimize OS WinTemp,WinOS Coolness Controls,Default Temp Fixes Win,Reduce WinHeat Effectively,Thermal Settings Adjust Win,Manage WinTemperature Norm
thumbnail: https://thmb.techidaily.com/6462de374e4f489455f584c5102443a7cb28c7609933729fa2bbdde0fb2df507.jpg
---

## Reclaiming Default Heat Reduction Rules in WinOS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://facebook.techidaily.com/7-negative-effects-of-social-media-on-people-and-users/"><u>7 Negative Effects of Social Media on People and Users</u></a></li>
<li><a href="https://techidaily.com/is-your-oneplus-nord-ce-3-lite-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your OnePlus Nord CE 3 Lite 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/effortless-itunes-for-podcast-enthusiasts/"><u>Effortless iTunes for Podcast Enthusiasts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-winscreens-mastery-identifying-the-top-5-capture-apps/"><u>In 2024, WinScreens Mastery  Identifying the Top 5 Capture Apps</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-xiaomi-redmi-note-12-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Xiaomi Redmi Note 12 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-windows-integration-with-steam-deck/"><u>Master Windows Integration with Steam Deck</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-high-quality-audio-collections-a-youtube-creators-guidebook-for-2024/"><u>[New] High-Quality Audio Collections  A YouTube Creator's Guidebook for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-satirical-hits-the-funniest-song-rewrites/"><u>2024 Approved  Satirical Hits  The Funniest Song Rewrites</u></a></li>
<li><a href="https://win11.techidaily.com/making-the-most-of-windows-11-using-dev-drive-effectively/"><u>Making the Most of Windows 11: Using Dev Drive Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/instant-setup-acquiring-adobe-reader-via-ms-store/"><u>Instant Setup: Acquiring Adobe Reader via MS Store</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevating-your-content-strategy-youtube-keywords-explained-for-2024/"><u>Elevating Your Content Strategy  YouTube Keywords Explained for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/keep-it-neat-how-to-make-windows-recycle-bin-self-cleanse/"><u>Keep It Neat: How to Make Windows Recycle Bin Self-Cleanse</u></a></li>
<li><a href="https://win11.techidaily.com/guide-repairing-windows-based-pen-tablets/"><u>Guide: Repairing Windows-Based Pen Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-11-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 11 & 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Infinix Note 30 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revive-your-lost-iphone-x-with-these-tips-for-2024/"><u>Revive Your LOST iPhone X with These Tips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-file-damaged-message-error-0x80070570-in-windows-oses/"><u>Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/commanding-control-navigating-the-windows-print-hub/"><u>Commanding Control: Navigating the Windows Print Hub</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-basics-windows-system-configuration/"><u>Master the Basics: Windows System Configuration</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-steam-deck-performance-with-coolers/"><u>Enhancing Steam Deck Performance with Coolers</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-overcoming-geforce-nows-xc0f1103f-problem-in-win11/"><u>Guides to Overcoming GeForce Now’s Xc0f1103f Problem in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-for-bulk-folder-formation-in-windows-1011/"><u>Efficient Methods for Bulk Folder Formation in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-to-reclaim-blank-login-screen-on-windows-11/"><u>Fixes to Reclaim Blank Login Screen on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-free-media-tools-for-windows-pcs/"><u>Explore the Finest Free Media Tools for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-displaying-messages-errors-in-discord-for-windows/"><u>Fixing Non-Displaying Messages Errors in Discord for Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-silent-snapshots-avoiding-blurry-blows/"><u>In 2024, Silent Snapshots  Avoiding Blurry Blows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-most-effective-6-voice-changer-applications-for-real-time-use-for-2024/"><u>New The Most Effective 6 Voice Changer Applications for Real-Time Use for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-10-simple-yet-effective-neon-text-generators-online-for-2024/"><u>New 10 Simple Yet Effective Neon Text Generators Online for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-solutions-for-oppo-network-unlock-by-drfone-android/"><u>In 2024, Best Solutions for Oppo Network Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-the-disparity-between-remote-windows-upgrades-and-purchases/"><u>Evaluating the Disparity Between Remote Windows Upgrades & Purchases</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-upgrade-your-tiktok-profile-essentials-for-authenticity/"><u>[New] In 2024, Upgrade Your TikTok Profile  Essentials for Authenticity</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-professional-tips-for-editing-and-refining-instagram-videos/"><u>[Updated] In 2024, Professional Tips for Editing and Refining Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-file-transfers-in-battlenet-windows/"><u>Mastering Fast File Transfers in Battle.net Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-taskbar-size-tweaks/"><u>Mastering Windows 11 Taskbar Size Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-permission-restrictions-and-open-hidden-folders/"><u>How to Disable Permission Restrictions and Open Hidden Folders</u></a></li>
<li><a href="https://win11.techidaily.com/faster-booting-window-11s-boot-delay-adjustment-explained/"><u>Faster Booting: Window 11'S Boot Delay Adjustment Explained</u></a></li>
</ul></div>

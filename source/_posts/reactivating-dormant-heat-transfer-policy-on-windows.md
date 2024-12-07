---
title: Reactivating Dormant Heat Transfer Policy on Windows
date: 2024-12-05T22:38:19.563Z
updated: 2024-12-07T06:59:39.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Dormant Heat Transfer Policy on Windows
excerpt: This Article Describes Reactivating Dormant Heat Transfer Policy on Windows
keywords: WINDOWS HT Policy Reactivation,HT Policy Update Windows,Reviving Windows Thermal Policy,Restarting HT Policy Windows,Dormant Heat Transfer in Windows,Thermal Management Windows Reinitiate,Windows HT Process Renewal
thumbnail: https://thmb.techidaily.com/79265524b64a96a355aa9c66ef040a78b4c61cd77b813b963d28880dc313d729.jpg
---

## Reactivating Dormant Heat Transfer Policy on Windows

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-channel-expansion-at-wallet-friendly-costs/"><u>[New] 2024 Approved Channel Expansion at Wallet-Friendly Costs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-a-comprehensive-list-of-best-skype-recorder-models-for-2024/"><u>[Updated] A Comprehensive List of Best Skype Recorder Models for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/configure-canon-mx870-driver-on-win-xp-to-8-systems/"><u>Configure Canon MX870 Driver on Win XP to 8 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/delineating-differences-comparative-analysis-of-microsoft-and-native-windows-logins/"><u>Delineating Differences: Comparative Analysis of Microsoft & Native Windows Logins</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-realme-c55-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Realme C55 Location Settings | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/from-draft-to-edit-essential-film-techniques-via-youtube/"><u>From Draft to Edit Essential Film Techniques via YouTube</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/hp-unveils-future-growth-tactics-amidst-hybrid-office-boom-driving-up-demand-for-computers-and-quick-start-ink-program/"><u>HP Unveils Future Growth Tactics Amidst Hybrid Office Boom Driving Up Demand for Computers & Quick-Start Ink Program</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-changes-in-windows-11-app-settings/"><u>Navigating Changes in Windows 11 App Settings</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-windows-10-photos-not-your-cup-of-tea-try-these-8-alternatives/"><u>New 2024 Approved Windows 10 Photos Not Your Cup of Tea? Try These 8 Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-code-c0000022-in-microsoft-windows/"><u>Tackling Error Code C0000022 in Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-automatic-power-down-for-idle-windows-systems/"><u>Tailoring Automatic Power-Down for Idle Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-mobile-titles-android-in-windows-11-and-google-play/"><u>Transitioning Mobile Titles: Android in Windows 11 and Google Play</u></a></li>
</ul></div>


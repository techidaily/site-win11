---
title: Repairing Dormant Thermal Regulation Protocol in Windows
date: 2024-09-11T16:20:05.370Z
updated: 2024-09-16T16:22:02.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Repairing Dormant Thermal Regulation Protocol in Windows
excerpt: This Article Describes Repairing Dormant Thermal Regulation Protocol in Windows
keywords: Thermal Control Fix,Windows Heat Repair,Regulate Temp Proto,Thermal Reg System,Dormant Heat Fixing,Windows Thermal Reset,Temp Protocol Restore
thumbnail: https://thmb.techidaily.com/0ab25ce0bb8d4ab2078e845cda986fa9a30d3de551640bc5deeb7f8730f9ba76.jpg
---

## Repairing Dormant Thermal Regulation Protocol in Windows

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

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
<li><a href="https://extra-guidance.techidaily.com/new-mastering-multitask-media-consumption-harnessing-pip-feature-in-netflix/"><u>[New] Mastering Multitask Media Consumption Harnessing PIP Feature in Netflix</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-charting-the-course-to-prodigy-status-for-ajey-carryminati/"><u>[Updated] In 2024, Charting the Course to Prodigy Status for Ajey (CarryMinati)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-integrated-marketing-campaigns-for-brand-and-video-platforms/"><u>[Updated] Integrated Marketing Campaigns for Brand and Video Platforms</u></a></li>
<li><a href="https://fox-direct.techidaily.com/5-best-sd-card-for-gopro-cameras-hero-87-included/"><u>5 Best SD Card for GoPro Cameras - Hero 8/7 Included</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-oneplus-nord-n30-se-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your OnePlus Nord N30 SE</u></a></li>
<li><a href="https://win11.techidaily.com/debate-time-which-is-more-user-friendly-chocolatey-or-wm/"><u>Debate Time: Which Is More User-Friendly, Chocolatey or WM?</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-charge-notifications-in-win-1011/"><u>Fine-Tuning Charge Notifications in Win 10/11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-realme-12-proplus-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Realme 12 Pro+ 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-itel-p55plus-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Itel P55+ to Outlook | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-unleash-funimate-with-apk-on-your-phone/"><u>In 2024, How to Unleash Funimate with APK on Your Phone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-ringtones-for-pixels-where-to-download/"><u>In 2024, Top Ringtones for Pixels Where to Download?</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-to-upgrade-mouses-double-tap-velocity/"><u>Quick Tips to Upgrade Mouse’s Double-Tap Velocity</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-error-sevenzeronine/"><u>Tackling Windows Error SevenZeroNine</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-strategies-for-powerful-windows-file-navigation/"><u>Ultimate Strategies for Powerful Windows File Navigation</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-root-cause-of-file-creation-problem-error-30005/"><u>Understanding the Root Cause of File Creation Problem - Error 30005</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


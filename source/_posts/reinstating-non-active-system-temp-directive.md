---
title: Reinstating Non-Active System Temp Directive
date: 2024-10-14T21:00:02.631Z
updated: 2024-10-15T21:20:57.414Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Non-Active System Temp Directive
excerpt: This Article Describes Reinstating Non-Active System Temp Directive
keywords: Non-Active Systems Directive,System Temp Revise,Directive Reinstate,Active System Temp Fix,Temperature Management,System Update Protocol,Directive Compliance
thumbnail: https://thmb.techidaily.com/a55de6d667ce151e4f6994d9b6a4777fce149eccc985ca7253a27ff290bf8c11.jpg
---

## Reinstating Non-Active System Temp Directive

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-15-best-sites-to-find-and-download-royalty-free-music-for-youtube/"><u>[New] 2024 Approved 15 Best Sites to Find & Download Royalty-Free Music for YouTube</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-a-thorough-examination-adobe-lightroom-for-android-users-for-2024/"><u>[New] A Thorough Examination Adobe Lightroom for Android Users for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-legal-and-ethical-methods-boosting-your-tiktok-profile/"><u>[Updated] Legal and Ethical Methods Boosting Your TikTok Profile</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-clip-connoisseurs-essential-list-of-retro-vhs-effects/"><u>2024 Approved The Clip Connoisseur's Essential List of Retro VHS Effects</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cloud-economy-in-review-comparative-analysis-2024/"><u>Cloud Economy in Review Comparative Analysis 2024</u></a></li>
<li><a href="https://win11.techidaily.com/delineating-differences-comparative-analysis-of-microsoft-and-native-windows-logins/"><u>Delineating Differences: Comparative Analysis of Microsoft & Native Windows Logins</u></a></li>
<li><a href="https://win11.techidaily.com/enlarge-pin-gallery-in-windows-11-ui/"><u>Enlarge Pin Gallery in Windows 11 UI</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-auditory-gamespace-vaults-copyright-free-for-2024/"><u>Free Auditory Gamespace Vaults (Copyright-Free) for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-apple-iphone-11-pro-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For Apple iPhone 11 Pro Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-errored-photo-transfers-from-iphones/"><u>Mastering the Art of Correcting Errored Photo Transfers From iPhones</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-changes-in-windows-11-app-settings/"><u>Navigating Changes in Windows 11 App Settings</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-data-protection-with-controlled-access-settings/"><u>Optimize Data Protection with Controlled Access Settings</u></a></li>
<li><a href="https://android-frp.techidaily.com/space-saver-computing-essentials-fanless-intel-n100-windows-11-with-16gb-ram-and-fast-emmc-storage/"><u>Space-Saver Computing Essentials: Fanless Intel N100, Windows 11 with 16GB RAM and Fast eMMC Storage</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-mobile-titles-android-in-windows-11-and-google-play/"><u>Transitioning Mobile Titles: Android in Windows 11 and Google Play</u></a></li>
</ul></div>


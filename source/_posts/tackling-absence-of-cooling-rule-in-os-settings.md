---
title: Tackling Absence of Cooling Rule in OS Settings
date: 2024-09-19T16:25:53.260Z
updated: 2024-09-22T09:46:34.787Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Absence of Cooling Rule in OS Settings
excerpt: This Article Describes Tackling Absence of Cooling Rule in OS Settings
keywords: Cooling System OS,OS Temperature Regulation,Overheat Prevention OS,OS Config Cooling,Heat Management OS,OS Thermal Settings,Cooling Rule OS Compliance
thumbnail: https://thmb.techidaily.com/0a9719ddcbae5c52ddb9477f8674bda6f7443fbaaf23c9836dcb573723ce4b8e.jpg
---

## Tackling Absence of Cooling Rule in OS Settings

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
<li><a href="https://extra-hints.techidaily.com/new-campaign-tactics-for-enhancing-health-awareness/"><u>[New] Campaign Tactics for Enhancing Health Awareness</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-professional-gamers-showcase-live-recording-in-obs/"><u>[Updated] Professional Gamers Showcase - Live Recording in OBS</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-step-by-step-to-superior-image-clarity-by-removing-backgrounds-using-affinity/"><u>[Updated] Step-by-Step to Superior Image Clarity by Removing Backgrounds Using Affinity</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-enhance-your-media-experience-mastering-hdr-videos-with-windows/"><u>2024 Approved Enhance Your Media Experience Mastering HDR Videos with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/no1-7/"><u>人気No.1! ストリーミングオーディオ・レコーディング専用ソフト、詳しく見てみませんか（7つ選び）</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ditch-costly-reimaginations-create-personalized-editions-using-game-mods/"><u>Ditch Costly Reimaginations: Create Personalized Editions Using Game Mods</u></a></li>
<li><a href="https://video-capture.techidaily.com/1726026765741-dvd/"><u>DVD 地帯識別符号を克服して自由に映像再生する方法</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sharpen-your-scopes-essential-close-up-techniques-for-mines/"><u>In 2024, Sharpen Your Scopes Essential Close-Up Techniques for Mines</u></a></li>
<li><a href="https://win11.techidaily.com/manage-your-documents-with-confidence-using-wonderfoxs-top-notch-pdf-organizer-suite/"><u>Manage Your Documents with Confidence Using WonderFox's Top-Notch PDF Organizer Suite</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-powerpoint-multimedia-seamless-tutorial-on-adding-mp4-files-perfectly/"><u>Mastering PowerPoint Multimedia: Seamless Tutorial on Adding MP4 Files Perfectly</u></a></li>
<li><a href="https://win11.techidaily.com/mp4wmawindows-1011/"><u>MP4とWMAの間で素早く変換:Windows 10/11ユーザー向け方法</u></a></li>
<li><a href="https://extra-tips.techidaily.com/price-tracker-for-cloud-space-services-a-detailed-review/"><u>Price Tracker for Cloud Space Services A Detailed Review</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-mp3-conversion-transferring-your-cherished-tunes-with-ease/"><u>Seamless MP3 Conversion - Transferring Your Cherished Tunes with Ease</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


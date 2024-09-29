---
title: Tackling Absence of Cooling Rule in OS Settings
date: 2024-09-24T18:50:38.018Z
updated: 2024-09-28T23:19:46.852Z
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-bebops-avian-acrobatics-a-parrot-revelation/"><u>[Updated] 2024 Approved Bebop's Avian Acrobatics – A Parrot Revelation</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-create-awe-inspiring-gopro-time-lapse-cinematography/"><u>[Updated] Create Awe-Inspiring GoPro Time-Lapse Cinematography</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-leading-economical-screen-snapper-kit/"><u>[Updated] Leading Economical Screen Snapper Kit</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhanced-site-insights-through-cookiebot-integration/"><u>Enhanced Site Insights Through Cookiebot Integration</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-deskjet-3050-printer-driver-download-for-windows/"><u>HP Deskjet 3050 Printer Driver Download for Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-comprehensive-guide-to-applying-and-customizing-filters-in-video-editing/"><u>In 2024, Comprehensive Guide to Applying and Customizing Filters in Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-xiaomi-civi-3-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Xiaomi Civi 3 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-hidden-gems-unlocking-full-potential/"><u>Windows 11'S Hidden Gems: Unlocking Full Potential</u></a></li>
</ul></div>


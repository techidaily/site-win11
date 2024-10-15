---
title: Overhauling Deactivated Thermal Control on WinPC
date: 2024-10-14T20:22:31.844Z
updated: 2024-10-15T16:02:35.861Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overhauling Deactivated Thermal Control on WinPC
excerpt: This Article Describes Overhauling Deactivated Thermal Control on WinPC
keywords: PC Thermal Fix,WinPC Heat Revamp,Thermal WinControl,Deactivate TC Overhaul,Windows Thermal Repair,PC Thermal Control Update,WinPC Temp Management
thumbnail: https://thmb.techidaily.com/59ebf54bbd2728b1cee67f80e126289c9f6737977aace37b8f0906719738cd6b.jpg
---

## Overhauling Deactivated Thermal Control on WinPC

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
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541">
  <img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-quick-steps-to-proficient-gif-design/"><u>[New] Quick Steps to Proficient GIF Design</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-maximize-reach-essential-youtube-seo-tools-unlocked/"><u>[Updated] 2024 Approved Maximize Reach Essential YouTube SEO Tools Unlocked</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-embark-on-a-google-meet-journey/"><u>[Updated] Embark on a Google Meet Journey</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-harnessing-lut-power-for-free-high-quality-colorization-for-2024/"><u>[Updated] Harnessing LUT Power for Free, High-Quality Colorization for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-quick-content-in-a-facebook-frame/"><u>[Updated] In 2024, Quick Content in a Facebook Frame</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-demystifying-screen-recording-insights-from-showmore-experts/"><u>2024 Approved Demystifying Screen Recording Insights From ShowMore Experts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/android-users-learn-how-to-enable-voice-control-with-chatgpts-alternate-voicegpt/"><u>Android Users, Learn How to Enable Voice Control with ChatGPT's Alternate - VoiceGPT</u></a></li>
<li><a href="https://win11.techidaily.com/fundamental-insights-into-windows-snoozer-functionality/"><u>Fundamental Insights Into Window's Snoozer Functionality</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ultimate-guide-to-free-pptp-vpn-for-beginners-on-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Free PPTP VPN For Beginners On Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-devices-name-conflicts-with-ease-windows-guide/"><u>Navigate Through Devices Name Conflicts with Ease (Windows Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-dropbox-performance-lessening-cpu-overuse-in-windows/"><u>Optimizing Dropbox Performance: Lessening CPU Overuse in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-windows-11-app-opening/"><u>Turbocharge Windows 11 App Opening</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-video-reversal-made-simple-a-beginners-guide-to-final-cut-pro/"><u>Updated In 2024, Video Reversal Made Simple A Beginners Guide to Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-examining-their-unique-traits/"><u>Windows Terminal and PowerShell: Examining Their Unique Traits</u></a></li>
</ul></div>


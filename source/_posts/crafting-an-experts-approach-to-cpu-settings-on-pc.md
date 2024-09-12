---
title: Crafting an Expert's Approach to CPU Settings on PC
date: 2024-09-11T09:38:57.707Z
updated: 2024-09-12T09:38:57.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting an Expert's Approach to CPU Settings on PC
excerpt: This Article Describes Crafting an Expert's Approach to CPU Settings on PC
keywords: Expert PC CPU Tuning,Masterful CPU Configuration,Professional PC Optimization,Skilled CPU Adjustment,Top PC Settings Guide,Proficient CPU Setup,Elite PC Performance Tips
thumbnail: https://thmb.techidaily.com/445d6c97ace4ef05d63cde4f33374d4b0783e76d1e91d61e1ddb527be75674b2.jpg
---

## Crafting an Expert's Approach to CPU Settings on PC

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118304/7443" target="_top" id="2118304">
  <img src="//a.impactradius-go.com/display-ad/7443-2118304" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118304/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-composing-an-emotive-tiktok-finale-statement/"><u>[New] 2024 Approved Composing An Emotive TikTok Finale Statement</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-stepwise-instructions-snapchat-for-mac-users/"><u>[New] 2024 Approved Stepwise Instructions Snapchat for Mac Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-a-step-by-step-breakdown-creating-your-best-yt-shorts/"><u>[New] A Step-by-Step Breakdown Creating Your Best YT Shorts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-the-ultimate-guide-to-pre-recorded-yoga-on-youtube/"><u>[New] In 2024, The Ultimate Guide to Pre-Recorded Yoga on YouTube</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-microphone-data-review-tips/"><u>[Updated] In 2024, Microphone Data Review Tips</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-innovative-ways-to-use-your-webcam-for-2024/"><u>[Updated] Innovative Ways to Use Your Webcam for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-x-fold-2-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo X Fold 2</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-warzone-wonders-your-a-list-of-top-7-fps-adventures/"><u>2024 Approved Warzone Wonders - Your A-List of Top 7 FPS Adventures</u></a></li>
<li><a href="https://extra-resources.techidaily.com/charting-the-course-for-unmatched-cloud-storage/"><u>Charting the Course for Unmatched Cloud Storage</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-addressing-windows-error-code-0xc0000001/"><u>Decoding and Addressing Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-taskbar-add-capslock-and-numlock-icons-on-win11/"><u>Enhance Taskbar: Add CapsLock & NumLock Icons on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-cracking-credential-vault-code/"><u>Expert Tips: Cracking Credential Vault Code</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-explorer-extraordinaire-unlocking-the-sixest-techniques-for-windows-11-path-duplication/"><u>Exploring Explorer Extraordinaire: Unlocking the Sixest Techniques for Windows 11 Path Duplication</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vmware-blue-screen-errors-on-windows-11/"><u>Fixing VMware Blue Screen Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/future-forward-workspace-microsoft-adds-ai-to-windows-11-boosting-productivity/"><u>Future-Forward Workspace: Microsoft Adds AI to Windows 11, Boosting Productivity</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-add-motion-blur-to-face-with-picsart/"><u>How to Add Motion Blur to Face with Picsart</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-build-a-successful-career-in-ai-prompt-design-and-stability-forecast/"><u>How to Build a Successful Career in AI Prompt Design and Stability Forecast</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enforce-windows-default-screensaver-settings/"><u>How to Enforce Windows Default Screensaver Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-keyboard-shortcuts-activating-while-typing/"><u>How to Fix Windows Keyboard Shortcuts Activating While Typing</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-oppo-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Oppo Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-15-pro-max-video-to-computer-drfone-by-drfone-ios/"><u>How to Stream Apple iPhone 15 Pro Max Video to Computer? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-itel-a60s-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Itel A60s Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-and-fix-frozen-screensaver-on-pc/"><u>How to Unlock and Fix Frozen Screensaver on PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-iphone-11-how-to-unlock-a-disabled-iphone-11-by-drfone-ios/"><u>In 2024, Disabled iPhone 11 How to Unlock a Disabled iPhone 11?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-8-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-savvy-saving-with-20-best-free-storage-services-up-to-1tb/"><u>In 2024, Savvy Saving with 20 Best Free Storage Services, Up To 1TB</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-ultimate-text-effect-strategies/"><u>In 2024, Ultimate Text Effect Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-detach-onedrive-from-msid-the-microsoft-identity-on-windows/"><u>Learn to Detach OneDrive From MSID, the Microsoft Identity on WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-passwords-essential-guide-to-unlocking-credential-manager/"><u>Master Your Windows Passwords: Essential Guide to Unlocking Credential Manager</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-new-widget-chooser-in-microsoft-windows-11/"><u>Mastering New Widget Chooser in Microsoft Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-proxy-configurations/"><u>Mastering Windows 11 Proxy Configurations</u></a></li>
<li><a href="https://buynow-help.techidaily.com/mastery-in-your-hands-the-ultimate-xp-pen-artist-16-pro-digital-brushboard-review/"><u>Mastery in Your Hands: The Ultimate XP-Pen Artist 16 Pro Digital Brushboard Review</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsoft-offices-error-0x80041015/"><u>Navigating Through Microsoft Office's Error 0X80041015</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-mouse-settings-to-enhance-accessibility-in-windows-11/"><u>Navigating Through Mouse Settings to Enhance Accessibility in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-past-wired-network-limit-overcome-windows-100mbps-capping/"><u>Pushing Past Wired Network Limit: Overcome Windows' 100Mbps Capping</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-ps4-controllers-ultimate-fixes-for-non-charging-problems/"><u>Revive Your PS4 Controllers! Ultimate Fixes for Non-Charging Problems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-file-merging-techniques-for-modern-windows-users/"><u>Seamless File Merging Techniques for Modern Windows Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/1722999465504-steam-vr-detection-problems-try-these-6-tricks-to-get-it-working/"><u>Steam VR Detection Problems? Try These 6 Tricks to Get It Working</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-reset-tutorial-for-your-pc-graphics-driver/"><u>Step-by-Step Reset Tutorial for Your PC Graphics Driver</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-the-world-of-command-line-alias-names/"><u>Tapping Into the World of Command Line Alias Names</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ltimate-comparison-of-gif-creators/"><u>The Ultimate Comparison of GIF Creators</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-resolve-iphone-images-not-uploading-on-windows-system/"><u>Tips to Resolve iPhone Images Not Uploading on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-portable-windows-platforms/"><u>Top 4 Portable Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-to-utilizing-hdr-on-windows-11-systems/"><u>Ultimate Guide to Utilizing HDR on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-access-adobe-ps-not-opening-in-latest-windows/"><u>Unblocking Access: Adobe PS Not Opening in Latest Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-windows-methodology-to-split-audiosystems/"><u>Unpacking Windows’ Methodology to Split Audiosystems</u></a></li>
<li><a href="https://win11.techidaily.com/whats-delayed-immortals-fenyx-rising-release-solved/"><u>What's Delayed: Immortals Fenyx Rising Release Solved</u></a></li>
<li><a href="https://win11.techidaily.com/win-users-picks-optimal-torrent-tools/"><u>Win Users' Picks: Optimal Torrent Tools</u></a></li>
<li><a href="https://win11.techidaily.com/workarounds-for-fixed-energy-mode-switches-in-win11/"><u>Workarounds for Fixed Energy Mode Switches in Win11</u></a></li>
</ul></div>


---
title: Switching From Modern Search Bar Design Back to Icons in Win11
date: 2024-10-19T08:15:32.483Z
updated: 2024-10-21T03:33:38.871Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switching From Modern Search Bar Design Back to Icons in Win11
excerpt: This Article Describes Switching From Modern Search Bar Design Back to Icons in Win11
keywords: Win11 Icon Switch,Icons Over Search Bar,Revive Classic Windows,Win11 Visual Upgrade,Modern UI Shift,Replace Search Bar Icons,New Win11 Interface
thumbnail: https://thmb.techidaily.com/9a1d2889cbe4ad14880fa77a388cff944d010380f4cf0a1f83bd01829ce96a1e.jpg
---

## Switching From Modern Search Bar Design Back to Icons in Win11

 Windows 11 is still an evolving platform, so users may notice changes in their UI as time goes on. Some of these changes aren't always appreciated, and you may have noticed that your taskbar search icon has become a search bar.

 If so, read on. Here's how to revert the Windows 11 search bar to a search icon.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Happened to the Windows 11 Taskbar Search Icon?

![screenshot of the new taskbar search icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/screenshot_of_new_search_taskbar_icon.jpg)

 If you're keeping Windows 11 updated, you would have had your taskbar search icon change over to a larger bar-shaped icon.

 This change happened automatically and, as of the time of writing, cannot be changed through the settings menu.

 Thankfully, there's a catch-all solution to many of these design changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043855/7443" target="_top" id="2043855">
  <img src="//a.impactradius-go.com/display-ad/7443-2043855" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043855/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Restoring Features with ViVeTool

![screenshot of ViVeTool in system 32](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/screenshot_of_vivetool_in_system_32.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 ViVeTool is what we'll be using to change this feature back, and it can be found on the[GitHub page for ViVeTool](https://github.com/thebookisclosed/ViVe/releases/tag/v0.3.2) . In order to properly use this program, it needs to be extracted into the right location: System32.

 Make sure you read up on[System32 and how important it is for your system before you proceed](https://www.makeuseof.com/tag/windows-system32/) . ViVeTool is a safe program, but it's good to know what you're doing before you jump in.

 When you're ready, extract the downloaded ZIP for ViVeTool into your System32 folder.

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Restore the Windows 11 Search Bar Icon

![screenshot of the quick command menu opening windows terminal in admin mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/screenshot_of_quick_command_windows_terminal_admin.jpg)

<!-- affiliate ads begin -->
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Begin by launching an admin-level terminal window. To do this, right-click on the start menu icon, and hit**Windows Terminal - Admin** . Make sure you click**Yes** to the User Account Control window.

Next, input the following code into the terminal window:

`vivetool /disable /id:39263329`

 You'll know it's successful if you see the message**Successfully set feature configurations** .

 Then, all you have to do is restart. Your search icon should return to its original style.

## Features Change, Even if You Don’t Want Them To

 At the end of the day, this might very well be a temporary fix. Microsoft could include a toggle in the future, or add in further changes that break the functionality of this tool.

 While that might be annoying, as long as there are people using Windows, there will be people making modifications such as ViVeTool to give control back to the user.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-the-techno-conductors-playbook-mastering-windows-pc-for-capturing-live-broadcasts/"><u>[New] 2024 Approved The Techno Conductor's Playbook Mastering Windows PC for Capturing Live Broadcasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leverage-free-luts-to-upgrade-your-obs-video-production-quality/"><u>[New] Leverage Free LUTs to Upgrade Your OBS Video Production Quality</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-youtube-movie-maker-unleashed-creative-possibilities-explored/"><u>[New] YouTube Movie Maker Unleashed Creative Possibilities Explored</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-laptop-and-mobile-commencing-a-google-meet-session/"><u>[Updated] Laptop & Mobile Commencing a Google Meet Session</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-principles-of-documentary-storytelling/"><u>[Updated] Principles of Documentary Storytelling</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-top-5-under-100-gaming-keyboards-your-next-purchase-for-2024/"><u>[Updated] Top 5 Under-$100 Gaming Keyboards – Your Next Purchase for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Addressing High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/assessing-the-effectiveness-of-western-digital-data-lifeguard-for-hard-drive-health-checks/"><u>Assessing the Effectiveness of Western Digital Data LifeGuard for Hard Drive Health Checks</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-print-on-edge-security-mode-windows-11/"><u>Enabling Print on Edge Security Mode Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-functionality-of-component-services-utility-in-windows/"><u>Exploring the Functionality of Component Services Utility in Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-frame-rate-drop-in-dying-light-how-gamers-overcame-fps-problems/"><u>Fixing the Frame Rate Drop in Dying Light - How Gamers Overcame FPS Problems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-xiaomi-redmi-k70-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Xiaomi Redmi K70?</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
</ul></div>


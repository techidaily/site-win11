---
title: Guide to Window 11 Custom Taskbar Sizing
date: 2024-08-16T00:32:24.244Z
updated: 2024-08-17T00:32:24.244Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Window 11 Custom Taskbar Sizing
excerpt: This Article Describes Guide to Window 11 Custom Taskbar Sizing
keywords: Windows 11 Bar Size Guide,Adjust Taskbar Dimensions W11,Taskbar Resize Tutorial W11,Custom Taskbar Setting Window11,W11 Taskbar Sizing Configuration,Mastering Taskbar Space in Windows 11,Personalize W11 Taskbar Size
thumbnail: https://thmb.techidaily.com/da3a565149456b725f254b5d80c3b1f1c06d74a5fc993d32dbb395957f6fba49.jpg
---

## Guide to Window 11 Custom Taskbar Sizing

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and [how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-channel-finale-101-insider-tricks-for-successful-outros/"><u>[Updated] 2024 Approved  Channel Finale 101  Insider Tricks for Successful Outros</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-end-of-struggle-operational-obs-camera-for-2024/"><u>[Updated] End of Struggle  Operational OBS Camera for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-unshackling-from-tiktoks-covert-bans-for-2024/"><u>[Updated] Unshackling From TikTok's Covert Bans for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-navigating-youtube-sharing-with-google-credentials/"><u>2024 Approved  Navigating YouTube Sharing with Google Credentials</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-solo-stream-triumph-strategies-for-clear-consistent-broadcasts/"><u>2024 Approved  Solo Stream Triumph  Strategies for Clear, Consistent Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-the-search-function-in-windows-11-for-you/"><u>Adapting the Search Function in Windows 11 for You</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-uncertainty-check-cpu-generation-on-windows-8-ways/"><u>Avoid Uncertainty – Check CPU Generation on Windows (8 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/boost-quality-with-these-5-free-windows-editors/"><u>Boost Quality with These 5 FREE Windows Editors</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-re-establishing-managed-status-on-windows-11/"><u>Comprehensive Guide for Re-Establishing Managed Status on Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/comprehensive-solutions-for-thaumaturge-stability-issues-on-pcs/"><u>Comprehensive Solutions for Thaumaturge Stability Issues on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-technologies-in-microsofts-ai-hub/"><u>Demystifying the Technologies in Microsoft's AI Hub</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-reliable-voice-commands-for-valorant-gaming/"><u>Ensuring Reliable Voice Commands for Valorant Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-requires-privilege-error-code-0x80070522-in-windows-devices/"><u>Eradicating Requires Privilege Error (Code 0X80070522) in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-reopen-stuck-adobe-photoshop-in-windows/"><u>Guidelines to Reopen Stuck Adobe Photoshop in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-gallery-in-file-explorer-in-windows-11/"><u>How to Enable the Gallery in File Explorer in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-dedicated-video-ram-vram-in-windows-11-and-11/"><u>How to Increase Dedicated Video RAM (VRAM) in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-pcs-current-window-background-file/"><u>How to Locate PC's Current Window Background File</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-se-2020-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone SE (2020) without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sound-sleuths-unite-free-beats-tracking-tools/"><u>In 2024, Sound Sleuths Unite! Free Beats-Tracking Tools</u></a></li>
<li><a href="https://win11.techidaily.com/leading-edge-lives-beyond-windows-11-expectations/"><u>Leading-Edge Lives: Beyond Windows 11 Expectations</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-the-easy-ways-to-turn-your-watching-experience-on-youtube-into-a-screencast-without-money/"><u>Learn the Easy Ways to Turn Your Watching Experience on YouTube Into a Screencast Without Money</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-boot-failures-8-fixes-for-virtual-machines-on-wm11os/"><u>Overcome Boot Failures: 8 Fixes for Virtual Machines on WM11OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-windows-laptop-lag-on-dual-screens/"><u>Overcoming the Hurdle of Window's Laptop Lag on Dual Screens</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-reviving-windows-or-beyond/"><u>Rethink Reviving: Windows or Beyond?</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-non-functional-email-banners-for-office-users/"><u>Reviving Non-Functional Email Banners for Office Users</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-to-correcting-kernel3edll-file-problems-in-windows/"><u>Step-by-Step Guide to Correcting Kernel3e.dll File Problems in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-bypassing-hiccups-and-blockades/"><u>Streamlining Windows 11: Bypassing Hiccups & Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-your-digital-sketchpad-launching-ms-paint-on-win11/"><u>Unveiling Your Digital Sketchpad: Launching MS Paint on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-best-cryptographic-solutions-ranked-148-chars/"><u>Window's Best Cryptographic Solutions Ranked (148 Chars)</u></a></li>
</ul></div>

---
title: Customizing Taskbar Spacing on Windows 11
date: 2024-08-28T00:53:39.505Z
updated: 2024-08-29T00:53:39.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Taskbar Spacing on Windows 11
excerpt: This Article Describes Customizing Taskbar Spacing on Windows 11
keywords: WinTaskbarAdjustment,SpaceBarTaskConfig,TaskbarCustomizeWin,WindowSpacingTaskbar,AdjustTaskBarWindows,CustomTaskbarSpacing,Windows11TaskBarSpace
thumbnail: https://thmb.techidaily.com/d6473782f31868e794fc3ab8460fc67b139be82f000417effd74e9124ff9dff3.jpg
---

## Customizing Taskbar Spacing on Windows 11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-youtube-titanics-1-8-vids-of-note/"><u>[New] 2024 Approved  YouTube Titanics  #1-#8 Vids of Note</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-advanced-capture-strategies-for-roblox-games-mac-edition-for-2024/"><u>[New] Advanced Capture Strategies for Roblox Games (Mac Edition) for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-captivate-viewers-adding-animation-to-instagram-text/"><u>[New] Captivate Viewers  Adding Animation to Instagram Text</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-decoding-the-essence-of-asmr-videos/"><u>[Updated] 2024 Approved  Decoding the Essence of ASMR Videos</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-iphone-13-pro-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your iPhone 13 Pro for Free</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-free-video-merger-software-without-watermarks/"><u>Best Free Video Merger Software Without Watermarks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-realme-12-proplus-5g-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Realme 12 Pro+ 5G</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-kali-a-windows-users-guide/"><u>Dive Into Kali: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-flicker-in-windows-os-a-step-by-step-guide/"><u>Eliminating Flicker in Windows OS: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-unsupported-windows-hello-scanner-mismatch/"><u>Eliminating the Unsupported Windows Hello Scanner Mismatch</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-isdonedll-problem-steps/"><u>Eliminating Windows 11'S ISDone.dll Problem Steps</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-fullscreen-experience-tackling-windows-overscan/"><u>Enhance Fullscreen Experience: Tackling Windows Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-fixing-failed-windows-mmc-creations/"><u>Expert Guide to Fixing Failed Windows MMC Creations</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-insignia-usbvga-driver-installed-step-by-step-guide/"><u>Get Your Insignia USB/VGA Driver Installed - Step by Step Guide!</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-ctrl-key-malfunction-fixes-on-win11/"><u>Guiding You Through Ctrl Key Malfunction Fixes on Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-enable-usb-debugging-on-a-locked-vivo-y27-4g-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Vivo Y27 4G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-xbox-game-update-issues-on-pc/"><u>How to Solve Xbox Game Update Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-windows-update-interruptions/"><u>How to Turn Off Windows Update Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/improve-visual-identification-displaying-this-pc-icon/"><u>Improve Visual Identification: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-ideal-mac-screenshot-guide-5-streamlined-and-effective-methods/"><u>In 2024, Ideal Mac Screenshot Guide  5 Streamlined and Effective Methods</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-leveraging-data-key-performance-indicators-for-igtv-videos/"><u>In 2024, Leveraging Data  Key Performance Indicators for IGTV Videos</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-controller-compatibility-steams-essential-guide/"><u>Master Controller Compatibility: Steam's Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-zero-error-guidance-to-resolve-windows-11-store-glitches/"><u>Mastery over Zero-Error: Guidance to Resolve Windows 11 Store Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/off-the-cuff-tricks-to-work-with-onedrive-locally/"><u>Off-the-Cuff Tricks to Work with OneDrive Locally</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-multiscreen-woes-in-windows/"><u>Overcoming Multiscreen Woes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-regain-lost-connection-on-windows/"><u>Protocols to Regain Lost Connection on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-adding-dolby-atmos-in-win-11-pro/"><u>Quick Steps for Adding Dolby Atmos in Win 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-your-intel-unison-problems-with-these-steps/"><u>Resolve Your Intel Unison Problems with These Steps</u></a></li>
<li><a href="https://win11.techidaily.com/rethinking-user-authorization-on-windows-systems/"><u>Rethinking User Authorization on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/securing-write-rights-to-steam-directories-with-windows-11/"><u>Securing Write Rights to Steam Directories with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-joining-onedrive-with-liveid-windows/"><u>The Ultimate Guide: Joining OneDrive with LiveID (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-11-whiz-11-common-problems-solutions-revealed/"><u>The Windows 11 Whiz: 11 Common Problems, Solutions Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-typing-lag-seven-effective-fixes-for-win-os/"><u>Win over Typing Lag: Seven Effective Fixes for WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-trick-showhide-user-defined-directories/"><u>Windows 11 Trick: Show/Hide User-Defined Directories</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-weather-wisdom-best-forecasting-tools-roundup/"><u>Windows 11 Weather Wisdom: Best Forecasting Tools Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-gameplay-steps-to-recover-disconnected-league/"><u>Winning Back Gameplay: Steps to Recover Disconnected League</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
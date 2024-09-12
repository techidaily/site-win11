---
title: Enlivening the Inactive Wastebin in Windows 11
date: 2024-09-11T09:45:14.077Z
updated: 2024-09-12T09:45:14.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enlivening the Inactive Wastebin in Windows 11
excerpt: This Article Describes Enlivening the Inactive Wastebin in Windows 11
keywords: Wastebin Activation,Bin Revival Win11,Enliven Bin Windows,Windows Bin Life,Reactivate Wastebin,Bin Rejuvenate Win11,Win11 Bin Boost
thumbnail: https://thmb.techidaily.com/a4a765e99a54a380752423d8d88b32966a3339aa9293b1bce2b9a95dc690dd25.jpg
---

## Enlivening the Inactive Wastebin in Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121335/18498" target="_top" id="2121335">
  <img src="//a.impactradius-go.com/display-ad/18498-2121335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121335/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-a-step-by-step-journey-through-high-impact-youtube-banner-designs-for-2024/"><u>[New] A Step-by-Step Journey Through High-Impact YouTube Banner Designs for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-asmr-unveiled-benefits-for-your-well-being-for-2024/"><u>[New] ASMR Unveiled Benefits for Your Well-Being for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/hannel-prominence-mastery-a-comprehensive-youtube-guide/"><u>[New] Channel Prominence Mastery A Comprehensive YouTube Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nhancing-comments-with-emojis-on-youtube-for-2024/"><u>[New] Enhancing Comments with Emojis on YouTube for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-top-notch-hacks-navigating-instagrams-forgotten-features/"><u>[Updated] 2024 Approved Top-Notch Hacks Navigating Instagram's Forgotten Features</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-beginners-walkthrough-setting-up-vrecord-software/"><u>[Updated] In 2024, Beginner’s Walkthrough Setting Up VRecord Software</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-unveiling-effective-metaverse-engagement-tactics-for-2024/"><u>[Updated] Unveiling Effective Metaverse Engagement Tactics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-addressing-windows-error-code-0xc0000001/"><u>Decoding and Addressing Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-taskbar-add-capslock-and-numlock-icons-on-win11/"><u>Enhance Taskbar: Add CapsLock & NumLock Icons on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-functional-status-of-windows-event-viewer/"><u>Ensuring Functional Status of Windows Event Viewer</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/ensuring-smooth-streaming-solutions-for-fb-livestream-problems/"><u>Ensuring Smooth Streaming Solutions for FB Livestream Problems</u></a></li>
<li><a href="https://win11.techidaily.com/experience-freed-digital-conversations-winstyle/"><u>Experience Freed Digital Conversations, WinStyle</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-cracking-credential-vault-code/"><u>Expert Tips: Cracking Credential Vault Code</u></a></li>
<li><a href="https://technical-tips.techidaily.com/explore-immersive-escape-puzzles-on-iphones-and-ipads-a-fresh-take-after-the-room-and-myst/"><u>Explore Immersive Escape Puzzles on iPhones and iPads – A Fresh Take After The Room and Myst</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-explorer-extraordinaire-unlocking-the-sixest-techniques-for-windows-11-path-duplication/"><u>Exploring Explorer Extraordinaire: Unlocking the Sixest Techniques for Windows 11 Path Duplication</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vmware-blue-screen-errors-on-windows-11/"><u>Fixing VMware Blue Screen Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/future-forward-workspace-microsoft-adds-ai-to-windows-11-boosting-productivity/"><u>Future-Forward Workspace: Microsoft Adds AI to Windows 11, Boosting Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/guide-how-to-quickly-screenshot-uac-prompts/"><u>Guide: How to Quickly ScreenShot UAC Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enforce-windows-default-screensaver-settings/"><u>How to Enforce Windows Default Screensaver Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-keyboard-shortcuts-activating-while-typing/"><u>How to Fix Windows Keyboard Shortcuts Activating While Typing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-virtual-memory-in-windows-11/"><u>How to Increase Virtual Memory In Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-and-fix-frozen-screensaver-on-pc/"><u>How to Unlock and Fix Frozen Screensaver on PC</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-best-photo-and-video-display-apps-from-xi-to-x/"><u>In 2024, Best Photo & Video Display Apps From XI to X</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-vivo-v29-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Vivo V29 Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-is-it-possible-to-use-miracast-with-apple-iphone-11-drfone-by-drfone-ios/"><u>In 2024, Is it Possible to Use Miracast with Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-infinix-hot-30i-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Infinix Hot 30i for Parents | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/insider-tips-creating-unique-podcast-names/"><u>Insider Tips Creating Unique Podcast Names</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/instructions-on-changing-fb-page-backdrop-for-2024/"><u>Instructions on Changing FB Page Backdrop for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/lava-storm-5g-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Lava Storm 5G Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-detach-onedrive-from-msid-the-microsoft-identity-on-windows/"><u>Learn to Detach OneDrive From MSID, the Microsoft Identity on WINDOWS</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-passwords-essential-guide-to-unlocking-credential-manager/"><u>Master Your Windows Passwords: Essential Guide to Unlocking Credential Manager</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-new-widget-chooser-in-microsoft-windows-11/"><u>Mastering New Widget Chooser in Microsoft Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-steam-stability-overcoming-responsiveness-issues/"><u>Mastering Steam Stability: Overcoming Responsiveness Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-proxy-configurations/"><u>Mastering Windows 11 Proxy Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/minecraft-wi-fi-connectivity-problems-solved-on-pc/"><u>Minecraft Wi-Fi Connectivity Problems, Solved on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-the-dxgi-device-removal-issue/"><u>Mitigating the DXGI Device Removal Issue</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsoft-offices-error-0x80041015/"><u>Navigating Through Microsoft Office's Error 0X80041015</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-mouse-settings-to-enhance-accessibility-in-windows-11/"><u>Navigating Through Mouse Settings to Enhance Accessibility in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/perfecting-the-craft-of-youtube-short-video-making-for-2024/"><u>Perfecting the Craft of YouTube Short Video Making for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/precision-wacom-driver-safe-and-compatible-with-windows-tablets/"><u>Precision Wacom Driver - Safe & Compatible with Windows Tablets</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-past-wired-network-limit-overcome-windows-100mbps-capping/"><u>Pushing Past Wired Network Limit: Overcome Windows' 100Mbps Capping</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-file-merging-techniques-for-modern-windows-users/"><u>Seamless File Merging Techniques for Modern Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-overcoming-package-access-problems-in-ws11ws10/"><u>Step-by-Step Guide to Overcoming Package Access Problems in WS11/WS10</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-reset-tutorial-for-your-pc-graphics-driver/"><u>Step-by-Step Reset Tutorial for Your PC Graphics Driver</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-invalid-profile-error-windows-xpvista7-solution/"><u>Tackling Invalid Profile Error: Windows XP/Vista/7 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-the-world-of-command-line-alias-names/"><u>Tapping Into the World of Command Line Alias Names</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/things-you-must-know-for-screen-mirroring-apple-iphone-6s-drfone-by-drfone-ios/"><u>Things You Must Know for Screen Mirroring Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-resolve-iphone-images-not-uploading-on-windows-system/"><u>Tips to Resolve iPhone Images Not Uploading on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-portable-windows-platforms/"><u>Top 4 Portable Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-to-utilizing-hdr-on-windows-11-systems/"><u>Ultimate Guide to Utilizing HDR on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-access-adobe-ps-not-opening-in-latest-windows/"><u>Unblocking Access: Adobe PS Not Opening in Latest Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-faster-mobile-data-speed-discover-easy-fixes-in-just-10-steps/"><u>Unlocking Faster Mobile Data Speed - Discover Easy Fixes in Just 10 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-windows-methodology-to-split-audiosystems/"><u>Unpacking Windows’ Methodology to Split Audiosystems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-secrets-of-chatgpts-token-threshold-and-beyond-possibilities/"><u>Unveiling the Secrets of ChatGPT's Token Threshold and Beyond Possibilities</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-access-all-matches-free-world-cup-live-streaming-options/"><u>Updated Access All Matches Free World Cup Live Streaming Options</u></a></li>
<li><a href="https://extra-information.techidaily.com/upside-down-visuals-unraveling-instagram-video-confusion/"><u>Upside Down Visuals Unraveling Instagram Video Confusion</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/video-scheduler-internal-error-on-windows-11-solved/"><u>Video Scheduler Internal Error on Windows 11 [Solved]</u></a></li>
<li><a href="https://win11.techidaily.com/whats-delayed-immortals-fenyx-rising-release-solved/"><u>What's Delayed: Immortals Fenyx Rising Release Solved</u></a></li>
<li><a href="https://win11.techidaily.com/win-users-picks-optimal-torrent-tools/"><u>Win Users' Picks: Optimal Torrent Tools</u></a></li>
<li><a href="https://win11.techidaily.com/workarounds-for-fixed-energy-mode-switches-in-win11/"><u>Workarounds for Fixed Energy Mode Switches in Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
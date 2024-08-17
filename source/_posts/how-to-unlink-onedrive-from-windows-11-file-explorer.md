---
title: How To Unlink OneDrive From Windows 11 File Explorer
date: 2024-08-16T00:42:36.751Z
updated: 2024-08-17T00:42:36.751Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Unlink OneDrive From Windows 11 File Explorer
excerpt: This Article Describes How To Unlink OneDrive From Windows 11 File Explorer
keywords: Unlink OneDrive,Remove OneDrive,Disconnect OneDrive,Detach OneDrive,Separate OneDrive,Unhook OneDrive,Sever OneDrive Link
thumbnail: https://thmb.techidaily.com/db3dbeacfdd5ea435b3f8eb406f01646288938a037fe9e28d65cbe9fbebcdbb0.png
---

## How To Unlink OneDrive From Windows 11 File Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-instagram-essential-hashtag-tips/"><u>[New] 2024 Approved  Mastering Instagram  Essential Hashtag Tips</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-spotlight-on-best-selling-ae-plugins-for-instagram-for-2024/"><u>[New] Spotlight on Best-Selling AE Plugins for Instagram for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-desktopmobile-techniques-for-sound-rate-manipulation-in-youtube/"><u>[Updated] Desktop/Mobile Techniques for Sound Rate Manipulation in YouTube</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-fundamentals-of-starting-an-instantaneous-broadcast/"><u>[Updated] The Fundamentals of Starting an Instantaneous Broadcast</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-budget-friendly-pc-video-snippet-creators/"><u>2024 Approved  Budget-Friendly PC Video Snippet Creators</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-frontiers-in-virtuality-industry-analysis/"><u>2024 Approved  Frontiers in Virtuality  Industry Analysis</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-heaviest-airborne-haulers-drone-selection-insights/"><u>2024 Approved  Heaviest Airborne Haulers  Drone Selection Insights</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-master-the-mix-combining-youtube-links-in-stories/"><u>2024 Approved  Master the Mix  Combining YouTube Links in Stories</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-maximizing-tweet-control-15-premier-unfollow-utilities/"><u>2024 Approved  Maximizing Tweet Control  15 Premier Unfollow Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Addressing High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-revamped-widget-picker-in-win11/"><u>Configuring Revamped Widget Picker in Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/earning-equation-finns-financial-frequency/"><u>Earning Equation  Finn's Financial Frequency</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-solid-state-drive-speed-on-windows-via-ssd-fresh/"><u>Elevate Solid State Drive Speed on Windows via SSD Fresh</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-hello-login-fingerprint-failure/"><u>Eliminating Windows Hello Login Fingerprint Failure</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-print-on-edge-security-mode-windows-11/"><u>Enabling Print on Edge Security Mode Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-microcomputers-reviewed/"><u>Essential Windows Microcomputers Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-functionality-of-component-services-utility-in-windows/"><u>Exploring the Functionality of Component Services Utility in Windows</u></a></li>
<li><a href="https://techidaily.com/hard-reset-honor-magic-6-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Honor Magic 6 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-nokia-c110-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Nokia C110 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-slow-printer-on-windows/"><u>How to Fix a Slow Printer on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-instant-restoration-for-missing-snaps/"><u>In 2024, Instant Restoration for Missing Snaps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-oppo-reno-10-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Oppo Reno 10 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-turn-the-screws-right-youtube-video-rotation-for-all-angles/"><u>In 2024, Turn the Screws Right  YouTube Video Rotation for All Angles</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-charmap-incompatibility-challenges/"><u>Overcoming Windows CharMap Incompatibility Challenges</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-zte-nubia-flip-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best ZTE Nubia Flip 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-microsoft-store-crash-error-0x800704cf-in-windows/"><u>Quick Fix for Microsoft Store Crash: Error 0X800704CF in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tips-for-access-denied-on-nvidia-panel/"><u>Quick-Fix Tips for Access Denied on NVIDIA Panel</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/smart-notetaking-reinvented-explore-6-cutting-edge-ai-apps-for-optimal-note-management/"><u>Smart Notetaking Reinvented: Explore 6 Cutting-Edge AI Apps for Optimal Note Management</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-savers-a-guide-to-win11/"><u>Tailoring Screen Savers: A Guide to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-ultimate-guide-to-uniform-focus-in-teamblend-calls-for-2024/"><u>The Ultimate Guide to Uniform Focus in Teamblend Calls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-15-asmr-content-providers-for-2024/"><u>Top 15 ASMR Content Providers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-beyond-fcpx-10-video-editing-solutions-for-every-budget-for-2024/"><u>Updated Beyond FCPX 10 Video Editing Solutions for Every Budget for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/upgrade-to-the-latest-drivers-for-your-brother-l2690dw-printer-quick-guide-and-resources/"><u>Upgrade to the Latest Drivers for Your Brother L2690DW Printer: Quick Guide and Resources</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-itel-p40-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Itel P40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winfixer-rectifying-the-network-not-reachable-error-in-windows-11/"><u>Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11</u></a></li>
</ul></div>

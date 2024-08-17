---
title: "Adjusting Desktop Date & Time: A Win 10/11 Guide"
date: 2024-08-15T23:16:12.577Z
updated: 2024-08-16T23:16:12.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Adjusting Desktop Date & Time: A Win 10/11 Guide"
excerpt: "This Article Describes Adjusting Desktop Date & Time: A Win 10/11 Guide"
keywords: Win 10 SetTime,Win 11 DateChange,SetWinDateWin10,Adjust WindowsDateTime,TimeWin10Configure,DesktopSetWindows,WinOSDateTimeAdjust
thumbnail: https://thmb.techidaily.com/92290ca438acc7b53d6d463fb220788f23c7aae03036a5859c384dd9ace3b529.jpg
---

## Adjusting Desktop Date & Time: A Win 10/11 Guide

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-9-critical-steps-to-double-down-on-your-tiktok-clans-growth/"><u>[New] 2024 Approved  9 Critical Steps to Double Down on Your TikTok Clan's Growth</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-from-screens-to-spreads-the-dos-and-donts-of-live-blogging/"><u>[New] 2024 Approved  From Screens to Spreads  The Do's and Don'ts of Live Blogging</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-tips-on-achieving-fluidity-in-inshot-cuts/"><u>[New] Expert Tips on Achieving Fluidity in Inshot Cuts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-accelerate-or-slow-down-on-the-screen-netflix/"><u>[Updated] Accelerate or Slow Down on the Screen (Netflix)</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-adding-motion-blur-effect-in-photoshop/"><u>2024 Approved  The Ultimate Guide to Adding Motion Blur Effect in Photoshop</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/analyzing-the-precision-of-yis-4k-actioncam/"><u>Analyzing the Precision of Yi's 4K ActionCam</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-disk-usage-errors-in-modern-windows-os/"><u>Circumventing Disk Usage Errors in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-cleaner-windows-11-desktop-layout/"><u>Designing a Cleaner Windows 11 Desktop Layout</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-organize-your-pcenas-7-prime-windows-photos-tools/"><u>Effortlessly Organize Your PC'enas: 7 Prime Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-application-speed-through-improved-networking/"><u>Enhance Windows Application Speed Through Improved Networking</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-windows-selection-of-best-nintendo-switch-imitators/"><u>Exclusive Windows Selection of Best Nintendo Switch Imitators</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-an-overheating-windows-laptop-when-gaming/"><u>How to Fix an Overheating Windows Laptop When Gaming</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-without-backup-on-poco-m6-pro-4g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery without backup on Poco M6 Pro 4G</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-system-of-iphone-se-2020-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of iPhone SE (2020)? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-nubia-red-magic-8s-pro-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-vivo-y78-5g-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Vivo Y78 5G Pictures  An Easy Method Explained.</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-overcoming-obscured-visual-space-on-youtube/"><u>In 2024, Overcoming Obscured Visual Space on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-windows-n-editions-for-business-purposes/"><u>Investigating Windows N Editions: For Business Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-on-mac-via-parallels/"><u>Mastering Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-top-10-best-audio-mixer-software-for-free-for-2024/"><u>New Top 10 Best Audio Mixer Software for FREE for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-path-alteration-guide-for-windows-11-users/"><u>OneDrive Path Alteration Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/1719302097899-opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now!</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-reviving-copy-paste-feature-across-browsers/"><u>Quick Guide: Reviving Copy-Paste Feature Across Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-greyed-out-pin-deletion-in-windows-11-interface/"><u>Resetting Greyed-Out Pin Deletion in Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-prime-audiosubtitle-malfunctions-on-windows-11-systems/"><u>Resolve Prime Audio/Subtitle Malfunctions on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-windows-audioscape-via-driver-update-steps/"><u>Revamping Windows Audioscape via Driver Update Steps</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-windows-update-failure-code-xc004f050/"><u>Reverse Windows Update Failure Code XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-services-console-a-list-of-7-restoration-techniques/"><u>Reviving a Dormant Services Console: A List of 7 Restoration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/roblox-error-403-resolving-access-denied-in-win/"><u>Roblox Error 403: Resolving Access Denied in Win</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-1110s-d3d11-gpu-woes-to-fixable-errors/"><u>Simplifying Windows 11/10'S D3D11 GPU Woes to Fixable Errors</u></a></li>
<li><a href="https://extra-support.techidaily.com/sketchgiggle-generate-chuckles-for-2024/"><u>SketchGiggle  Generate Chuckles for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/skyrocketing-view-figures-by-sustaining-youtubes-creative-commons-license-for-2024/"><u>Skyrocketing View Figures by Sustaining YouTube's Creative Commons License for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rejuvenating-stuck-windows-based-itunes/"><u>Strategies for Rejuvenating Stuck Windows-Based iTunes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/synergizing-storytelling-with-ai-transforming-dandd-through-chatgpt-and-dall-e/"><u>Synergizing Storytelling with AI: Transforming D&D Through ChatGPT & DALL-E</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-vds-failures-head-on/"><u>Tackling Windows VDS Failures Head-On</u></a></li>
<li><a href="https://win11.techidaily.com/three-simplified-steps-for-customizing-win11-ui/"><u>Three Simplified Steps for Customizing Win11 UI</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steam-solutions-for-a-sluggish-connection/"><u>Troubleshooting Steam: Solutions for a Sluggish Connection</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-vivo-y100i-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Vivo Y100i without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unleash-high-speed-internet-anywhere-with-the-slim-and-sturdy-ourlink-u631-usb-nac-wireless-adaptor/"><u>Unleash High-Speed Internet Anywhere with the Slim and Sturdy Ourlink U631 USB N/AC Wireless Adaptor</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-iphone-15-plus-passcode-without-a-computer-drfone-by-drfone-ios/"><u>Unlocking iPhone 15 Plus Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-pc-mysteries-a-step-by-step-guide-to-error-code-management-in-command-prompt/"><u>Unraveling PC Mysteries: A Step-by-Step Guide to Error Code Management in Command Prompt</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-latency-issue-addressed-for-laptop-gpu/"><u>Windows 11 Latency Issue Addressed for Laptop GPU</u></a></li>
</ul></div>

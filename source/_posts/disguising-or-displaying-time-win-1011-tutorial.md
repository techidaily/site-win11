---
title: "Disguising or Displaying Time: Win 10/11 Tutorial"
date: 2024-08-16T00:25:03.997Z
updated: 2024-08-17T00:25:03.997Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disguising or Displaying Time: Win 10/11 Tutorial"
excerpt: "This Article Describes Disguising or Displaying Time: Win 10/11 Tutorial"
keywords: Win10TimeTutorial,Win11TimeDisplay,PCTroubleshootingGuide,OperatingSystemUpdate,TimeTrackingWindows,SystemPerformanceBoost,OSUpgradeHelpCenter
thumbnail: https://thmb.techidaily.com/48eff568c35933b40401a65faa40dbe7bb6a58eb499e343dac1cbda32fedf601.jpg
---

## Disguising or Displaying Time: Win 10/11 Tutorial

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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-intuitive-camera-roll-consolidation-step-by-step-snapchat-guide/"><u>[New] 2024 Approved  Intuitive Camera Roll Consolidation  Step-by-Step Snapchat Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-archive-powerpoint-into-video-repository/"><u>[New] In 2024, Archive PowerPoint Into Video Repository</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-streamlining-song-selection-for-youtube-playlist-curation/"><u>[New] In 2024, Streamlining Song Selection for YouTube Playlist Curation</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-luminance-hdr-review-is-this-a-good-choice-to-create-hdr/"><u>[New] Luminance HDR Review Is This a Good Choice to Create HDR</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-sdr-to-hdr-ultimate-guide-on-sdr-to-hdr-video-conversion/"><u>[New] SDR to HDR Ultimate Guide on SDR to HDR Video Conversion</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-uniting-visuals-the-art-of-video-sequence-composition-for-2024/"><u>[New] Uniting Visuals  The Art of Video Sequence Composition for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-essential-tips-for-efficient-camera-roll-upload-to-snapchat/"><u>[Updated] 2024 Approved  Essential Tips for Efficient Camera Roll Upload to Snapchat</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-flip-the-script-crafting-unique-and-shareable-memes-on-social-platforms/"><u>[Updated] Flip the Script  Crafting Unique and Shareable Memes on Social Platforms</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-powerpoint-presentations-enhancing-clarity-with-voiceovers/"><u>[Updated] In 2024, PowerPoint Presentations  Enhancing Clarity with Voiceovers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-mastering-mac-from-live-classroom-to-recorded-session/"><u>[Updated] Mastering Mac  From Live Classroom to Recorded Session</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-shield-from-ai-crafted-youtube-video-selections/"><u>[Updated] Shield From AI-Crafted YouTube Video Selections</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-viral-vortex-keywords-that-propel-you-into-social-media-spotlight/"><u>[Updated] Viral Vortex  Keywords that Propel You Into Social Media Spotlight</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-free-open-source-video-conferencing-solutions-the-ultimate-list-for-corporates-and-schools/"><u>2024 Approved  Free, Open Source Video Conferencing Solutions  The Ultimate List for Corporates & Schools</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-honing-skills-for-hiring-best-filmmakers/"><u>2024 Approved  Honing Skills for Hiring Best Filmmakers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-animation-solutions-with-advanced-3d-modellers/"><u>2024 Approved  Innovative Animation Solutions with Advanced 3D Modellers</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-clear-the-wallpaper-history-on-windows/"><u>3 Ways to Clear the Wallpaper History on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-ingenious-cmd-puzzles-to-perplex-and-pleasure/"><u>5 Ingenious CMD Puzzles to Perplex and Pleasure</u></a></li>
<li><a href="https://facebook.techidaily.com/5-ways-to-make-life-better-without-your-phone/"><u>5 Ways to Make Life Better Without Your Phone</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-quickly-launch-apps-on-windows-11/"><u>5 Ways to Quickly Launch Apps on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-xiaomi-13t-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Xiaomi 13T without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-change-themes-on-windows-11/"><u>9 Ways to Change Themes On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-printer-administration-interface/"><u>A Comprehensive Look at Windows Printer Administration Interface</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-tutorial-incorporating-widgets-in-windows-11/"><u>A Step-by-Step Tutorial: Incorporating Widgets in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-and-upgrade-top-5-essentials-to-enhance-win-pcs/"><u>Accelerate and Upgrade: Top 5 Essentials to Enhance Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-efficiency-introducing-flow-launcher-methodology/"><u>Accelerate Workflow Efficiency: Introducing Flow Launcher Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-your-virtual-space-windows-11-home/"><u>Accessing Your Virtual Space: Windows 11 Home</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-alt-tab-switching-in-w11/"><u>Ace the Art of Alt Tab Switching in W11</u></a></li>
<li><a href="https://win11.techidaily.com/activate-invisible-mode-quick-turnoff-of-windows-pcs/"><u>Activate Invisible Mode: Quick Turnoff of Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connectivity-issues-fix-iphone-images-not-uploading-in-windows/"><u>Addressing Connectivity Issues: Fix iPhone Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-apps-from-files-in-windows-os/"><u>Addressing Disconnected Apps From Files in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-domain-services-print-problems-in-win11/"><u>Addressing Domain Services Print Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-issues-with-windows-alt-code-operations-53-characters/"><u>Addressing Issues with Windows Alt Code Operations (53 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-dll-issue-in-windows-810/"><u>Addressing Missing DLL Issue in Windows 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-security-strategies-in-powertoys/"><u>Advanced File Security Strategies in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-to-clear-microsoft-defender-history-on-pcs/"><u>Advanced Techniques to Clear Microsoft Defender History on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-tray-graphics-windows-resource-indicators-displayed/"><u>Amplify Tray Graphics: Windows Resource Indicators Displayed</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-spotifys-default-auto-play-on-windows/"><u>Avoid Spotify's Default Auto-Play on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-most-common-blunders-for-first-timers-with-windows-11/"><u>Avoiding the Most Common Blunders for First-Timers with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-black-screen-in-windows-quick-fix-guide/"><u>Banish Black Screen in Windows - Quick Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-novelties-the-next-gen-of-windows-11/"><u>Beyond Novelties: The Next Gen of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-audio-5-ways-for-above-100-output-on-pcs/"><u>Boosting Audio: 5 Ways for Above-100%% Output on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-explore-4-innovative-microsoft-paint-additions/"><u>Breaking Boundaries: Explore 4 Innovative Microsoft Paint Additions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://fox-http.techidaily.com/enabling-pip-for-youtube-viewing-on-your-iphone-for-2024/"><u>Enabling PIP for YouTube Viewing on Your iPhone for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/enhancing-videos-with-professional-voiceovers/"><u>Enhancing Videos with Professional Voiceovers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/find-out-which-phones-make-the-best-friends-with-gear-vr/"><u>Find Out Which Phones Make the Best Friends with Gear VR</u></a></li>
<li><a href="https://discord-videos.techidaily.com/from-novice-to-pro-your-discord-broadcast-journey/"><u>From Novice to Pro  Your Discord Broadcast Journey</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-6-plus-without-losing-any-content-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 6 Plus without Losing Any Content? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-iphone-6s-without-apple-id-by-drfone-ios/"><u>How to Erase an iPhone 6s without Apple ID?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oneplus-11-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From OnePlus 11 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-redmi-note-12-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi Redmi Note 12 5GFRP Lock</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-time-honored-tricks-top-1980s-visual-effects-to-elevate-your-edits/"><u>In 2024, Time-Honored Tricks  Top 1980S Visual Effects to Elevate Your Edits</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-boost-mobile-apple-iphone-xr-before-the-plan-expires-by-drfone-ios/"><u>In 2024, Unlock Your Boost Mobile Apple iPhone XR Before the Plan Expires</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/journey-through-updates-unveiling-lg-bp550-new/"><u>Journey Through Updates  Unveiling LG BP550 New</u></a></li>
<li><a href="https://win11.techidaily.com/1719380925919-keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now</u></a></li>
<li><a href="https://extra-resources.techidaily.com/leading-websites-for-digital-3d-text-with-a-golden-accent/"><u>Leading Websites for Digital 3D Text with a Golden Accent</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-how-to-splitcuttrim-avi-files-easily/"><u>New 2024 Approved How to Split/Cut/Trim AVI Files Easily</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/premier-filmmakers-digital-backdrop-changer/"><u>Premier Filmmaker's Digital Backdrop Changer</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/ranking-of-free-easy-to-use-image-overlay-apps-on-smartphones-for-2024/"><u>Ranking of Free, Easy-to-Use Image Overlay Apps on Smartphones for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-c51-video-recovery-recover-deleted-videos-from-realme-c51-by-fonelab-android-recover-video/"><u>Realme C51 Video Recovery - Recover Deleted Videos from Realme C51</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-vivo-v27-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Vivo V27</u></a></li>
<li><a href="https://win11.techidaily.com/1719254765561-solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-on-iphone-6-plus-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock on iPhone 6 Plus</u></a></li>
</ul></div>

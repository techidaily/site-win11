---
title: Disabling Windows System Update Warnings
date: 2024-08-15T23:36:55.080Z
updated: 2024-08-16T23:36:55.080Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Windows System Update Warnings
excerpt: This Article Describes Disabling Windows System Update Warnings
keywords: Disable Update Alerts,Stop Win Updates Notify,Silence OS Update Warnings,Halt Windows System Alerts,Prevent Windows Update Alarms,Mute Windows Update Issues,Cease Updates Notifications
thumbnail: https://thmb.techidaily.com/6e0cdf2b7038ec925488e32c1b0811331fe39479e79326e6be564a7361db8bbb.jpg
---

## Disabling Windows System Update Warnings

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://extra-information.techidaily.com/new-become-a-pip-expert-enhancing-visual-narratives-on-macos-sierra/"><u>[New] Become a PIP Expert  Enhancing Visual Narratives on macOS Sierra</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-complete-guide-to-video-studios-focusing-on-xvideo/"><u>[New] Complete Guide to Video Studios  Focusing on XVideo</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-zero-to-hero-profit-on-reddit-with-no-experience-top-13/"><u>[New] From Zero to Hero  Profit on Reddit with No Experience (Top 13)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-digitally-rediscovering-past-facebook-sharing-how-to-for-tech-users/"><u>[New] In 2024, Digitally Rediscovering Past Facebook Sharing  How-To for Tech Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-mac-basics-for-creating-attractive-first-youtube-videos/"><u>[New] Mac Basics for Creating Attractive First Youtube Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-collect-premium-audio-for-video-editors/"><u>[Updated] 2024 Approved  Collect Premium Audio for Video Editors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fast-track-uncovering-erased-reddit-conversations/"><u>[Updated] Fast Track  Uncovering Erased Reddit Conversations</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-channel-milestone-hurdle-cross-the-10k-view-threshold-fast/"><u>[Updated] In 2024, Channel Milestone Hurdle – Cross the 10K View Threshold Fast</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-deciphering-instagrams-video-limit-rules/"><u>[Updated] In 2024, Deciphering Instagram's Video Limit Rules</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instagram-reels-strategy-for-instant-success/"><u>[Updated] In 2024, Instagram Reels Strategy for Instant Success</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-checklist-for-finding-film-specialists/"><u>[Updated] The Ultimate Checklist for Finding Film Specialists</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unlocking-the-art-of-alluring-youtube-live-image-creation/"><u>[Updated] Unlocking the Art of Alluring YouTube Live Image Creation</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-unleashing-your-contents-potential-journey-towards-gaining-sponsorship-revenue/"><u>2024 Approved  Unleashing Your Content's Potential  Journey Towards Gaining Sponsorship Revenue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-videocapture-analysis-hub/"><u>2024 Approved  VideoCapture Analysis Hub</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-nubia-red-magic-9-proplus-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Nubia Red Magic 9 Pro+ Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-mouse-customization-for-better-trail-control/"><u>A Simple Guide to Mouse Customization for Better Trail Control</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-look-of-window-11s-search-field/"><u>Altering the Look of Window 11'S Search Field</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-act-equalizing-pc-and-mobile-internet-speeds/"><u>Balancing Act: Equalizing PC & Mobile Internet Speeds</u></a></li>
<li><a href="https://win11.techidaily.com/covert-compression-techniques-for-windows-1011-users/"><u>Covert Compression Techniques for Windows 10/11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-reasons-for-preserving-your-win-11-alerts/"><u>Discover the Reasons for Preserving Your Win 11 Alerts</u></a></li>
<li><a href="https://win-blog.techidaily.com/endureless-control-malfunctions-heres-how-to-fix-them-swiftly-and-easily/"><u>Endureless Control Malfunctions? Here's How to Fix Them Swiftly and Easily!</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-organization-synergizing-to-do-and-ifttt/"><u>Enhance Organization: Synergizing To-Do & IFTTT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhance-your-ai-experience-with-these-5-chatgpt-features-youre-missing-out-on/"><u>Enhance Your AI Experience with These 5 ChatGPT Features You're Missing Out On</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-updating-halt-from-e8024002e/"><u>Eradicating Windows Updating Halt From E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-device-stall-code-0x887a0006-guide/"><u>Fixing Device Stall: Code 0X887A0006 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-glitch-nvidia-experiences-x0001-in-w11/"><u>Fixing Glitch: Nvidia Experience's X0001 in W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-one-sided-windows-headphone-sound-loss/"><u>Fixing One-Sided Windows Headphone Sound Loss</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-shortage-of-usb-interface-points-in-windows/"><u>Fixing Shortage of USB Interface Points in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/free-nba-live-streams-15-ways-to-watch-the-action/"><u>Free NBA Live Streams  15 Ways to Watch the Action</u></a></li>
<li><a href="https://win11.techidaily.com/from-a-simple-pin-a-comprehensive-approach-to-switching-passwords-in-windows-11/"><u>From a Simple PIN: A Comprehensive Approach to Switching Passwords in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/get-rid-of-unwanted-files-setting-up-scheduled-deletions-on-win11/"><u>Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-fixes-for-windows-11-taskbar-loss/"><u>Guiding Fixes for Windows 11 Taskbar Loss</u></a></li>
<li><a href="https://driver-download.techidaily.com/hassle-free-guide-to-installing-asus-z370-e-motherboard-drivers-online/"><u>Hassle-Free Guide to Installing ASUS Z370-E Motherboard Drivers Online</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-file-download-failures-in-windows-1011/"><u>How to Resolve File Download Failures in Windows 10/11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-f23-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo F23 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-beginners-pathway-to-proficientyoucamuse/"><u>In 2024, Beginner's Pathway to ProficientYouCamUse</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimal-conclusion-to-vr-journeys/"><u>In 2024, Optimal Conclusion to VR Journeys</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-xiaomi-redmi-note-12-proplus-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Xiaomi Redmi Note 12 Pro+ 5G</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-insights-new-folder-formation-in-windows-11/"><u>Innovative Insights: New Folder Formation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instructional-manual-restoring-originality-in-windows-11-search/"><u>Instructional Manual: Restoring Originality in Windows 11 Search</u></a></li>
<li><a href="https://youtube-help.techidaily.com/inviting-support-without-coercion-listeners-guide-for-2024/"><u>Inviting Support Without Coercion  Listener's Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-uninstallation-without-recovery-options/"><u>Mastering Printer Uninstallation without Recovery Options</u></a></li>
<li><a href="https://howto.techidaily.com/nokia-c12-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nokia C12 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-startup-changing-boot-timeout-in-windows-11/"><u>Optimize Startup: Changing Boot Timeout in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-fatal-application-hiccups-windows-edition/"><u>Overcoming Fatal Application Hiccups: Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/paint-your-thoughts-desktop-design-mastery-in-windows/"><u>Paint Your Thoughts: Desktop Design Mastery in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sound-error-on-audacity-in-win1011/"><u>Resolving Sound Error on Audacity in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/1719196389328-resolving-stuck-windows-update-problems-now/"><u>Resolving Stuck Windows Update Problems Now</u></a></li>
<li><a href="https://win11.techidaily.com/sketch-mastery-for-desktop-users-in-windows-11/"><u>Sketch Mastery for Desktop Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-with-6-advanced-trackers-for-win-users/"><u>Streamline System Use with 6 Advanced Trackers for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://win11.techidaily.com/the-leaders-small-computers-running-windows/"><u>The Leaders: Small Computers Running Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-science-behind-windows-11s-streamlined-file-safety-measures/"><u>The Science Behind Windows 11’S Streamlined File Safety Measures</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-sluggish-windows-printer/"><u>Troubleshoot Sluggish WIndows Printer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3d11-gpu-error-on-windows-11-and-10/"><u>Troubleshooting D3D11 GPU Error on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-bsod-traces-within-windows-108/"><u>Understanding BSOD Traces Within Windows 10/8</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-infinix-zero-30-5g-by-drfone-android/"><u>Universal Unlock Pattern for Infinix Zero 30 5G</u></a></li>
<li><a href="https://win11.techidaily.com/win11-fixing-persistent-read-only-folders/"><u>Win11: Fixing Persistent Read-Only Folders</u></a></li>
<li><a href="https://win11.techidaily.com/win11-quick-fixes-for-photoshop-not-launching/"><u>Win11: Quick Fixes for Photoshop Not Launching</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
</ul></div>

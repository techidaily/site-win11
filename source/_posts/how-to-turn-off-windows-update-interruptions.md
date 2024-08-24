---
title: How to Turn Off Windows Update Interruptions
date: 2024-08-23T06:10:18.920Z
updated: 2024-08-24T06:10:18.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Off Windows Update Interruptions
excerpt: This Article Describes How to Turn Off Windows Update Interruptions
keywords: WinUpdateStop,EndWindowsUpdates,DisableAutoUpdates,StopUpdaterInterrupts,CeaseWindowsUpdate,ShutOffWindowsUpdates,InterruptionFreeUpdate
thumbnail: https://thmb.techidaily.com/4d7dde3a99efac5f6bdb879d88148e0d5b48fb1025ad045c8786c79687920a30.jpg
---

## How to Turn Off Windows Update Interruptions

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

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
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-innovations-in-live-broadcast-with-periscope/"><u>[New] 2024 Approved  Innovations in Live Broadcast with Periscope</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-perfecting-your-snap-zoom-levels-unveiled-in-insta-stories/"><u>[New] In 2024, Perfecting Your Snap  Zoom Levels Unveiled in Insta Stories</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitter-treatment-creating-gifs-without-spending-a-dime/"><u>[New] In 2024, Twitter Treatment  Creating GIFs Without Spending a Dime</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-mastering-yourwebcamrecordingbasics-for-2024/"><u>[New] Mastering YourWebcam RecordingBasics for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-seamlessly-bring-back-windows-photo-viewer-in-win-11-systems/"><u>[New] Seamlessly Bring Back Windows Photo Viewer in Win 11 Systems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-universal-strategy-to-preserve-your-favorite-youtube-broadcasts-on-all-devices/"><u>[Updated] 2024 Approved  Universal Strategy to Preserve Your Favorite YouTube Broadcasts on All Devices</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-beyond-ustream-live-streaming-choices-for-2024/"><u>[Updated] Beyond Ustream  Live Streaming Choices for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-formulating-final-fact-finding-flourishes-for-2024/"><u>[Updated] Formulating Final Fact-Finding Flourishes for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fps-fanatics-compendium-selecting-superior-extensions/"><u>[Updated] FPS Fanatics' Compendium  Selecting Superior Extensions</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-a-comprehensive-tour-youtube-creator-suite/"><u>[Updated] In 2024, A Comprehensive Tour  YouTube Creator Suite</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-jump-into-action-on-tiktok-live-easy-methods-revealed/"><u>[Updated] Jump Into Action on TikTok Live  Easy Methods Revealed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-revitalizing-video-engagement-easy-steps-for-an-animated-subscribe-button-in-filmora/"><u>[Updated] Revitalizing Video Engagement  Easy Steps for an Animated Subscribe Button in Filmora</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unveil-the-secrets-to-excellent-youtube-thumbnails-for-2024/"><u>[Updated] Unveil the Secrets to Excellent YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-prime-frame-rate-enhancing-laggard-motion/"><u>2024 Approved  Prime Frame Rate Enhancing Laggard Motion</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-social-network-harmony-integrating-instagram-and-facebook/"><u>2024 Approved  Social Network Harmony  Integrating Instagram & Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-optical-character-recognition-ocr-understanding-image-based-text-capture-with-copernic-software/"><u>A Deep Dive Into Optical Character Recognition (OCR): Understanding Image-Based Text Capture with Copernic Software</u></a></li>
<li><a href="https://article-posts.techidaily.com/become-a-successful-smm-in-10-steps/"><u>Become a Successful SMM in 10 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-unwanted-edge-shortcut-popups/"><u>Conquering Unwanted Edge Shortcut Popups</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-leverage-copernic-for-efficient-cloud-storage-searches/"><u>Discover How to Leverage Copernic for Efficient Cloud Storage Searches</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-connection-integrate-your-pc-and-phone-through-flow/"><u>Effortless Connection - Integrate Your PC & Phone Through Flow</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-image-quality-mastering-windows-11s-background-blur-function-in-photos/"><u>Elevate Your Image Quality: Mastering Windows 11'S Background Blur Function in Photos</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-pc-performance-for-faster-steam-content-loading/"><u>Enhancing PC Performance for Faster Steam Content Loading</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-fixing-two-users-ms-login-conflicts/"><u>Expert Tips: Fixing Two Users' MS Login Conflicts</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search</u></a></li>
<li><a href="https://win11.techidaily.com/1723809008305-find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search!</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-zerox-error-code-0x80049dd3-and-enhance-typing/"><u>Fix Windows 11'S Zerox Error (Code: 0X80049DD3) and Enhance Typing</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-chromes-non-responsive-black-screen/"><u>Fixing Chrome's Non-Responsive Black Screen</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-gui-glitches-windows-ux-graphic-improvements-made/"><u>Fixing GUI Glitches: Windows UX Graphic Improvements Made</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-vivo-y100i-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Vivo Y100i Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-the-wsl-error-4294967295-on-windows/"><u>How to Resolve the WSL Error 4294967295 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-a-printer-connection-in-windows/"><u>How to Troubleshoot a Printer Connection in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlink-onedrive-from-windows-11-file-explorer/"><u>How To Unlink OneDrive From Windows 11 File Explorer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-auroras-high-dynamic-range-a-game-changer/"><u>In 2024, Aurora's High Dynamic Range  A Game Changer?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oppo-find-x6-pro-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Oppo Find X6 Pro Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-samsung-gear-360-replacements-latest-innovations-in-camera-tech/"><u>In 2024, Samsung Gear 360 Replacements  Latest Innovations in Camera Tech</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-pursuing-a-profession-in-prompt-engineering-worth-your-time-8-essential-factors-to-consider/"><u>Is Pursuing a Profession in Prompt Engineering Worth Your Time? 8 Essential Factors to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-email-management-9-key-upgrades-in-windows-outlook/"><u>Mastering Email Management: 9 Key Upgrades in Windows' Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/1723809006534-mastering-social-media-growth-with-seamless-menu-expand-functions-on-fb-li-yt-top-level-navigation-essentials/"><u>Mastering Social Media Growth with Seamless Menu Expand Functions on FB, LI, YT - Top-Level Navigation Essentials!</u></a></li>
<li><a href="https://win11.techidaily.com/mending-printer-not-found-error-in-windows-11/"><u>Mending 'Printer Not Found' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-configurations-in-win11/"><u>Navigating Network Configurations in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-workspace-learning-to-use-windows-11s-taskbar-search/"><u>Optimizing Your Workspace: Learning to Use Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/removing-persistent-edge-toolbar-items/"><u>Removing Persistent Edge Toolbar Items</u></a></li>
<li><a href="https://win11.techidaily.com/savings-saved-the-hidden-dangers-in-cheap-windows-activation-codes/"><u>Savings, Saved? The Hidden Dangers in Cheap Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-document-discovery-using-copernics-expert-text-search-features-for-professionals/"><u>Streamline Document Discovery Using Copernic's Expert Text Search Features for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-workflow-with-outlook-preview-on-windows-11/"><u>Streamlining Workflow with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-to-virtualbox-70-on-windows-11-your-ultimate-walkthrough/"><u>Transitioning to VirtualBox 7.0 on Windows 11 – Your Ultimate Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/turn-back-to-standard-contrast-on-windows/"><u>Turn Back to Standard Contrast on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-fixes-overcoming-firefox-page-load-issues-in-windows/"><u>Win Fixes: Overcoming Firefox Page Load Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-print-admin-a-user-friendly-approach/"><u>Windows Print Admin: A User-Friendly Approach</u></a></li>
</ul></div>

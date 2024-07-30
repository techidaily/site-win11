---
title: "Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11"
date: 2024-07-29T15:49:13.324Z
updated: 2024-07-30T15:49:13.324Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11"
excerpt: "This Article Describes Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11"
keywords: Active Windows Hours,Time Blocking W11,Surprise Prevention Windows,Control Active Times,Schedule W11 Settings,Avoid Alerts W11,Windows 11 Activity Period
thumbnail: https://thmb.techidaily.com/f05049a163390a10effd56fd7872beac0cf9789080e0cebdf0db85a2c18febb4.jpg
---

## Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
9. Exit the Registry Editor window.  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-perfecting-virtual-presentations-key-practices-for-using-skypes-screen-share-feature/"><u>[New] 2024 Approved  Perfecting Virtual Presentations  Key Practices for Using Skype’s Screen Share Feature</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-tailored-techniques-for-logging-high-quality-roblox-sessions-on-a-mac/"><u>[New] 2024 Approved  Tailored Techniques for Logging High-Quality Roblox Sessions on a Mac</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-kick-start-your-digital-broadcast-today/"><u>[New] How to Kick-Start Your Digital Broadcast Today</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-pathway-to-facebook-success-livestreaming-recorded-visual-narratives/"><u>[New] In 2024, Pathway to Facebook Success  Livestreaming Recorded Visual Narratives</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-prime-binge-worthy-hits-highest-tweets-and-view-counts/"><u>[New] In 2024, Prime Binge-Worthy Hits  Highest Tweets & View Counts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-quick-curving-techniques-for-modern-photoshop-artists/"><u>[New] Quick Curving Techniques for Modern Photoshop Artists</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-twitch-livestream-hacks-to-boost-engagement-and-followers/"><u>[Updated] 2024 Approved  Twitch Livestream Hacks to Boost Engagement and Followers</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-essential-mixer-streaming-tips-for-mac-users/"><u>[Updated] In 2024, Essential Mixer Streaming Tips for Mac Users</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-from-filer-to-fanfare-transmitting-videos-across-services/"><u>[Updated] In 2024, From Filer to Fanfare  Transmitting Videos Across Services</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-study-aids-top-10-educational-history-channels/"><u>[Updated] Study Aids  Top 10 Educational History Channels</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-taming-the-audio-in-your-canva-videos-step-by-step/"><u>[Updated] Taming the Audio in Your Canva Videos Step by Step</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-economic-sphere-of-the-philanthropic-mr-beast/"><u>[Updated] The Economic Sphere of the Philanthropic Mr. Beast</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-discover-premier-portable-audio/"><u>2024 Approved  Discover Premier Portable Audio</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unveiling-the-secrets-to-effective-virtual-meetings-with-zoom-win10/"><u>2024 Approved  Unveiling the Secrets to Effective Virtual Meetings with Zoom (Win10)</u></a></li>
<li><a href="https://win11.techidaily.com/30-minute-guide-to-resolving-windows-onedrive-fails/"><u>30 Minute Guide to Resolving Windows OneDrive Fails</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-top-win-drawing-apps-that-challenge-procreates-edge/"><u>5 Top Win Drawing Apps That Challenge Procreate's Edge</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-reasons-users-prefer-older-windows-versions/"><u>7 Key Reasons Users Prefer Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-derek-walsh-phd-dr-jeffrey-l-gardiner-phd-and-david-c-muller-phd-from-their-book-understanding-the-psychology-of-religion-exploring-god-33/"><u>A Compre Written by Derek Walsh, PhD; Dr. Jeffrey L. Gardiner, PhD; and David C. Muller, PhD; From Their Book Understanding the Psychology of Religion: Exploring God Wise</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenhensive-guide-to-windows-graphics-reset-techniques/"><u>A Compreenhensive Guide to Windows Graphics Reset Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-reading-qr-codes-with-windows-os/"><u>A Deeper Dive Into Reading QR Codes with Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-winning-path-with-efficient-play/"><u>Accelerate Your Winning Path with Efficient Play</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/activating-and-deactivating-the-essential-windows-key/"><u>Activating & Deactivating the Essential Windows Key</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-sevenzeronine-in-windows/"><u>Addressing Error SevenZeroNine in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-windows-programs-a-fixers-manual/"><u>Addressing Inoperative Windows Programs: A Fixer’s Manual</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-write-prohibited-steam-directories-in-win-11/"><u>Addressing Write-Prohibited Steam Directories in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-xbox-apps-audio-challenges-in-windows-1011/"><u>Addressing Xbox App's Audio Challenges in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-login-failure-threshold-step-by-step-for-windows-11-users/"><u>Adjusting Login Failure Threshold: Step-by-Step for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/adopting-new-visual-elements-the-microsoft-store-experience/"><u>Adopting New Visual Elements: The Microsoft Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/advice-for-fixing-untraceable-windows-drives/"><u>Advice for Fixing Untraceable Windows Drives</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-windows-identifier-with-microsoft-entity/"><u>Aligning Windows Identifier with Microsoft Entity</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-keystroke-speed-with-typingaid-tools/"><u>Amplify Keystroke Speed with TypingAid Tools</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-with-11-troubleshooting-windows-tips/"><u>Avoid Frustration with 11 Troubleshooting Windows Tips</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-conflict-over-shared-device-camera-error-0xa00f4243/"><u>Avoiding Conflict Over Shared Device (Camera, Error 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-an-admin-in-windows-control-settings/"><u>Becoming an Admin in Windows Control Settings</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-of-windows-modern-standby-problems/"><u>Beneath the Surface of Windows Modern Standby Problems</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-speed-implementing-a-smart-enhanced-run-feature/"><u>Boosting System Speed: Implementing a Smart Enhanced Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-taskbar-efficiency/"><u>Boosting Windows 11 Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/boot-overhaul-guide-windows-revival-in-eight-steps/"><u>Boot Overhaul Guide: Windows Revival in Eight Steps</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-swapping-old-to-new-window-drivers/"><u>Breaking Barriers: Swapping Old to New Window Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-cycles-of-compliance-my-defiance-against-app-guard-norms/"><u>Breaking Cycles of Compliance: My Defiance Against App Guard Norms</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-code-breakdowns-quick-windows-fixes/"><u>Breaking Free From Code Breakdowns: Quick Windows Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/1719301836134-clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now!</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-redmi-13c-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi Redmi 13C Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719327784213-fixing-the-common-wwinplusp-errors-on-windows-devices/"><u>Fixing the Common WWin+P Errors on Windows Devices</u></a></li>
<li><a href="https://screen-recording.techidaily.com/from-pixels-to-perfection-selecting-the-premier-screen-recording-software/"><u>From Pixels to Perfection  Selecting the Premier Screen Recording Software</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/how-to-make-video-slideshow-with-your-travel-photos-for-2024/"><u>How to Make Video Slideshow with Your Travel Photos for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-realme-12-pro-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Realme 12 Pro 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-xs-max-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone XS Max Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-watch-hulu-outside-us-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-compelling-combinations-a-guide-to-creating-your-own-youtube-playlists/"><u>In 2024, Crafting Compelling Combinations  A Guide to Creating Your Own YouTube Playlists</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-on-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently On Apple iPhone 14 Plus</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-huawei-nova-y71-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Huawei Nova Y71 to New Android? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-meizu-21-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Meizu 21 Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719310047074-overcome-compatibility-issues-with-easy-fixed-steps/"><u>Overcome Compatibility Issues with Easy Fixed Steps.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/pivot-and-post-mastering-video-orientation/"><u>Pivot and Post  Mastering Video Orientation</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/quick-fame-quest-mastering-content-video-and-likes/"><u>Quick Fame Quest - Mastering Content, Video, and Likes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-vivo-x100-pro-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Vivo X100 Pro Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-xiaomi-redmi-note-12-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Xiaomi Redmi Note 12 5G Location | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/ultimate-guide-to-the-best-10-online-platforms-for-vimeo-downloading/"><u>Ultimate Guide to the Best  10 Online Platforms for Vimeo Downloading</u></a></li>
</ul></div>

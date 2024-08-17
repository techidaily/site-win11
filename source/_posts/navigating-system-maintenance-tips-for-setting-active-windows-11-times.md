---
title: "Navigating System Maintenance: Tips for Setting Active Windows 11 Times"
date: 2024-08-15T23:46:50.297Z
updated: 2024-08-16T23:46:50.297Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating System Maintenance: Tips for Setting Active Windows 11 Times"
excerpt: "This Article Describes Navigating System Maintenance: Tips for Setting Active Windows 11 Times"
keywords: Win11 Setup Guide,Timesync Windows 11,Optimal Win11 Time,Win11 Maintenance Tips,Active Windows 11 Schedule,Setting Win11 Clock,Timing Windows 11 Properly
thumbnail: https://thmb.techidaily.com/0d1e6d469f4667c3d31e2ee564e25a93a1f4e0a1835558608501c466657ed85d.png
---

## Navigating System Maintenance: Tips for Setting Active Windows 11 Times

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.
9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-step-by-step-guide-to-game-recording-using-obs/"><u>[New] 2024 Approved  Step-by-Step Guide to Game Recording Using OBS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-elevate-your-video-aesthetics-with-obss-customizable-luts-for-2024/"><u>[New] Elevate Your Video Aesthetics with OBS's Customizable LUTs for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/uture-earning-potential-in-gaming-videos/"><u>[New] Future Earning Potential in Gaming Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gamers-path-to-earnings-on-youtube-for-2024/"><u>[New] Gamer's Path to Earnings on YouTube for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-discover-the-ease-of-sound-liberation-with-pazeras-tools/"><u>[New] In 2024, Discover the Ease of Sound Liberation with Pazera's Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-streamline-your-video-capture-with-macbook-cam-settings/"><u>[New] Streamline Your Video Capture with MacBook Cam Settings</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-step-into-success-the-essentials-you-need-to-know-about-fb-stories/"><u>[Updated] 2024 Approved  Step Into Success  The Essentials You Need to Know About FB Stories</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-brand-awareness-through-opening/"><u>[Updated] Brand Awareness Through Opening</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-from-raw-footage-to-youtube-a-step-by-step-process-unveiled/"><u>[Updated] From Raw Footage to YouTube  A Step-by-Step Process Unveiled</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-ioss-best-selection-of-premium-psp-emulators/"><u>[Updated] In 2024, IOS's Best Selection of Premium PSP Emulators</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-depth-analysis-the-best-livestreaming-video-tech-for-2024/"><u>[Updated] In-Depth Analysis  The Best Livestreaming Video Tech for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-mobilizing-money-a-complete-guide-to-youtubes-revenue-features-for-2024/"><u>[Updated] Mobilizing Money  A Complete Guide to YouTube's Revenue Features for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-revolutionizing-the-market-the-leading-7-tools-to-create-digital-tokens-for-2024/"><u>[Updated] Revolutionizing the Market - The Leading 7 Tools to Create Digital Tokens for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-will-2023-see-an-increase-in-televising-video-content/"><u>[Updated] Will 2023 See an Increase in Televising Video Content?</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-xiaomi-redmi-note-12-pro-4g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Xiaomi Redmi Note 12 Pro 4G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-solutions-for-resolving-windows-11-naming-issues-in-directories/"><u>7 Solutions for Resolving Windows 11 Naming Issues in Directories</u></a></li>
<li><a href="https://win11.techidaily.com/access-advanced-control-panel-to-change-screen-after-dark-mode/"><u>Access Advanced Control Panel to Change Screen After Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-plugged-inspection-failure-for-pc-sound-devices/"><u>Addressing Plugged Inspection Failure for PC Sound Devices</u></a></li>
<li><a href="https://article-helps.techidaily.com/asmr-mic-spectacular-exceptional-sound-for-a-good-deal/"><u>ASMR Mic Spectacular  Exceptional Sound for a Good Deal</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/brief-stardom-flash-review-for-2024/"><u>Brief Stardom Flash Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabling-directives-essential-4-fixes-to-windows-ps-load-issue/"><u>Bypassing Disabling Directives: Essential 4 Fixes to Windows PS Load Issue</u></a></li>
<li><a href="https://tech-revival.techidaily.com/cease-the-comparison-game-grasping-how-siri-differs-from-chatgpt/"><u>Cease the Comparison Game - Grasping How Siri Differs From ChatGPT</u></a></li>
<li><a href="https://extra-information.techidaily.com/diy-itunes-tutorial-changing-and-upgrading-iphone-ringtones/"><u>DIY iTunes Tutorial  Changing & Upgrading iPhone Ringtones</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-hide-search-icon-from-taskbar-in-win-11/"><u>Easy Steps: Hide Search Icon From Taskbar in Win 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/essential-tips-for-using-switch-pro-controller-with-steam-for-2024/"><u>Essential Tips for Using Switch Pro Controller with Steam for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-windows-11-vm-reset/"><u>Guidelines for Windows 11 VM Reset</u></a></li>
<li><a href="https://win11.techidaily.com/handling-unable-to-open-file-for-writing-error-in-win-11/"><u>Handling Unable to Open File for Writing Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-to-do-app-when-its-not-syncing/"><u>How to Fix the Microsoft To Do App When It’s Not Syncing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-downloads-not-working-on-win-devices/"><u>How to Resolve Downloads Not Working on Win Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-a-non-responsive-windows-notepad-application/"><u>How to Revive a Non-Responsive Windows Notepad Application</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-apple-iphone-xs-max-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Leave a Life360 Group On Apple iPhone XS Max Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-y36-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y36 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-laugh-track-in-the-air-parody-anthems/"><u>In 2024, Laugh Track in the Air  Parody Anthems</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-inverted-images-conundrum-on-instagram-feed/"><u>In 2024, The Inverted Images Conundrum on Instagram Feed</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-safety-turning-on-folder-controls-in-windows/"><u>Mastering File Safety: Turning On Folder Controls in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-of-0xc000003e-error-on-pcs/"><u>Mastering the Fix of 0xC000003E Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-restart-efficient-three-ways/"><u>Mastering Windows Restart: Efficient Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-fn-keys-functionality-on-windows-1011/"><u>Optimizing FN Keys' Functionality on Windows 10/11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/our-commitment-to-excellence-245-satisfaction-certified/"><u>Our Commitment to Excellence – 245 Satisfaction Certified</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disconnects-resolving-fall-guys-errors-on-windows/"><u>Overcoming Disconnects: Resolving Fall Guys Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-note-apps-for-the-modern-windows-slates/"><u>Perfect Note Apps for the Modern Windows Slates</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-not-responsive-spotify-error-in-windows-oses/"><u>Resolving Not Responsive Spotify Error in Windows OSes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/splitcams-journey-to-video-excellence-an-overview/"><u>SplitCam's Journey to Video Excellence  An Overview</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-missing-windows-phone-link-notifications/"><u>Steps to Reactivate Missing Windows Phone Link Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-switch-apps-using-snap-feature-in-windows-11/"><u>Swiftly Switch Apps Using Snap Feature in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-vs-powershell-pinpointing-the-distinguishing-aspects/"><u>Terminal Vs. PowerShell: Pinpointing the Distinguishing Aspects</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-secure-windows-sound-level-adjustments/"><u>Tips to Secure Windows Sound Level Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-11-task-managers-perfect-for-organizing-daily-chores/"><u>Top 6 Windows 11 Task Managers Perfect for Organizing Daily Chores</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723013259514-trouble-with-house-flipper-2-heres-how-to-resolve-pc-malfunctions-and-enjoy-gaming/"><u>Trouble with House Flipper 2? Here's How to Resolve PC Malfunctions and Enjoy Gaming!</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-a-faulty-esc-key-in-windows-10-and-beyond/"><u>Troubleshoot a Faulty Esc Key in Windows 10 and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/unbeatable-black-friday-save-612-on-windows-10/"><u>Unbeatable Black Friday: Save $6.12 on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-hidden-cameras-fix-their-absence-in-dm/"><u>Uncover Hidden Cameras: Fix Their Absence in DM</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-securely-without-screensaver/"><u>Unlock Windows 11 Securely Without Screensaver</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-unlocking-advanced-visuals-how-to-use-picture-in-picture-in-final-cut-pro/"><u>Updated In 2024, Unlocking Advanced Visuals How to Use Picture-in-Picture in Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-organizing-the-art-of-customizing-windows-outlook-calendars/"><u>Winning at Organizing: The Art of Customizing Window's Outlook Calendars</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-fine-tuning-your-amd-settings-in-windows-gaming/"><u>Winning Strategy: Fine-Tuning Your AMD Settings in Windows Gaming</u></a></li>
</ul></div>

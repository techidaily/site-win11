---
title: 3 Ways to Reset the Windows 11 Settings App
date: 2024-08-15T23:23:47.954Z
updated: 2024-08-16T23:23:47.954Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Reset the Windows 11 Settings App
excerpt: This Article Describes 3 Ways to Reset the Windows 11 Settings App
keywords: Reset Windows 11,Windows 11 Restore,Settings App Reinit,Windows 11 Resetting,New Settings Sync,Update Windows 11,Fix Windows 11 Setup
thumbnail: https://thmb.techidaily.com/41e7c10c6afe154b3744b08a21830239b330cdc09fe1222610e43f6045480d9b.jpg
---

## 3 Ways to Reset the Windows 11 Settings App

 The Settings app in Windows 11 makes it simple for you to manage various settings and preferences on your computer. Whether you want to customize your computer's theme, manage network connections or check for system updates, the Windows Settings app is a central location for all your computer management needs.

 If the Windows 11 Settings app stops working, or if you want to restore it to its default settings, you can always reset it. You can reset the Windows Settings app using the search menu, Command Prompt or PowerShell. Let's go over all three methods in detail.

## 1\. How to Reset the Windows 11 Settings App Using the Search Menu

 The quickest way to reset the Windows 11 Settings app is through the search menu. So, let's start with that.

To reset the Windows 11 Settings app with the search menu:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to access the search menu.
2. Type**Settings** in the search box.
3. Select the**App settings** option from the right pane.
4. Scroll down to the Reset section and click the**Reset** button.
5. Select**Reset** again to confirm.  
![Reset Settings App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-in-windows-11.jpg)

 After completing the above steps, you can use one of the [many ways to access the Windows Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and configure it again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Reset the Windows 11 Settings App via PowerShell

 If you prefer to interact with your computer through a command-line interface, you can also use PowerShell to reset the Windows Settings app. Don’t worry, the process isn’t as intimidating as it might sound.

 Use these steps to reset the Windows 11 Settings app using PowerShell.

1. Click the**search icon** on the taskbar to open the search menu.
2. Type**Windows PowerShell** in the search box.
3. Select**Run as administrator** from the right side.
4. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
5. In the console, type the following command and press**Enter** to reset the Settings app.  
`Get-AppxPackage *Windows.ImmersiveControlPanel* | Reset-AppxPackage`  
![Reset Settings App Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

 If you're a PowerShell enthusiast, why not take the time to learn these [useful Windows PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to improve efficiency?

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Reset the Windows 11 Settings App Using Command Prompt

 Another way to reset the Windows 11 Settings app is via Command Prompt. Similar to the method above, resetting the Settings app using Command Prompt only requires you to run a single command.

 To reset the Windows 11 Settings app using Command Prompt, use these steps:

1. Press**Win + X** or right-click the**start icon** to open the Power User menu and select**Run** from the list.
2. Type**cmd** in the text box and then press**Ctrl + Shift + Enter** on your keyboard to [open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#how-to-run-command-prompt-as-an-administrator-through-the-windows-search-tool) .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, paste the following command and hit**Enter** :  
`PowerShell -ExecutionPolicy Unrestricted -Command "& {$manifest = (Get-AppxPackage *immersivecontrolpanel*).InstallLocation + '\AppxManifest.xml' ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}"`

![Reset Settings App Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->

 Once you run the above command, Windows will reset the Settings app on your computer.

 Do you find Command Prompt to be too complicated or boring to use? Here are some of [the best Command Prompt alternatives for Windows](https://www.makeuseof.com/best-command-prompt-alternatives-for-windows/) worth trying.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## Resetting the Windows 11 Settings App

 Regardless of the method you use, resetting Windows 11 Settings app shouldn’t take more than a couple of minutes of your time. After that, you can start configuring your computer settings from scratch.

 If, however, resetting the Settings app does not solve your problem, you can try creating a new user account. Alternatively, you can consider factory resetting your Windows 11 computer and starting over.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-instagram-silent-spots-how-to-make-every-frame-loud-and-clear/"><u>[New] 2024 Approved  Instagram Silent Spots - How to Make Every Frame Loud and Clear</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-efficientuseofyourwebcamforrecording/"><u>[New] EfficientUseOfYourWebcamForRecording</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-imagelogger-screen-logger-xtreme/"><u>[New] In 2024, ImageLogger Screen Logger Xtreme</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-precision-in-pacing-time-lapse-on-ipad/"><u>[New] In 2024, Precision in Pacing  Time-Lapse on iPad</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-screensphere-comprehensively-global-plus-locally-connected/"><u>[New] In 2024, ScreenSphere  Comprehensively Global + Locally Connected</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-beginners-handbook-to-instagrams-most-popular-feature-reels/"><u>[New] In 2024, The Beginner’s Handbook to Instagram’s Most Popular Feature – Reels</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-rapid-reactivities-leading-fast-paced-titles-on-pc-and-tablet/"><u>[New] Rapid Reactivities  Leading Fast-Paced Titles on PC & Tablet</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-reel-in-real-time-the-top-5-innovative-recorder-apps-for-browsers/"><u>[New] Reel in Real-Time  The Top 5 Innovative Recorder Apps for Browsers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-top-6-masterpieces-designing-mc-village-homes/"><u>[New] Top 6 Masterpieces  Designing MC Village Homes</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-drones-dynamic-duo-gear-and-lgcam-face-off-battle/"><u>[Updated] In 2024, Drones' Dynamic Duo  Gear & LGCam Face-Off Battle</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-enjoy-whole-audio-on-twitch-addressing-muted-segments-now/"><u>[Updated] In 2024, Enjoy Whole Audio on Twitch  Addressing Muted Segments Now</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-instant-title-insertion-for-your-videos-on-windows-photos/"><u>[Updated] Instant Title Insertion for Your Videos on Windows Photos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-social-stardom-spectrum-global-internet-icons-for-2024/"><u>[Updated] Social Stardom Spectrum  Global Internet Icons for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/13-enhanced-functions-for-windows-11-in-the-newest-update/"><u>13 Enhanced Functions for Windows 11 in the Newest Update</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-tech-gadgets-with-ois-for-professional-filmmaking/"><u>2024 Approved  Best Tech Gadgets with OIS for Professional Filmmaking</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-flourishing-in-virtual-dialogue-top-strategies-to-master-zoom-chats/"><u>2024 Approved  Flourishing in Virtual Dialogue  Top Strategies to Master ZOOM Chats</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-immerse-audiences-integrating-sound-effectively-in-canva-films/"><u>2024 Approved  Immerse Audiences  Integrating Sound Effectively in Canva Films</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-unleash-potential-stardews-premium-mod-lineup-7-14/"><u>2024 Approved  Unleash Potential  Stardew's Premium Mod Lineup #7-14</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-or-disable-the-delete-confirmation-dialog-on-windows/"><u>3 Ways to Enable or Disable the Delete Confirmation Dialog on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-make-windows-11-start-up-faster/"><u>3 Ways to Make Windows 11 Start Up Faster</u></a></li>
<li><a href="https://win11.techidaily.com/4-keys-to-reviving-a-device-stuck-in-night-setting/"><u>4 Keys to Reviving a Device Stuck in Night Setting</u></a></li>
<li><a href="https://win11.techidaily.com/5-immediate-actions-reviving-disabled-windows-defender-protection/"><u>5 Immediate Actions: Reviving Disabled Windows Defender Protection</u></a></li>
<li><a href="https://win11.techidaily.com/7-strong-arguments-against-switching-from-win10-to-win11-immediately/"><u>7 Strong Arguments Against Switching From Win10 to Win11 Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-to-rethink-your-email-client-the-modern-outlook/"><u>9 Reasons to Rethink Your Email Client - The Modern Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-upgrading-virtualbox-v70-in-win11/"><u>A Beginner's Guide to Upgrading VirtualBox v7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-unveiling-affordable-windows-10-mastery/"><u>A Complete Unveiling: Affordable Windows 10 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-change-taskbar-history-19852023/"><u>A Window Into Change: Taskbar History (1985–2023)</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-policy-settings-with-windows-11-expertise/"><u>Accelerate Policy Settings with Windows 11 Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-virtualization-setting-up-win11-with-vmware-17-player/"><u>Accelerating Virtualization: Setting Up Win11 with VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-driver-verifier-manager-w11-edition/"><u>Accessing Driver Verifier Manager W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-synchronized-data-across-your-multiple-windows-desktops-with-aoemi/"><u>Achieve Synchronized Data Across Your Multiple Windows Desktops With AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/address-windows-missing-camera-mystery-in-device-manager/"><u>Address Windows' Missing Camera Mystery in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-errors-when-transferring-images-from-iphone-to-pc/"><u>Addressing Errors When Transferring Images From iPhone to PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-cannot-locate-gpeditmsc-error-in-windows/"><u>Addressing the Cannot Locate Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011s-error-0x8007045d/"><u>Addressing Win 10/11'S Error 0X8007045D</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-onedrives-incorrect-tag-issue/"><u>Addressing Windows Error: OneDrive’s Incorrect Tag Issue</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clock-display-window-10-and-11-guide/"><u>Adjusting Clock Display: Window 10 & 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-preview-sizes-on-windows-11/"><u>Adjusting Photo Preview Sizes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/amd-graphics-update-essentials-for-windows-11-users/"><u>AMD Graphics Update Essentials for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-new-windows-editions-which-fits-you-best-home-or-pro/"><u>Assessing New Windows Editions: Which Fits You Best, Home or Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/automating-windows-11-app-installation-a-guide-to-winstall/"><u>Automating Windows 11 App Installation: A Guide to Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-missed-messages-solutions-to-windows-mail-alert-issues/"><u>Avoiding Missed Messages: Solutions to Windows Mail Alert Issues</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-save-location-blunders-on-windows-devices/"><u>Avoiding Save Location Blunders on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-windows-11-installation/"><u>Beginner's Blueprint to Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/1719289257399-black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime!</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-email-readability-pinning-gmail-bar-on-pc/"><u>Boosting Email Readability: Pinning Gmail Bar on PC</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-widget-integration-in-windows-11/"><u>Boosting Productivity with Widget Integration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breached-bytebandit-ponder-the-path-for-a-possible-pivot/"><u>Breached ByteBandit: Ponder the Path for a Possible Pivot</u></a></li>
<li><a href="https://win11.techidaily.com/1719285734353-breathe-life-back-into-your-computers-print-command-wwinplusp/"><u>Breathe Life Back Into Your Computer's Print Command (WWin+P)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-infinix-note-30i-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Infinix Note 30i.</u></a></li>
<li><a href="https://fox-glue.techidaily.com/dissecting-gopros-max-and-hero-11-video-capabilities-for-2024/"><u>Dissecting GoPro's Max and Hero 11 Video Capabilities for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/dissecting-the-top-5-technological-missteps-of-recent-times/"><u>Dissecting the Top 5 Technological Missteps of Recent Times</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-nokia-c300-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Nokia C300 FRP In 3 Different Ways</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-xiaomi-13-ultra-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Xiaomi 13 Ultra?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-vivo-s18-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Vivo S18 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-elite-mac-audio-enhanced-screen-recorder/"><u>In 2024, Elite Mac Audio-Enhanced Screen Recorder</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-mastering-online-channel-name-creation-tips-and-tricks/"><u>In 2024, Mastering Online Channel Name Creation  Tips & Tricks</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/light-and-color-interplay-for-images-for-2024/"><u>Light & Color Interplay for Images for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-htc-u23-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends HTC U23 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719328494393-uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present!</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-depth-review-of-ivona-text-to-speech-by-nextup-technologies/"><u>Updated In-Depth Review of Ivona Text to Speech by NextUp Technologies</u></a></li>
</ul></div>

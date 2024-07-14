---
title: Controlling Devices in the Dormant System State
date: 2024-07-13T10:43:23.530Z
updated: 2024-07-14T10:43:23.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Devices in the Dormant System State
excerpt: This Article Describes Controlling Devices in the Dormant System State
keywords: Dormant System Controls,Device Management Sleep,Sleep Mode Device Ops,Operating Device Standby,Systems In Low-Power Mode,Power State Device Management,Devices in Idle Stance
thumbnail: https://thmb.techidaily.com/b291d1186c17a0e27af028a28ffb312d4304bf88d64275a707a4eb2f0cc766f8.jpg
---

## Controlling Devices in the Dormant System State

 When not in use, putting your Windows PC to sleep is an excellent way to preserve its battery life. You can wake your computer at any time by simply wiggling the mouse, pressing the power button, or pressing a key on your keyboard.

 Windows gives you complete control over devices that can wake your computer from a sleep state. In this guide, we will discuss how you can manage those devices.

## How to Check Which Devices Are Capable of Waking Your Windows PC From Sleep Mode

 Not every device connected to your system can wake Windows from sleep mode. You can use Command Prompt or Windows PowerShell to determine which of your devices supports waking the computer.

1. Press**Win + S** to open the search menu.
2. Type in**Windows PowerShell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to view a list of devices on your system that can wake Windows from any sleep state.  
`powercfg -devicequery wake_from_any`  
![Devices That Can Wake Windows From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-That-Can-Wake-Windows-From-Sleep-Mode.jpg)

 On this list, you'll see devices like your keyboard, mouse, network adapter, and more.

## How to Check Which Devices Are Allowed to Wake Your Windows PC From Sleep Mode

 Command Prompt or PowerShell can also tell you which devices are permitted to wake your Windows PC from sleep mode. Here's how to find out.

1. [Open Command Prompt or Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command and press**Enter** to view a list of devices that are allowed to wake your computer from sleep mode.  
`powercfg -devicequery wake_armed`  
![Devices Are Allowed to Wake Your Windows PC From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-Are-Allowed-to-Wake-Your-Windows-PC-From-Sleep-Mode.jpg)

## How to Find Out What Woke Your Windows PC From Sleep Mode

 Many times, you may find that your Windows computer wakes from sleep mode on its own. Often, it's one of the connected devices or processes that causes your computer to wake up. Windows can tell you exactly what woke your computer from sleep mode.

1. Press**Win + R** to open the Run dialog.
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to [launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
3. Input the following command and press**Enter** .  
`powercfg -lastwake`  
![Check What Woke Windows From Sleep](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-What-Woke-Windows-From-Sleep.jpg)

 Once you run the above command, Windows will tell you which device or process woke your computer from sleep mode.

 If you see something like**Wake History Count - 0** , it means that Windows doesn't have a record of wake history. This can happen if you've recently rebooted your computer.

## How to Allow or Deny a Device Permission to Wake Your Windows PC From Sleep Mode

 Once you know which devices are waking up your computer without your consent, you can take the necessary steps to prevent them from doing so.

To allow or deny a device permission to wake your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Device Manager** from the list.
3. Locate the device you want to configure. Right-click on it and select**Properties** .
4. In the Properties window, switch to the**Power Management** tab.
5. Check or uncheck the**Allow this device to wake the computer** checkbox to allow or disallow the permission.
6. Click**OK** to save the changes.  
![Allow or Disallow Device to Wake Computer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Allow-or-Disallow-Device-to-Wake-Computer-on-Windows.jpg)

 You can repeat the above steps to configure power management settings for more devices if you want.

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on [how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

## Manage Your Computer’s Sleep

 Now you know what devices can wake your computer from a sleep state and how to prevent them from doing so. That said, putting your computer in sleep mode may not always be the best option for your laptop. Sometimes, it’s better to shut it down completely.


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
<li><a href="https://win11.techidaily.com/exclusive-list-of-windows-most-reliable-usage-monitors/"><u>Exclusive List of Windows' Most Reliable Usage Monitors</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-fix-blurry-facebook-videos-in-smartphones-and-chromebooks/"><u>2024 Approved  Fix Blurry Facebook Videos in Smartphones & Chromebooks</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-masterful-method-smart-watch-to-access-mac/"><u>[Updated] Masterful Method  Smart Watch to Access Mac</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-boot-virtual-machine-troubles-with-vmware-on-win11/"><u>Fixing Non-Boot Virtual Machine Troubles with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/old-wallpapers-no-more-discover-three-solutions/"><u>Old Wallpapers No More! Discover Three Solutions</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/best-sound-remover-from-video-windowsmaconline-for-2024/"><u>Best Sound Remover From Video Windows/Mac/Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quicken-real-time-update-of-task-manager-in-win-11/"><u>Quicken Real-Time Update of Task Manager in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/your-quick-reference-to-fixing-windows-photo-application/"><u>Your Quick Reference to Fixing Window's Photo Application</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-windows-experience-the-significance-of-16gb-ram/"><u>Advancing Windows Experience: The Significance of 16GB RAM</u></a></li>
<li><a href="https://win11.techidaily.com/declutter-your-computer-finding-and-purging-windows-empties/"><u>Declutter Your Computer: Finding & Purging Windows' Empties</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-from-chaos-to-calm-quick-edits-for-your-overwhelming-tiktok-drafters/"><u>2024 Approved  From Chaos to Calm  Quick Edits for Your Overwhelming TikTok Drafters</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-auto-play-in-spotify-for-windows-pcs/"><u>Disabling Auto-Play in Spotify for Windows PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-beginners-path-to-screen-casting-with-apple-devices/"><u>2024 Approved  Beginner’s Path to Screen Casting with Apple Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-create-a-dynamic-display-windows-11s-rgb-lighting/"><u>How to Create a Dynamic Display: Windows 11'S RGB Lighting</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-the-feel-personalizing-touchpad-settings-in-windows-11/"><u>Fine-Tune the Feel: Personalizing Touchpad Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-halted-by-error-2e-solutions-here/"><u>Windows Update Halted by Error 2E? Solutions Here</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mac-cam-tips-superior-quality-recordings-for-2024/"><u>Mac Cam Tips  Superior Quality Recordings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-devhome-transforming-your-w11-experience/"><u>The Essence of DevHome: Transforming Your W11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-management-for-windows-11-domain-based/"><u>Biometric Management for Windows 11, Domain-Based</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-unlock-the-power-of-slow-motion-a-beginners-guide-to-windows-live-movie-maker/"><u>In 2024, Unlock the Power of Slow Motion A Beginners Guide to Windows Live Movie Maker</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-and-resolve-windows-error-code-0xc00000f-quickly/"><u>Avoid and Resolve Windows Error Code: 0Xc00000f Quickly</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-snap-edit-and-share-spectacularly-on-tiktok-with-themes/"><u>[Updated] In 2024, Snap, Edit & Share Spectacularly on TikTok with Themes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/burning-videos-to-dvd-a-beginners-guide-for-windows-and-mac-for-2024/"><u>Burning Videos to DVD A Beginners Guide for Windows and Mac for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tiktok-trends-the-top-ten-tweets-shaping-social-media/"><u>[Updated] TikTok Trends  The Top Ten Tweets Shaping Social Media</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-magixs-masterpiece-an-in-depth-look-at-video-pro-x/"><u>In 2024, Magix's Masterpiece  An In-Depth Look at Video Pro X</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-to-do-management-in-the-microsoft-ecosystem/"><u>Mastering To-Do Management in the Microsoft Ecosystem</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-transformative-typography-in-after-effects/"><u>[Updated] 2024 Approved  Transformative Typography in After Effects</u></a></li>
<li><a href="https://games-able.techidaily.com/premium-games-before-launch-exploration-or-caution/"><u>Premium Games Before Launch - Exploration or Caution?</u></a></li>
<li><a href="https://win11.techidaily.com/procedure-opening-driver-verifier-for-fault-analysis/"><u>Procedure: Opening Driver Verifier for Fault Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-windows-11-help-application-use/"><u>Steps to Regain Windows 11 Help Application Use</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-gain-entry-windowsstore-apps-explorer/"><u>How To Gain Entry: WindowsStore Apps Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-zoom-error-code-1132-in-windows-10-and-11/"><u>How to Fix Zoom Error Code 1132 in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-honor-magic-vs-2-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Honor Magic Vs 2 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/proven-tools-to-assist-in-making-your-pc-to-mac-os-transition-easier/"><u>Proven Tools to Assist in Making Your PC-to-Mac OS Transition Easier</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-soundscape-windows-11-spatial-tips/"><u>Elevate Your Soundscape: Windows 11 Spatial Tips</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inability-to-install-windows-store-apps/"><u>Resolving Inability to Install Windows Store Apps</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dealing-with-sudden-printer-shutdowns/"><u>Dealing with Sudden Printer Shutdowns</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/1713954039761-updated-in-2024-best-8-online-gif-to-apng-converters/"><u>Updated In 2024, | Best 8 Online GIF to APNG Converters</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-cut-videos-for-instagram-on-mac-for-2024/"><u>How To Cut Videos For Instagram On Mac for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-discreetly-discovering-content-how-to-read-instagram-stories-privately-on-pcandroidios-for-2024/"><u>[Updated] Discreetly Discovering Content  How to Read Instagram Stories Privately on PC/Android/iOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/joining-the-dots-win-keys-and-microsoft-login-registration/"><u>Joining the Dots: WIN KEYS and MICROSOFT LOGIN REGISTRATION</u></a></li>
<li><a href="https://win11.techidaily.com/revel-in-rich-software-diversity-on-windows/"><u>Revel in Rich Software Diversity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ready-for-success-testing-your-meeting-tech-on-windows/"><u>Ready for Success: Testing Your Meeting Tech on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-oneplus-nord-n30-se-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your OnePlus Nord N30 SE Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-the-google-play-store-on-windows-11/"><u>How to Install the Google Play Store on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-powershell-on-windows-system/"><u>Troubleshooting: No PowerShell on Windows System</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-essential-tips-for-operating-ez-grabber/"><u>[Updated] 2024 Approved  Essential Tips for Operating EZ Grabber</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-complete-guide-to-youtubes-live-image-lore/"><u>A Complete Guide to YouTube's Live Image Lore</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-nokia-130-music-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Nokia 130 Music Phone and Remove Locked Screen</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719580284583-learn-hindi-like-a-native-speaker-explore-7-compelling-benefits-from-mondly-online-study/"><u>Learn Hindi Like a Native Speaker: Explore 7 Compelling Benefits From Mondly Online Study!</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-prohibited-application-red-flag-in-windows/"><u>Fixing the Prohibited Application Red Flag in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-device-engagement-in-power-save-mode/"><u>Maximizing Device Engagement in Power Save Mode</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-a2-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on A2.</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-realme-c55-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Realme C55 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-windows-activation-flaw-0x803f700f/"><u>Mastering the Resolution of Windows Activation Flaw 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-xc0000142-in-microsoft-oses/"><u>Remedying Error XC0000142 in Microsoft OSes</u></a></li>
</ul></div>

---
title: 3 Ways to Reset the Windows 11 Settings App
date: 2024-07-13T11:12:07.272Z
updated: 2024-07-14T11:12:07.272Z
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

 If you're a PowerShell enthusiast, why not take the time to learn these [useful Windows PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to improve efficiency?

## 3\. How to Reset the Windows 11 Settings App Using Command Prompt

 Another way to reset the Windows 11 Settings app is via Command Prompt. Similar to the method above, resetting the Settings app using Command Prompt only requires you to run a single command.

 To reset the Windows 11 Settings app using Command Prompt, use these steps:

1. Press**Win + X** or right-click the**start icon** to open the Power User menu and select**Run** from the list.
2. Type**cmd** in the text box and then press**Ctrl + Shift + Enter** on your keyboard to [open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#how-to-run-command-prompt-as-an-administrator-through-the-windows-search-tool) .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, paste the following command and hit**Enter** :  
`PowerShell -ExecutionPolicy Unrestricted -Command "& {$manifest = (Get-AppxPackage *immersivecontrolpanel*).InstallLocation + '\AppxManifest.xml' ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}"`

![Reset Settings App Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-settings-app-using-command-prompt.jpg)

 Once you run the above command, Windows will reset the Settings app on your computer.

 Do you find Command Prompt to be too complicated or boring to use? Here are some of [the best Command Prompt alternatives for Windows](https://www.makeuseof.com/best-command-prompt-alternatives-for-windows/) worth trying.

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
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-xiaomi-redmi-k70e-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Xiaomi Redmi K70E | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unblocked-windows-reviving-context-menus-swiftly/"><u>Unblocked Windows: Reviving Context Menus Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-and-prevent-windows-drive-vanishing/"><u>Pinpoint and Prevent Windows Drive Vanishing</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-from-disruption-to-deliberation-repairing-the-fidelity-of-frequencies/"><u>New From Disruption to Deliberation Repairing the Fidelity of Frequencies</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-applying-and-creating-gif-background-on-your-devices-and-presentations-is-not-hard-read-below-to-learn-how-to-apply-a-gif-background-on-all-devices-for-/"><u>New Applying and Creating Gif Background on Your Devices and Presentations Is Not Hard. Read Below to Learn How to Apply a GIF Background on All Devices for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-iphone-15-pro-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>In 2024, iPhone 15 Pro Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-stalker-unveiled-preventive-measures-against-wacatacbml/"><u>The Silent Stalker Unveiled: Preventive Measures Against Wacatac.B!ml</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-system-performance-wins-top-diagnostic-list/"><u>Smooth System Performance: Win's Top Diagnostic List</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-capturing-clarity-perfecting-image-description-via-text-in-pcmac/"><u>In 2024, Capturing Clarity  Perfecting Image Description via Text in PC/Mac</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-past-the-steam-file-access-hurdle/"><u>Stepping Past the Steam “File Access” Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-memory-efficiency-for-device-interaction-windows/"><u>Streamlining Memory Efficiency for Device Interaction Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-brightest-stars-in-tiktok-for-passion-drive-and-success/"><u>[Updated] In 2024, Brightest Stars in TikTok  For Passion, Drive, & Success</u></a></li>
<li><a href="https://win11.techidaily.com/windows-history-top-removed-and-evolved-characteristics/"><u>Windows History: Top Removed and Evolved Characteristics</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-robloxs-restrictive-error-403-on-pc/"><u>Unraveling Roblox's Restrictive Error 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-rectify-slow-windows-app-connections-for-peak-performance/"><u>Swiftly Rectify Slow Windows App Connections for Peak Performance</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-network-drive-setup-a-comprehensive-walkthrough/"><u>Win11's Network Drive Setup: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-imagecapture-reviews-hub/"><u>[New] In 2024, ImageCapture Reviews Hub</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/essential-guide-to-top-10-budget-friendly-podcasting-software-free/"><u>Essential Guide to Top 10 Budget-Friendly Podcasting Software (Free)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-vivo-y100-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Vivo Y100 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-sync-blueprint-for-android-plus-microsoft-os/"><u>The Perfect Sync Blueprint for Android + Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships.</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-access-control-personalized-windows-pin-creation/"><u>Revolutionize Access Control: Personalized Windows Pin Creation</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-the-hurdles-of-steams-wide-screen-display/"><u>Overcoming the Hurdles of Steam's Wide Screen Display</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-leaders-in-learning-top-15-online-science-hubs/"><u>2024 Approved  Leaders in Learning  Top 15 Online Science Hubs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-samsung-galaxy-a54-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Samsung Galaxy A54 5G Without PUK Codes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-vloggers-guide-to-choosing-camgear-the-top-9-innovations/"><u>In 2024, The Vlogger's Guide To Choosing CamGear - The Top 9 Innovations</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-itop-insider-review-top-notch-screencast-software-compared/"><u>In 2024, ITop Insider Review  Top-Notch Screencast Software Compared</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-spreading-smiles-crafting-visual-jokes-for-fbinstagram-shares/"><u>[New] 2024 Approved  Spreading Smiles  Crafting Visual Jokes for FB/Instagram Shares</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-adjustment-the-six-essential-techniques/"><u>Windows 11 Image Adjustment: The Six Essential Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-master-guide-to-choosing-your-mp4-player/"><u>[New] Master Guide to Choosing Your MP4 Player</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-computing-10-top-alternatives-to-windows-defaults/"><u>Redefining Computing: 10 Top Alternatives to Windows' Defaults</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-quick-solutions-for-cursor-on-black-screen/"><u>Win10/11: Quick Solutions for Cursor on Black Screen</u></a></li>
</ul></div>

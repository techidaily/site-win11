---
title: Methodology for Disabling OneDrive Indicator in Windows 11
date: 2024-07-13T09:47:24.250Z
updated: 2024-07-14T09:47:24.250Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methodology for Disabling OneDrive Indicator in Windows 11
excerpt: This Article Describes Methodology for Disabling OneDrive Indicator in Windows 11
keywords: Disable OneDrive Sign,Win11 Stop OneDrive LED,Turn Off OneDrive Icon,End OneDrive Light Display,Deactivate OneDrive Indicator,Suppress OneDrive Status Lamp,Halt Windows 11 OneDrive Glow
thumbnail: https://thmb.techidaily.com/4718cfe78df90fc96fd0823cd6a47f148478c5d534b3bf1b20e29d9f9fc07b91.jpg
---

## Methodology for Disabling OneDrive Indicator in Windows 11

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

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

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

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
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-admin-mode-execution-in-windows-console/"><u>Overcoming Failed Admin Mode Execution in Windows Console</u></a></li>
<li><a href="https://win11.techidaily.com/surging-downloads-overcome-the-01kbs-stall-on-windows/"><u>Surging Downloads: Overcome the 0.1KB/S Stall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-writing-errors-for-files-in-windows-systems/"><u>Overcoming Writing Errors for Files in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-splitcam-reviewed-topping-in-video-recording-technology/"><u>[New] SplitCam Reviewed  Topping in Video Recording Technology?</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-color-management-in-windows/"><u>Navigating the Nuances of Color Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-read-only-windows-folder-problems/"><u>Navigating and Resolving Read-Only Windows Folder Problems</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-key-syndrome-cure-for-muted-mouse-clicks/"><u>The Silent Key Syndrome: Cure for Muted Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-unidentified-hdd-situations/"><u>Navigating Through Unidentified HDD Situations</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-dissecting-iconic-discord-emoticons-and-their-designers/"><u>[Updated] 2024 Approved  Dissecting Iconic Discord Emoticons and Their Designers</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-screens-overcoming-windows-setup-woes/"><u>Secure Your Screens: Overcoming Windows Setup Woes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-browse-and-compare-leading-affordable-quality-webm-streamers/"><u>2024 Approved  Browse and Compare  Leading Affordable, Quality WebM Streamers</u></a></li>
<li><a href="https://win11.techidaily.com/solving-rdp-connectivity-issues-in-win10plus/"><u>Solving RDP Connectivity Issues in Win10+</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unlocking-igtvs-potential-5-ways-to-surge-follower-count/"><u>[Updated] In 2024, Unlocking IGTV's Potential  5 Ways to Surge Follower Count</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-realme-gt-3-screen-sharing-drfone-by-drfone-android/"><u>How To Do Realme GT 3 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-an-inactive-itunes-on-your-pc/"><u>How to Reactivate an Inactive iTunes on Your PC</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/breaking-into-livestreaming-your-pathway-to-youtube-and-twitch-via-obs-for-2024/"><u>Breaking Into Livestreaming  Your Pathway to YouTube & Twitch via OBS for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-regain-lost-content-after-an-unexpected-tiktok-reload/"><u>2024 Approved  Regain Lost Content After an Unexpected TikTok Reload</u></a></li>
<li><a href="https://win11.techidaily.com/merging-windows-credentials-with-microsoft-identity-hub/"><u>Merging Windows Credentials with Microsoft Identity Hub</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-windows-lock-screen-timer-breakage/"><u>Repairing Window's Lock Screen Timer Breakage</u></a></li>
<li><a href="https://win11.techidaily.com/install-windows-11-on-mac-with-parallels-step-by-step/"><u>Install Windows 11 on Mac with Parallels Step-by-Step</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/everything-you-need-to-know-about-unlocked-apple-iphone-15-drfone-by-drfone-ios/"><u>Everything You Need To Know About Unlocked Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-recordings-best-free-windows-programs/"><u>Perfect Your Recordings: Best FREE Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-dont-make-these-top-8-mistakes/"><u>Mastering Windows 11: Don't Make These Top 8 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-combat-breakpoint-exception-error-in-windows/"><u>Solutions to Combat Breakpoint Exception Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-youtube-banner-success-a-complete-strategy/"><u>In 2024, Mastering YouTube Banner Success  A Complete Strategy</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/professional-voice-capture-on-mac-compiling-the-best-5-apps/"><u>Professional Voice Capture on Mac  Compiling The Best 5 Apps</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-the-secrets-to-flawless-gopro-4k-edits/"><u>2024 Approved  Unveiling the Secrets to Flawless GoPro 4K Edits</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-master-the-art-of-video-cuts-essential-tools-for-mac-users/"><u>[New] In 2024, Master the Art of Video Cuts  Essential Tools for Mac Users</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-seamlessly-on-windows-1110-systems/"><u>Reinstating Synapse Seamlessly on Windows 11/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-flexibility-in-your-windows-environment-with-alomware/"><u>Maximize Flexibility in Your Windows Environment with AlomWare</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-transform-your-snap-game-with-these-top-tips-for-2024/"><u>[Updated] Transform Your Snap Game with These Top Tips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restore-steam-game-symbols-from-nowhere/"><u>Restore Steam Game Symbols From Nowhere</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-0x800700e1-on-w10w11/"><u>Resolving Error Code: 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-ultimate-video-lighting-effects-editors/"><u>Updated 2024 Approved Ultimate Video Lighting Effects Editors</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-meizu-21-pro-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Meizu 21 Pro Phones</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-windows-understanding-report-generation-and-analysis/"><u>The Art of Windows Understanding: Report Generation & Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functionality-to-windows-tablet-gestures/"><u>Restoring Full Functionality to Windows Tablet Gestures</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-10-key-strategies-to-enhance-insta-highlights/"><u>[Updated] 2024 Approved  10 Key Strategies to Enhance Insta Highlights</u></a></li>
</ul></div>

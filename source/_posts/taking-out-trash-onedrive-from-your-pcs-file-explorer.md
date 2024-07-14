---
title: "Taking Out Trash: OneDrive From Your PC's File Explorer"
date: 2024-07-13T10:45:55.092Z
updated: 2024-07-14T10:45:55.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Taking Out Trash: OneDrive From Your PC's File Explorer"
excerpt: "This Article Describes Taking Out Trash: OneDrive From Your PC's File Explorer"
keywords: File Explorer Uploads,OneDrive Syncing,Office Files Online,Share Documents Easily,Cloud Storage Access,Removing Data Clutter,Direct Drive Backup
thumbnail: https://thmb.techidaily.com/543a8e6d7f06f3d9129829edd8982dbf9c6a6048e52160481e81c4276bc515b3.jpg
---

## Taking Out Trash: OneDrive From Your PC's File Explorer

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
<li><a href="https://extra-hints.techidaily.com/leading-6-sites-transforming-how-companies-connect-socially/"><u>Leading 6 Sites Transforming How Companies Connect Socially</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-the-maze-of-unspecified-obs-error-in-windows/"><u>Navigate Through the Maze of Unspecified OBS Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-repairing-disk-errors-issue-on-windows/"><u>How to Fix the Repairing Disk Errors Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-devices-performance-naturally-with-wintoys/"><u>Accelerate Your Device's Performance Naturally with WinToys</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-older-directx-applications-through-dxvk-transformation/"><u>Bolstering Older DirectX Applications Through DXVK Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-lighten-load-time-for-epic-games-on-windows/"><u>How to Lighten Load Time for Epic Games on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-top-lyric-video-creation-tools/"><u>Updated In 2024, Top Lyric Video Creation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-windows-11-registry-file-layout/"><u>Mastering the Windows 11 Registry File Layout</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-intelligence-of-microsofts-marketplace/"><u>Navigating the Intelligence of Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-up-advanced-security-features-ms-defender-aguard-for-windows-11-edge/"><u>How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-roadblocks-in-windows-app-functionality/"><u>Overcoming Common Roadblocks in Windows App Functionality</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-broadcast-your-online-meeting-via-youtube-google-meet-steps/"><u>[Updated] 2024 Approved  How To Broadcast Your Online Meeting via YouTube - Google Meet Steps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-easy-to-follow-setting-up-snapchat-on-a-mac/"><u>[Updated] In 2024, Easy to Follow  Setting up Snapchat on a Mac</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-cross-language-interactions-with-keyboard-shortcuts-on-windows-11/"><u>Enhance Cross-Language Interactions with Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-savings-with-windows-11-pro-secure-top-deals/"><u>Maximize Savings with Windows 11 Pro: Secure Top Deals</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-and-redo-store-registrations-in-win-11/"><u>How to Reset and Redo Store Registrations in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-windows-11-harnessing-background-blur-in-photos-app/"><u>Masterful Windows 11: Harnessing Background Blur in Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-proper-techniques-for-streaming-from-gopro-camera-to-social-networks/"><u>2024 Approved  Proper Techniques for Streaming From GoPro Camera to Social Networks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-1111/"><u>How to Install Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-in-windows-11-after-disruptions/"><u>Enhancing Wi-Fi Connectivity in Windows 11 After Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-savings-black-friday-6e2-win10-forever/"><u>Unmatched Savings: Black Friday - $6E2 (Win10) Forever</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-linux-use-without-wsl/"><u>Uncomplicated Linux Use Without WSL</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-for-frozen-keys-in-snipping-tool/"><u>Immediate Solution for Frozen Keys in Snipping Tool</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/supercharge-visual-and-aural-aspects-of-media-content/"><u>Supercharge Visual & Aural Aspects of Media Content</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-compatibility-checklist-tool/"><u>Navigating Windows 11'S Compatibility Checklist Tool</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-invalid-identifier-error-in-win11/"><u>Guide to Correct 'Invalid Identifier' Error in Win11</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-14-pro-max-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 14 Pro Max Data From iOS iTunes | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/youtubes-essential-view-total-to-secure-income/"><u>YouTube's Essential View Total to Secure Income</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-app-install-failure-on-microsofts-marketplace/"><u>Addressing App Install Failure on Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/cpu-age-determination-for-pc-users-8-effective-methods/"><u>CPU Age Determination for PC Users: 8 Effective Methods</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-snap-and-share-the-brief-vlog-age-for-2024/"><u>[New] Snap & Share  The Brief Vlog Age for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-video-editing-mastery-top-picks-for-apple-users/"><u>New Video Editing Mastery Top Picks for Apple Users</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-stalled-win11-license-numbers/"><u>Breathing Life Into Stalled Win11 License Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/end-of-windows-subsystem-preparing-for-androids-future/"><u>End of Windows Subsystem: Preparing For Android's Future</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-amplifying-presence-top-30plus-bio-strategies-for-filmora-creators-to-grow-followers/"><u>In 2024, Amplifying Presence  Top 30+ Bio Strategies for Filmora Creators to Grow Followers</u></a></li>
<li><a href="https://win11.techidaily.com/6-effective-techniques-to-resurrect-off-screen-windows-in-windows-11/"><u>6 Effective Techniques to Resurrect Off-Screen Windows in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-the-mysterious-windows-subsystem-for-linux-error-4294967295/"><u>Handling the Mysterious Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-spiritual-command-center-of-windows-11-os/"><u>Unlocking The Spiritual Command Center of Windows 11 OS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-novice-to-pro-mastering-spotify-advertisement-techniques/"><u>In 2024, From Novice to Pro  Mastering Spotify Advertisement Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-win11-powertoys-experience/"><u>Unveiling the Win11 PowerToys Experience</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-mcuicnt-file-access-problem-on-pcs/"><u>Mitigating McUICnt File Access Problem on PCs</u></a></li>
</ul></div>

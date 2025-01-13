---
title: Techniques for Eradicating OneDrive From Explorer Window
date: 2025-01-07T19:57:19.215Z
updated: 2025-01-12T17:26:35.015Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Eradicating OneDrive From Explorer Window
excerpt: This Article Describes Techniques for Eradicating OneDrive From Explorer Window
keywords: Remove Drives From Explorer,Eliminate OneDrive Explorer,Clearing OneDrive Windows,Banish OneDrive Explorer,Erase OneDrive Window Access,Forbid OneDrive Explorer Link,Purge OneDrive Explorer
thumbnail: https://thmb.techidaily.com/194a7e702c94714cd1ade34a1eef99f1c71a4608c10e7d8eb07bd33367c48152.jpg
---

## Techniques for Eradicating OneDrive From Explorer Window

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/updated-the-abcs-of-amassing-affection-on-fb-squaring-up-your-video-strategy/"><u>[Updated] The ABC's of Amassing Affection on FB Squaring Up Your Video Strategy</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-unmanned-vehicles-classified-for-2024/"><u>[Updated] Unmanned Vehicles - Classified for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-steam-login-interruptions-via-rust-for-windows-enthusiasts/"><u>Combatting Steam Login Interruptions via Rust for Windows Enthusiasts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-tecno-phantom-v-flip-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Tecno Phantom V Flip</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-nokia-c110-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Nokia C110 Location Settings | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/experience-the-next-wave-watching-fb-live-on-roku-for-2024/"><u>Experience the Next Wave Watching FB Live on Roku for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-epson-workforce-ds-30-ready-on-windows-1187-with-new-driver-download/"><u>Get Your Epson WorkForce DS 30 Ready on Windows 11/8/7 with New Driver Download</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-samsung-galaxy-m14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-some-outdated-your-hardware-drivers-with-windows-device-manager-in-windows-7-by-drivereasy-guide/"><u>How to identify some outdated your hardware drivers with Windows Device Manager in Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-achievement-roadblocks-on-steam-games/"><u>Overcoming Achievement Roadblocks on Steam Games</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-google-chromes-aw-snap-error/"><u>Overcoming Google Chrome’s Aw, Snap! Error</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-windows-voice-to-text-program-through-whisper-and-autohotkey/"><u>Personalized Window's Voice-to-Text Program Through Whisper & AutoHotkey</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-microphone-record-with-confidence/"><u>Windows 11 Microphone: Record with Confidence</u></a></li>
<li><a href="https://win11.techidaily.com/windows-modern-standby-uncovered-issues-and-impacts/"><u>Windows Modern Standby Uncovered: Issues & Impacts</u></a></li>
</ul></div>


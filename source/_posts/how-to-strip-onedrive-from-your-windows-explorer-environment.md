---
title: How To Strip OneDrive From Your Windows Explorer Environment
date: 2024-09-18T21:17:43.799Z
updated: 2024-09-22T08:10:32.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Strip OneDrive From Your Windows Explorer Environment
excerpt: This Article Describes How To Strip OneDrive From Your Windows Explorer Environment
keywords: Remove OneDrive,Strip OneDrive,Eliminate OneDrive,Disable OneDrive,Remove Files,Unlink OneDrive,Detach Cloud Storage,Remove,Strip,Eliminate,Disable,Unlink
thumbnail: https://thmb.techidaily.com/c6a00ed9bc739f2f19c543f786366f0b15e1dcc95bf3f36705f1220c5880cb1d.jpg
---

## How To Strip OneDrive From Your Windows Explorer Environment

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<li><a href="https://some-techniques.techidaily.com/new-innovations-in-crafting-engaging-vlogging-scripts/"><u>[New] Innovations in Crafting Engaging Vlogging Scripts</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-masterful-multimedia-publishing-videos-on-the-worlds-most-popular-social-network/"><u>[Updated] 2024 Approved Masterful Multimedia Publishing Videos on the World's Most Popular Social Network</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-snap-up-on-details-with-videoleaps-advanced-zooming-for-2024/"><u>[Updated] Snap Up on Details with VideoLeap's Advanced Zooming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/flagiconnga-chinwendu-ihezuo-sheikh-jamal-dhanmondi-club-10-goals-chinwendu-ihezuo-29-total-in-all-tournaments/"><u>{{Flagicon|NGA}} Chinwendu Ihezuo (Sheikh Jamal Dhanmondi Club, 10 Goals) Chinwendu Ihezuo '''29 Total in All Tournaments :'''</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-for-minimizing-dvd-storage-footprint-using-premier-compression-programs/"><u>Effective Techniques for Minimizing DVD Storage Footprint Using Premier Compression Programs</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-transform-high-resolution-4k-content-into-1080p-with-ease/"><u>Effective Techniques: Transform High-Resolution 4K Content Into 1080P with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-dvd-formatting-tips-and-techniques-for-windows-users/"><u>Effortless DVD Formatting Tips and Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/encouraging-readers-to-consider-homestays-or-volunteer-exchanges-for-authentic-local-experiences/"><u>Encouraging Readers to Consider Homestays or Volunteer Exchanges for Authentic Local Experiences.</u></a></li>
<li><a href="https://win11.techidaily.com/get-free-downloads-access-your-favorite-movies-and-tunes-from-anywhere/"><u>Get Free Downloads: Access Your Favorite Movies & Tunes From Anywhere</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-7-innovative-approaches-to-color-correction/"><u>In 2024, 7 Innovative Approaches to Color Correction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-pairing-process-how-to-successfully-link-airpods-with-windows-11/"><u>Mastering the Pairing Process: How to Successfully Link AirPods with Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On OnePlus Nord N30 SE? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-troubleshooting-and-repairing-hewlett-packard-code-e43-faults/"><u>Step-by-Step Guide: Troubleshooting and Repairing Hewlett-Packard Code E43 Faults</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


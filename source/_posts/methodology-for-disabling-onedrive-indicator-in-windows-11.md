---
title: Methodology for Disabling OneDrive Indicator in Windows 11
date: 2024-06-25T11:23:04.630Z
updated: 2024-06-26T11:23:04.630Z
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
<li><a href="https://win11.techidaily.com/unlocking-artistic-freedom-starting-microsoft-paint-on-windows-11/"><u>Unlocking Artistic Freedom: Starting Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/10-quick-tips-recognizing-your-xbox-controller-in-windows/"><u>10 Quick Tips: Recognizing Your Xbox Controller in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-use-estimating-windows-app-size/"><u>Efficient Use: Estimating Windows App Size</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-seamless-program-deployment/"><u>Navigating Windows 11'S Seamless Program Deployment</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-invalid-label-error-on-windows-11/"><u>Guide to Rectify 'Invalid Label' Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-11-ui/"><u>The Essentials of Windows 11 UI</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-ultimate-list-of-video-editors-with-music-integration/"><u>New The Ultimate List of Video Editors with Music Integration</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-intricacies-of-omegle-a-comprehensive-guide-to-its-functioning-and-safety-measures-for-2024/"><u>The Intricacies of Omegle A Comprehensive Guide to Its Functioning and Safety Measures for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevating-your-chromebooks-zoom-experience/"><u>Elevating Your Chromebook's Zoom Experience</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-unlocking-the-archive-of-yesteryear-how-to-view-facebook-past-content/"><u>In 2024, Unlocking the Archive of Yesteryear  How To View Facebook Past Content</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-resolving-common-instagram-video-glitches-for-2024/"><u>[Updated] Resolving Common Instagram Video Glitches for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-novel-set-of-pertinent-probing-for-podcast-participants/"><u>In 2024, Novel Set of Pertinent Probing for Podcast Participants</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-vidstreamer-for-social-platforms/"><u>[Updated] 2024 Approved  VIDStreamer for Social Platforms</u></a></li>
<li><a href="https://change-location.techidaily.com/list-of-pokemon-go-joysticks-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-free-video-orientation-correction-tools-for-iphone/"><u>Updated Best Free Video Orientation Correction Tools for iPhone</u></a></li>
</ul></div>

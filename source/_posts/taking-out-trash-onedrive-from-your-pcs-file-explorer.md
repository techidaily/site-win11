---
title: "Taking Out Trash: OneDrive From Your PC's File Explorer"
date: 2024-06-25T11:39:17.794Z
updated: 2024-06-26T11:39:17.794Z
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
<li><a href="https://win11.techidaily.com/exclusive-single-board-compatible-with-windows/"><u>Exclusive Single-Board Compatible with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-screenshot-feature-to-suit-your-preferences/"><u>Tailor Windows Screenshot Feature to Suit Your Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/leading-painting-programs-beyond-the-procreate-window-experience/"><u>Leading Painting Programs Beyond the Procreate Window Experience</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-unused-disk-space-in-windows-efficiently/"><u>Harnessing Unused Disk Space in Windows Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/stop-blue-screen-bsos-quick-fix-strategies-for-win11/"><u>Stop Blue Screen BSOS: Quick Fix Strategies for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inability-to-install-windows-store-apps/"><u>Resolving Inability to Install Windows Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-savings-black-friday-6e2-win10-forever/"><u>Unmatched Savings: Black Friday - $6E2 (Win10) Forever</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enablingdisabling-multitasking-in-safari-devices/"><u>Enabling/Disabling Multitasking in Safari Devices</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/1713954156148-updated-in-2024-how-to-make-boring-videos-look-cool-by-b-rolls/"><u>Updated In 2024, How To Make Boring Videos Look Cool By B Rolls</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-55-best-tiktok-comedy-joke-threads/"><u>[Updated] 2024 Approved  55 Best TikTok Comedy Joke Threads</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-ultimate-list-of-imovie-alternatives-for-windows-11-and-10-for-2024/"><u>Updated The Ultimate List of iMovie Alternatives for Windows 11 and 10 for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/transforming-youtube-videos-into-cash-flows/"><u>Transforming YouTube Videos Into Cash Flows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-screencast-mastery-guide-essential-tips-unveiled/"><u>[Updated] Screencast Mastery Guide  Essential Tips Unveiled</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-experts-to-follow-on-igtv/"><u>[Updated] In 2024, Experts to Follow on IGTV</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/infuse-harmonies-into-motion-picture-sequences-using-media-encrypter-for-2024/"><u>Infuse Harmonies Into Motion Picture Sequences Using Media Encrypter for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-unleash-creativity-with-step-by-step-voice-modification-on-tiktok-for-2024/"><u>[New] Unleash Creativity with Step-by-Step Voice Modification on TikTok for 2024</u></a></li>
</ul></div>

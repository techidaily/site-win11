---
title: How To Strip OneDrive From Your Windows Explorer Environment
date: 2024-09-10T17:27:44.804Z
updated: 2024-09-17T04:42:24.073Z
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-quick-adjustment-invert-playback-on-vlc-interface/"><u>[New] 2024 Approved Quick Adjustment Invert Playback on VLC Interface</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-ultimate-guide-to-instas-trendy-filters/"><u>[New] 2024 Approved The Ultimate Guide to Insta's Trendy Filters</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-7-best-apps-to-go-live-on-youtube-from-iphone-or-android-for-2024/"><u>[New] 7 Best Apps to Go Live on YouTube From iPhone or Android for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-through-slug-line-syntax-in-screenplays/"><u>[Updated] Navigating Through Slug Line Syntax in Screenplays</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-0x80040610-a-tactical-approach-to-outlook-repair/"><u>Eliminating Error 0X80040610: A Tactical Approach to Outlook Repair</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/enhance-your-training-routine-with-garmin-vivoactive-3s-music-feature-for-athletes/"><u>Enhance Your Training Routine with Garmin Vivoactive 3'S Music Feature for Athletes</u></a></li>
<li><a href="https://win11.techidaily.com/hack-the-store-glitch-defeating-error-code-x80072f30-on-pc/"><u>Hack the Store Glitch: Defeating Error Code X80072F30 on PC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-12-drfone-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/language-mastery-face-off-determining-the-best-between-chatgpt-and-google-translate-for-seamless-communication/"><u>Language Mastery Face-Off: Determining the Best Between ChatGPT and Google Translate for Seamless Communication</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-c0000005-errors-in-windows/"><u>Mastering the Art of Fixing C0000005 Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-lunar-client-launch-hurdle/"><u>Overcoming Windows' Lunar Client Launch Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-eliminating-minecraft-win-error-1/"><u>Quick Remedies for Eliminating Minecraft Win Error: 1</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->


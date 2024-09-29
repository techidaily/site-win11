---
title: Streamlining Your File Explorer by Omitting OneDrive
date: 2024-09-24T23:27:08.543Z
updated: 2024-09-29T00:31:55.421Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining Your File Explorer by Omitting OneDrive
excerpt: This Article Describes Streamlining Your File Explorer by Omitting OneDrive
keywords: Streamlined Folder Views,DropOneDrive,OptimizeFileExplorer,ExcludeDriveIntegration,SimplifyWindowsStorage,RemoveOneDriveFiles,EfficientFolderNavigation
thumbnail: https://thmb.techidaily.com/9d3732c41a53a8a22c767ec42385e845ec206bbdbcdafbf7af2a45ba4a50f286.jpg
---

## Streamlining Your File Explorer by Omitting OneDrive

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-skills.techidaily.com/updated-pixel-perfecting-free-high-quality-mobile-photography-boost/"><u>[Updated] Pixel Perfecting Free, High-Quality Mobile Photography Boost</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-what-does-instantaneous-video-removal-mean-for-user-privacy-for-2024/"><u>[Updated] What Does Instantaneous Video Removal Mean for User Privacy for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-precision-video-correction-eradicating-fish-eye-from-gopro/"><u>2024 Approved Precision Video Correction Eradicating Fish Eye From GoPro</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/directing-youtube-media-to-your-facebook-profile-and-feed-for-2024/"><u>Directing YouTube Media to Your Facebook Profile and Feed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-text-glyphs-in-windows-11/"><u>Discovering Text Glyphs in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-for-identifying-high-space-usage-windows/"><u>Effective Strategies for Identifying High-Space Usage Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-taskbar-clarity-with-w11-tricks/"><u>Enhancing Your Taskbar Clarity with W11 Tricks</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-a05s-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel A05s to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-to-apple-iphone-12-drfone-by-drfone-ios/"><u>In 2024, How to Mirror PC to Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/multitasking-made-simple-windows-1110-window-cascade-guide/"><u>Multitasking Made Simple: Windows 11/10 Window Cascade Guide</u></a></li>
<li><a href="https://win11.techidaily.com/premium-laptops-highlighted-at-ifa-2023/"><u>Premium Laptops Highlighted at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-cameras-to-device-manager-display/"><u>Reintroduce Missing Cameras to Device Manager Display</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unlinked-files-and-absence-of-assigned-apps-win/"><u>Resolving Unlinked Files and Absence of Assigned Apps (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-performance-of-a-non-responsive-windows-folder/"><u>Strategies to Improve Performance of a Non-Responsive Windows Folder</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/superior-non-zoom-virtual-collaboration-options/"><u>Superior Non-Zoom Virtual Collaboration Options</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-honor-x8b-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Honor X8b Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>


---
title: Step-by-Step to Delete OneDrive Icon in Windows Explore
date: 2024-06-25T10:18:24.318Z
updated: 2024-06-26T10:18:24.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step to Delete OneDrive Icon in Windows Explore
excerpt: This Article Describes Step-by-Step to Delete OneDrive Icon in Windows Explore
keywords: Deleting OneDrive Icon,OneDrive Removal Guide,Remove OneDrive Explorer Icon,Uninstall OneDrive Windows,Stop OneDrive Icons,Clearing OneDrive in IE,Easy OneDrive Disable
thumbnail: https://thmb.techidaily.com/6af9f284b317fd0fc6915e0019f4adbc9dd81ab605d1c55ebd68e10c11778128.png
---

## Step-by-Step to Delete OneDrive Icon in Windows Explore

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
<li><a href="https://win11.techidaily.com/bypassing-installation-obstacles-for-app-removal-in-windows-11/"><u>Bypassing Installation Obstacles for App Removal in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-code-3-error-in-nvidia-opengl-win1011/"><u>Techniques to Address Code 3 Error in Nvidia OpenGL (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-up-to-full-operating-system-windows-for-steam-deck/"><u>Stepping Up to Full Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-auto-clickers-with-hotkeys-for-windows/"><u>The 5 Best Auto Clickers With Hotkeys for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-non-operational-ccleaner-on-win11/"><u>Overhauling Non-Operational CCleaner on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-spatial-capability-with-windows-11-settings/"><u>Unleash Full Spatial Capability with Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-reclaiming-faulty-usb-connectivity-windows/"><u>Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-photos-app-background-blur-feature-on-windows-11/"><u>How to Use the Photos App Background Blur Feature on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/regain-access-to-microsoft-store-features-on-pcs/"><u>Regain Access to Microsoft Store Features on PCs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elemental-story-framework/"><u>Elemental Story Framework</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-perfecting-sound-levels-in-recordings-step-by-step-guide/"><u>[New] In 2024, Perfecting Sound Levels in Recordings  Step-by-Step Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-how-to-save-funny-tweet-graphics-gifs-in-minutes/"><u>[New] In 2024, How To Save Funny Tweet Graphics (GIFs) in Minutes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gaining-insights-how-to-ask-the-right-questions/"><u>2024 Approved  Gaining Insights  How to Ask the Right Questions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-meme-mayhem-top-twenty-from-reddit-and-twitter-for-2024/"><u>[New] Meme Mayhem  Top Twenty From Reddit & Twitter for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-live-screen-archive-aggregators/"><u>[New] 2024 Approved  Live Screen Archive Aggregators</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-become-a-cartoon-star-best-apps-for-transforming-your-photos-on-iphone-and-android-for-2024/"><u>New Become a Cartoon Star Best Apps for Transforming Your Photos on iPhone and Android for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-downloading-twitters-animated-content-simplified-for-2024/"><u>[New] Downloading Twitter's Animated Content Simplified for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/creating-your-own-path-on-youtube-a-course-guide/"><u>Creating Your Own Path on YouTube  A Course Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/spotlight-on-5-captivating-book-viddies/"><u>Spotlight on 5 Captivating Book Viddies</u></a></li>
</ul></div>

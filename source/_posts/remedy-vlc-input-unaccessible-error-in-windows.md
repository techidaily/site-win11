---
title: Remedy VLC Input Unaccessible Error in Windows
date: 2024-12-30T16:42:03.669Z
updated: 2025-01-06T20:06:28.158Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy VLC Input Unaccessible Error in Windows
excerpt: This Article Describes Remedy VLC Input Unaccessible Error in Windows
keywords: Fix VLC Access Error,Resolve VLC Unavailability,VLC Playback Issue Windows,Stop VLC Input Error,Unlock VLC Media Player,VLC Streaming Problems,End VLC Incompatibility
thumbnail: https://thmb.techidaily.com/a04f09fd3f332adf9ea1d2c4b6687272d88f08a364f88560f34c633d621d6cbc.jpg
---

## Remedy VLC Input Unaccessible Error in Windows

 It is not often that VLC Media Player fails to play a file. But sometimes, when you try to open a media file, you may encounter the "your input can’t be opened" error on VLC. This error can occur with both local media files and when you try to stream a YouTube video, albeit for different reasons.

 Invalid file or folder name, issues with the VLC media player, and issues with YouTube.luac file are the common causes of this error. If you experience this error, here are a few quick fixes to resolve the "your input can’t be opened" VLC error on Windows.

 If the error occurs when streaming a YouTube video, skip to the fourth solution in this guide.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Change the File/Folder Path

![copy folder file move windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/copy-folder-file-move-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The "your input can’t be opened" error can occur if the folder path for the saved media is too long. For example, if your file is saved in D:\\Users\\Downloads\\Media\\New\\Files, moving it to a main folder such as**D:\\Users** can fix the issue.

To move the media file to a different folder:

1. Press**Win + E** to open**File Explorer** .
2. Next, navigate to the folder where your media files are saved.
3. Right-click on the media file and select**Copy** .
4. Next, create a new folder in**D:\\Users** and paste the file. Now open the file to see if it plays without the error.

## 2\. Change Folder or File Name

![rename file folder windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/rename-file-folder-windows-11.jpg)

 If you have a large folder with hundreds of media files,[renaming the folder or file on Windows](https://www.makeuseof.com/windows-11-rename-files/) can help you fix this error. Try to rename the folder with a short name to fix the error.

 That said, if the issue is with individual files, try to rename the video file to something simple without using any special characters. Even if the original file name has no visible special characters, rename it with a random name and then try to play the media.

To rename the folder:

1. Press**Win + E** to open**File Explorer** .
2. Next, navigate to the folder which has your media files with errors.
3. Select and right-click on the folder.
4. Select the**Rename** option from the context menu. Alternatively, press**F2** on your keyboard to access the rename option.
5. Rename the folder or file to a small name than the current folder name. Avoid using any special characters.
6. Once renamed, open the folder and play any media file with the error to see if the problem is resolved.

## 3\. Reset VLC Media Player Preference

 VLC offers tons of customization options. If the error is triggered after making a change to the VLC media player, you can reset the preferences to fix the issue.

 Note that when you reset preferences, you will lose all the changes made to your VLC media player. To reset VLC's preferences:

1. Launch the**VLC Media Player** and click on**Tools** .
2. Select**Preferences** from the context menu. Alternatively, press**Ctrl + P** to open the Simple Preferences dialog.  
![vlc media player preferences](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/vlc-media-player-preferences.jpg)
3. In the**Interface** tab, scroll down and click on**Reset Preferences.**  

![reset preferences vlc media player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-preferences-vlc-media-player.jpg)
4. Click**OK** when the **Are you sure you want to reset your VLC media player preferences** dialog appears.
5. Relaunch the VLC media player and try to play the media file to see if the error is resolved.

## 4\. Modify the Youtube.luac VLC File to Fix Issues With YouTube Video Steaming

 When trying to stream a YouTube video, you may encounter the VLC is unable to open the MRL error. To fix the YouTube streaming error on VLC, you’ll need to modify an associated YouTube.luac file and replace it with a new script available on GitHub. Here’s how to do it.

1. Open the[GitHub page for the YouTube.luac file](http://github.com/videolan/vlc/blob/master/share/lua/playlist/youtube.lua) .
2. Next, select all the content of the script on the YouTube.luac page. Alternatively, click the**Copy raw content** button in the top right corner to copy the code to your clipboard.  
![youtube luac code script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/youtube-luac-code-script.jpg)
3. Next, press the**Win key** and type**VLC** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Right-click on the VLC Media Player icon and select**Open File Location.**  
![open vlc media player file location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-vlc-medai-player-file-location.jpg)
5. Next, right-click again on the**VLC media player** icon in the new**File Explore** tab and select**Open file location.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Here, locate and open the**lua** folder.
2. Next, open the**playlist** folder.
3. Locate and right-click on the**youtube.luac** file.  
![edit youtube luac file vlc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-youtube-luac-file-vlc.jpg)
4. Select**Open with** and select**Notepad++** or another text file editor to open the file.  
![youtube luac script save](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/youtube-luac-script-save.jpg)
5. When the file opens, press**Ctrl + A** to select all the contents of the file. Then, press**Ctrl + V** to paste the script copied from the GitHub page for VLC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Press**Ctrl + S** and click**Yes** to confirm the action.

 Once the file is saved, launch VLC and check if the error is resolved. If not, try to create a new text file with the above script and save it as**youtube.lua** . Next, delete the**youtube.luac** file in**VLC\\lua\\playlist** and then move the**youtube.lua** file to the same folder. Try to stream any YouTube video via VLC to check if the error is resolved.

## 5\. Take Ownership of the Media File

 You can[take ownership of a file in Windows](https://www.makeuseof.com/take-ownership-of-windows-files-and-folders-with-these-tools/) to fix the "your input can’t be opened" error in VLC. Taking ownership should work if the error is triggered due to insufficient permission to access the file.

To take ownership of a media file:

1. Open**File Explorer** and navigate to the location where the file is stored.
2. Right-click on the media file and select**Properties** .  
![properties media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/properties-media.jpg)
3. In the**Properties** dialog, open the**Security** tab.
4. Next, click the**Advanced** button.  
![file properties advanced security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-properties-advanced-security.jpg)
5. Click the**Change** button for**Owner** .  

![file properties advanced security change owner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-properties-advanced-security-change-owner.jpg)
6. Next, type your user account name in the**Enter** t**he object name to select the** field and click**Check Names.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![file properties advanced security change owner select user group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-properties-advanced-security-change-owner-select-user-group.jpg)
7. If the user is found, click**OK** .

8. Click**Apply** and**OK** on all the open dialogs to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reinstall VLC Media Player

 In rare instances, the error can be due to an issue with the VLC app. If none of the solutions above work, try to uninstall and reinstall VLC to see if that helps fix the error.

To uninstall the VLC media player:

1. Press**Win + I** to open**Settings** .
2. Next, open the**Apps** tab in the left pane.  
![windows 11 view installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-view-installed-apps.jpg)
3. Click on**Installed apps** and then search for VLC.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![uninstall vlc media player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-vlc-media-player.jpg)
4. Click the**three-dots menu** for the VLC media player and select**Uninstall** . Click**Uninstall** once again to confirm the action.
5. Once uninstalled, open the[VLC media player page](https://www.videolan.org/vlc/) and download the installer. Install the app and check for any improvements.

## Invalid File Name and Long File Path Triggers This Error

 If the error occurs when playing a local media file, you can fix it by renaming it or moving it to a different folder. Often an invalid file name issue seem to trigger this error on VLC. However, to fix the issue while streaming a YouTube video, you’ll need to modify the youtube.luac file and add the new code to make it work again.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-craft-standout-videos-mastery-of-youtube-thumbnail-dimensions/"><u>[New] 2024 Approved How to Craft Standout Videos Mastery of YouTube Thumbnail Dimensions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-a-detailed-look-at-successful-valheim-sowing-for-2024/"><u>[New] A Detailed Look at Successful Valheim Sowing for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-top-12-best-tycoon-games-guaranteed-to-hook-you-for-2024/"><u>[Updated] Top 12 Best Tycoon Games Guaranteed to Hook You for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-poco-c50-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Poco C50 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-techniques-for-effortless-background-blur-using-windows-11-photos/"><u>Cutting Edge Techniques for Effortless Background Blur Using Windows 11 Photos</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ultimate-4-windows-webp-viewers/"><u>Discover the Ultimate 4 Windows WebP Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/effective-utilization-of-ping-commands-in-windows-networks/"><u>Effective Utilization of Ping Commands in Windows Networks</u></a></li>
<li><a href="https://fox-glue.techidaily.com/effortless-srt-conversion-the-ultimate-txt-solution-in-a-flash/"><u>Effortless SRT Conversion The Ultimate TXT Solution in a Flash</u></a></li>
<li><a href="https://buynow-help.techidaily.com/kobo-nia-overview-and-review-a-formidable-challenger-in-the-kindle-ecosystem/"><u>Kobo Nia Overview and Review: A Formidable Challenger in the Kindle Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-event-log-failures-in-windows-11/"><u>Overcoming Event Log Failures in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-deactivated-thermal-control-on-winpc/"><u>Overhauling Deactivated Thermal Control on WinPC</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-javascript-catastropes-windows-11-and-11-s-solutions-for-discord/"><u>Resolve Javascript Catastropes: Windows 11 & 11 S Solutions for Discord</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-back-to-original-touch-key-settings-on-windows/"><u>Reverting Back to Original Touch Key Settings on Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-persistent-problem-wallpaper-engine-stability-improvements-for-windows-users/"><u>Solving the Persistent Problem: Wallpaper Engine Stability Improvements for Windows Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/synergistic-computing-chatgpt-and-the-apple-ecosystem/"><u>Synergistic Computing: ChatGPT and the Apple Ecosystem</u></a></li>
</ul></div>


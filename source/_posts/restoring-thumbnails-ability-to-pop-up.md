---
title: Restoring Thumbnails' Ability to Pop Up
date: 2024-11-05T22:42:09.856Z
updated: 2024-11-07T21:35:00.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Thumbnails' Ability to Pop Up
excerpt: This Article Describes Restoring Thumbnails' Ability to Pop Up
keywords: Thumbnail Trigger,Image Popup Revival,Restore Thumbs Functionality,Thumbnail Clickability,Recovering Thumbnails,Enhancing Thumbnail Response,Thumbnails Resuscitation
thumbnail: https://thmb.techidaily.com/c7f5000e41b71ee026b5d1dc2b4d2e4d8155a2a1a3717610151f0f8cc3caeaae.jpg
---

## Restoring Thumbnails' Ability to Pop Up

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100530/7443" target="_top" id="2100530">
  <img src="//a.impactradius-go.com/display-ad/7443-2100530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-the-art-of-igtv-on-instagram-stories-for-2024/"><u>[New] Mastering the Art of IGTV on Instagram Stories for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-essential-techniques-for-fast-forwarding-in-spotify/"><u>[Updated] 2024 Approved The Essential Techniques for Fast-Forwarding in Spotify</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-what-is-t-series-income-on-youtube/"><u>2024 Approved What Is T Series Income on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-window-11-lock-patterns/"><u>Crafting Unique Window 11 Lock Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-virtual-experience-moving-to-virtualbox-v70-on-windows-11/"><u>Elevating Your Virtual Experience: Moving to VirtualBox v7.0 on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-how-to-expose-and-rectify-vanished-videos-on-fb/"><u>In 2024, How to Expose and Rectify Vanished Videos on FB</u></a></li>
<li><a href="https://win11.techidaily.com/installing-windows-compressed-archive-cab-files-simplified/"><u>Installing Windows Compressed Archive (CAB) Files Simplified</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/making-audio-files-out-of-instagram-videos/"><u>Making Audio Files Out of Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11s-dialer/"><u>Navigate to Windows 11'S Dialer</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-system-rename-user-folders-win11-style/"><u>Optimize Your System: Rename User Folders, Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-notification-failures-in-outlook-top-strategies-for-windows-users/"><u>Overcoming Notification Failures in Outlook: Top Strategies for Windows Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-samsung-galaxy-m14-5g-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Samsung Galaxy M14 5G and Browser | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revolutionized-action-recording-with-tomtoms-newest-bandit-for-2024/"><u>Revolutionized Action Recording with TomTom's Newest Bandit for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-reversing-text-entry-errors-in-windows/"><u>Strategies for Reversing Text Entry Errors in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-infinix-smart-7-hd-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Infinix Smart 7 HD Phone Pattern Lock</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-restart-non-operational-nvidia-cp-win11/"><u>Tips to Restart Non-Operational NVidia CP, Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/transforming-your-instagram-films-with-border-magic-for-2024/"><u>Transforming Your Instagram Films with Border Magic for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-top-windows-based-ndsswitch-games/"><u>Ultimate Guide: Top Windows-Based NDS/Switch Games</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
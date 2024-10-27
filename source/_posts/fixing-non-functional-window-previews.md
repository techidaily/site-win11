---
title: Fixing Non-Functional Window Previews
date: 2024-10-24T17:26:49.525Z
updated: 2024-10-26T17:24:34.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Non-Functional Window Previews
excerpt: This Article Describes Fixing Non-Functional Window Previews
keywords: Fix Window Preview Issues,Unfreeze Windows,Resolve Frozen Screens,Window Preview Reset,Prevent Freezing Errors,Enhance Window Viewing,Optimize Display Windows
thumbnail: https://thmb.techidaily.com/e6c6b6e32249dbf76f20abd6c6055b57975d7da74a0ada4b319cc0a746113075.jpg
---

## Fixing Non-Functional Window Previews

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

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
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
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-the-goofy-way-a-look-back-at-the-90s-comedy-vhs/"><u>[New] 'The Goofy Way' A Look Back at the 90S Comedy VHS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-a-comprehensive-list-of-excellent-fb-cover-photo-creators/"><u>[Updated] 2024 Approved A Comprehensive List of Excellent FB Cover Photo Creators</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-viral-beats-to-ringtones-transforming-tiktok-sounds/"><u>[Updated] From Viral Beats to Ringtones Transforming TikTok Sounds</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-step-by-step-blueprint-for-impressive-photographic-mosaics/"><u>[Updated] Step-by-Step Blueprint for Impressive Photographic Mosaics</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-smudge-solution-blurring-visions-in-video-content/"><u>[Updated] The Smudge Solution Blurring Visions in Video Content</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-step-by-step-softening-audio-routine/"><u>2024 Approved Step-by-Step Softening Audio Routine</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-restoring-functionality-to-resource-monitor-on-win11/"><u>Comprehensive Guide: Restoring Functionality to Resource Monitor on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-digital-footprints-finding-windows-11-writable-mac/"><u>Deciphering Digital Footprints: Finding Windows 11' Writable MAC</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-chronicle-of-run-command-activities/"><u>Enabling Chronicle of Run Command Activities</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-locked-honor-phone-by-drfone-android/"><u>How to Reset a Locked Honor Phone</u></a></li>
<li><a href="https://win11.techidaily.com/hypervisor-blues-heres-your-win-10-and-11-fix-guide/"><u>Hypervisor Blues? Here's Your Win 10 & 11 Fix Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-future-is-now-equip-yourself-with-these-7-devices/"><u>In 2024, The Future Is Now - Equip Yourself with These 7 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-logins-passing-or-faltering-attempts/"><u>Insight Into Windows Logins: Passing or Faltering Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/reach-windows-11-excellence-top-settings-to-personalize-and-tweak/"><u>Reach Windows 11 Excellence: Top Settings to Personalize and Tweak</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-windows-shared-folder-entry-points/"><u>Reclaim Windows Shared Folder Entry Points</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-ownership-related-settings-glitches-in-windows-11/"><u>Resolving Ownership-Related Settings Glitches in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-samsung-galaxy-f34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-process-for-purging-history-from-ms-defender/"><u>Unveiling the Process for Purging History From MS Defender</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-create-neon-effects-online-8-simple-and-free-tools-to-get-you-started-for-2024/"><u>Updated Create Neon Effects Online 8 Simple and Free Tools to Get You Started for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
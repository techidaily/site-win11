---
title: Strategies to Reactivate Non-Operational Buttons
date: 2024-11-20T22:03:07.685Z
updated: 2024-11-28T02:25:49.993Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Reactivate Non-Operational Buttons
excerpt: This Article Describes Strategies to Reactivate Non-Operational Buttons
keywords: Button Reactivation Tips,Operational Buttons Strategy,Resurrecting Inactive UI Elements,Reviving Unused Interface Controls,Non-Functional Button Fixes,UI Button Rejuvenation Steps,Reactivating Dormant Interaction Tools
thumbnail: https://thmb.techidaily.com/99ddeff4dd981a34b1bf66d98e84fae1038add51e63fa5e698f7136621990952.jpg
---

## Strategies to Reactivate Non-Operational Buttons

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.

9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-from-darkness-to-daylight-funniest-incarcerated-facebook-friends-quotes/"><u>[Updated] 2024 Approved From Darkness to Daylight Funniest Incarcerated Facebook Friends Quotes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-innovative-video-marketing-youtube-trailers-with-filmora/"><u>[Updated] 2024 Approved Innovative Video Marketing YouTube Trailers with Filmora</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-steps-to-capture-ios-audio-files/"><u>[Updated] Quick Steps to Capture iOS Audio Files</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-uncluttered-focus-affinity-photos-cleanup-technique/"><u>[Updated] Uncluttered Focus Affinity Photo's Cleanup Technique</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-ideal-tools-for-secure-vimeo-downloads/"><u>2024 Approved Ideal Tools for Secure Vimeo Downloads</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlined-accessibility-learning-iphoneipad-techniques-for-podcast-downloads/"><u>2024 Approved Streamlined Accessibility Learning iPhone/iPad Techniques for Podcast Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-11s-inability-to-open-files-for-writing/"><u>Correcting Windows 11'S Inability to Open Files for Writing</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-update-restrictions-a-guide-to-uninstalling-apps/"><u>Easing Windows Update Restrictions: A Guide to Uninstalling Apps</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-setting-auto-empty-for-windows-trash/"><u>Maximizing Efficiency: Setting Auto-Empty for Windows Trash</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-write-restrictions-in-windows-folders/"><u>Overcoming Write Restrictions in Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/quickening-startup-with-efficient-win11-configurations/"><u>Quickening Startup with Efficient Win11 Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/seven-strategies-to-start-using-windows-11-widgets/"><u>Seven Strategies to Start Using Windows 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/swift-windows-paper-handler-fix/"><u>Swift Windows Paper Handler Fix</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211310978-9781923009493-the-world-of-italian-folk-magic/"><u>The World of Italian Folk Magic | Free Book</u></a></li>
<li><a href="https://win-online.techidaily.com/transferir-informacion-entre-discos-ssd-samsung-sin-necesidad-de-cables-metodos-efectivos/"><u>Transferir Información Entre Discos SSD Samsung Sin Necesidad De Cables: Métodos Efectivos</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/your-ultimate-guide-to-accessing-fun-kids-movies-at-no-cost-online/"><u>Your Ultimate Guide to Accessing Fun Kids Movies at No Cost Online</u></a></li>
</ul></div>


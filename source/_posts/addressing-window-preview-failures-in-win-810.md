---
title: Addressing Window Preview Failures in Win 8/10
date: 2024-06-25T11:42:41.322Z
updated: 2024-06-26T11:42:41.322Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Window Preview Failures in Win 8/10
excerpt: This Article Describes Addressing Window Preview Failures in Win 8/10
keywords: Windows View Failures,Win 8/10 Screen Issues,Window Preview Crashes,OS X Window Problems,Fixing Windows 8 Display,Resolving Win 10 Glitches,Overcoming View Errors
thumbnail: https://thmb.techidaily.com/66474ad3ea796bd372c3cdc425ee2c1b3cee0dd881c03ccdd13266e6df3b21d0.jpg
---

## Addressing Window Preview Failures in Win 8/10

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

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
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
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

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/enhancing-folder-context-menus-on-windows-11/"><u>Enhancing Folder Context Menus on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-addressing-winscombsvc-errors-in-windows-os/"><u>Tips & Tricks for Addressing WinScombSvc Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-terminal-mastering-focus-mode-transitions/"><u>Navigating Windows Terminal: Mastering Focus Mode Transitions</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-power-of-task-manager-with-admin-rights-in-win11/"><u>Unleash Full Power of Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-microsoft-edges-heavy-background-tasks/"><u>Curbing Microsoft Edge's Heavy Background Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/mending-your-silent-windows-headset-mic/"><u>Mending Your Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-xpatch-fixes-for-error-0x80073712/"><u>Mastering Windows XPatch Fixes for Error 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-to-remove-restrictions-on-blocked-windows-files/"><u>Advanced Methods to Remove Restrictions on Blocked Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflicting-apps-camera-use-windows-error-0xa00f4243/"><u>Addressing Conflicting Apps' Camera Use: Windows Error 0xA00F4243</u></a></li>
<li><a href="https://extra-information.techidaily.com/basic-understanding-of-animate-graphic-content/"><u>Basic Understanding of Animate Graphic Content</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unseen-features-in-depth-look-at-instagrams-ask-emoji/"><u>[Updated] 2024 Approved  Unseen Features  In-Depth Look at Instagram’s Ask Emoji</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-culinary-cinematography-step-by-step-recipe-tutorials/"><u>In 2024, Culinary Cinematography  Step-by-Step Recipe Tutorials</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-how-to-choose-between-filmora-and-democreator/"><u>2024 Approved  How to Choose Between Filmora and Democreator</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-no-root-audio-recording-on-android-devices-tutorial/"><u>[New] No-Root Audio Recording on Android Devices [Tutorial]</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-explore-the-leading-websites-for-legal-montage-music-downloads/"><u>Updated 2024 Approved Explore the Leading Websites for Legal Montage Music Downloads</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-improve-zoo-call-quality-banish-background-noise/"><u>2024 Approved  Improve Zoo Call Quality  Banish Background Noise</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-precise-process-installing-snapchat-on-a-mac-os/"><u>In 2024, Precise Process  Installing Snapchat on a Mac OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/driving-growth-with-metaverse-marketing-excellence/"><u>Driving Growth with Metaverse Marketing Excellence</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-a-comprerans-guide-to-finding-and-joining-exclusive-discords/"><u>[New] In 2024, A Compreran's Guide to Finding and Joining Exclusive Discords</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
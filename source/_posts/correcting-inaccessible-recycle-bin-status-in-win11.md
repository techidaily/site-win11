---
title: Correcting Inaccessible Recycle Bin Status in Win11
date: 2025-01-12T16:22:15.791Z
updated: 2025-01-18T19:08:30.635Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Inaccessible Recycle Bin Status in Win11
excerpt: This Article Describes Correcting Inaccessible Recycle Bin Status in Win11
keywords: Win11 Fix Recycle Issues,Access Win11 Trash,Enhance Win11 Bin,Resolve Win11 Waste Error,Windows Bin Status Correct,Fix Win11 Bin Not Shown,Improve Win11 Garbage Icon
thumbnail: https://thmb.techidaily.com/b41dfc1747c954c2591d35270b4a20079e5707f867334ccdc51bba558ecb898b.jpg
---

## Correcting Inaccessible Recycle Bin Status in Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-the-art-of-smooth-video-transitioning/"><u>[New] In 2024, The Art of Smooth Video Transitioning</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-light-up-the-screen-techniques-for-stunning-youtube-visuals/"><u>[New] Light Up the Screen Techniques for Stunning YouTube Visuals</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-anonymous-story-consumption-navigating-through-instagram-stories-on-desktopmobile-free/"><u>[Updated] 2024 Approved Anonymous Story Consumption Navigating Through Instagram Stories on Desktop/Mobile [Free]</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-quintessential-scriptwriting-throughout-the-film-landscape/"><u>[Updated] In 2024, Quintessential Scriptwriting Throughout the Film Landscape</u></a></li>
<li><a href="https://some-techniques.techidaily.com/halls-of-fame-on-reddit-celebrating-best-rated-threads-for-2024/"><u>Halls of Fame on Reddit Celebrating Best-Rated Threads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-hardware-scheduler-for-graphics-in-winos/"><u>How to Turn Off Hardware Scheduler for Graphics in WINOS</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-simple-steps-for-android-voice-recording-no-root/"><u>In 2024, Simple Steps for Android Voice Recording (No Root)</u></a></li>
<li><a href="https://discover-blog.techidaily.com/optimized-with-advanced-analytics-cookiebots-expertise/"><u>Optimized with Advanced Analytics: Cookiebot's Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-old-windows-laptop-or-desktop-years/"><u>Pinpointing Old Windows Laptop or Desktop Years</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-xiaomi-redmi-13c-5g-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Xiaomi Redmi 13C 5G and Browser | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolve-your-gaming-experience-with-no-more-input-lag-tackling-the-issue-of-a-sluggish-second-monitor-in-win-1011/"><u>Resolve Your Gaming Experience with No More Input Lag: Tackling the Issue of a Sluggish Second Monitor in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-increasing-windows-11-pin-length/"><u>Step-by-Step Guide: Increasing Windows 11 PIN Length</u></a></li>
<li><a href="https://win11.techidaily.com/switch-onoff-tpm-support-in-virtualbox-version-70/"><u>Switch On/Off TPM Support in VirtualBox Version 7.0</u></a></li>
<li><a href="https://win11.techidaily.com/the-modernized-microsoft-app-you-cant-ignore-here-are-9-reasons/"><u>The Modernized Microsoft App You Can’t Ignore - Here Are 9 Reasons</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-of-device-serial-numbers-on-windows-platforms/"><u>Unlocking Secrets of Device Serial Numbers on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-system-recovery-options-with-windows-11s-restore-command/"><u>Unlocking System Recovery Options with Windows 11'S Restore Command</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-for-optimizing-valorant-downloads/"><u>Winning Strategies for Optimizing Valorant Downloads</u></a></li>
</ul></div>


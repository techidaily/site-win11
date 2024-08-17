---
title: Resolving Frozen Recycle Icon Status in Win11
date: 2024-08-15T23:47:02.368Z
updated: 2024-08-16T23:47:02.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Frozen Recycle Icon Status in Win11
excerpt: This Article Describes Resolving Frozen Recycle Icon Status in Win11
keywords: Fix Recycle Icons,Windows 11 Freeze Fix,Unfreeze Recycle Bin,Resolve WIN11 Errors,Clear Icon Halt,Win11 Troubleshooting,Stop Icon Stuck Status
thumbnail: https://thmb.techidaily.com/60fbcd30864e8b21a8752d2636e7944e4f6dffcb372de2311bd231d44717be72.jpg
---

## Resolving Frozen Recycle Icon Status in Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
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
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
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
<li><a href="https://extra-information.techidaily.com/new-a-detailed-study-on-workspace-optimization-and-productivity-levels/"><u>[New] A Detailed Study on Workspace Optimization and Productivity Levels</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-behind-the-scenes-insider-knowledge-for-youtube-video-production-for-2024/"><u>[New] Behind the Scenes  Insider Knowledge for YouTube Video Production for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-block-youtube-channels-on-computer-and-mobile-phones/"><u>[Updated] In 2024, How to Block YouTube Channels on Computer and Mobile Phones</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-imaginative-inspirations-for-virtual-explorers-the-best-metaverse-moments/"><u>2024 Approved  Imaginative Inspirations for Virtual Explorers  The Best Metaverse Moments</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-master-the-art-of-livestreaming-three-key-approaches-subscriber-less-style/"><u>2024 Approved  Master the Art of Livestreaming  Three Key Approaches, Subscriber-Less Style</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-a-microsoft-account-and-a-local-account-are-different-on-windows/"><u>6 Ways a Microsoft Account and a Local Account Are Different on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/behind-the-scenes-of-online-content-monetization/"><u>Behind the Scenes of Online Content Monetization</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-steps-to-engage-with-windows-covert-personality-explorer/"><u>Beneath the Surface: Steps to Engage with Windows’ Covert Personality Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-mcuicntexe-entry-point-loss-in-windows-systems/"><u>Cure for McUICnt.exe Entry Point Loss in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-use-of-windows-module-installer-worker/"><u>Decreasing Excessive Use of Windows Module Installer Worker</u></a></li>
<li><a href="https://win11.techidaily.com/disable-dim-display-feature-via-control-panel-quick-guide/"><u>Disable Dim Display Feature via Control Panel Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-mail-readability-removing-html-from-email-text/"><u>Enhancing Windows 11 Mail Readability: Removing HTML From Email Text</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/exciting-development-filmora-x-now-compatible-with-arm-devices-for-2024/"><u>Exciting Development Filmora X Now Compatible with ARM Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-blank-canvases-to-dynamic-displays-on-win-1011/"><u>From Blank Canvases to Dynamic Displays on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-11-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 11 & 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On OnePlus Nord N30 SE? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-honor-80-pro-straight-screen-edition-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Honor 80 Pro Straight Screen Edition FRP Bypass With Best Methods</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-password-cracking-tools-for-oppo-find-n3-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Oppo Find N3</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-windows-11-pin-more-secure-and-elongated/"><u>Making Your Windows 11 PIN More Secure & Elongated</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-not-recognized-fix-for-windows-users/"><u>Overcoming Device Not Recognized: Fix for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/pixelprecision-snag-9-tactics-to-reinstate-it/"><u>PixelPrecision Snag? 9 Tactics to Reinstate It</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-window-icons-on-windows/"><u>Refreshing Window Icons on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functioning-automated-rules-in-microsoft-outlook/"><u>Restoring Functioning Automated Rules in Microsoft Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-password-policy-setting-new-limit-post-failed-logins/"><u>Revamping Password Policy: Setting New Limit Post Failed Logins</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-10-shutdown-for-ongoing-processes/"><u>Strategies to Extend Windows 10 Shutdown for Ongoing Processes</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-system-top-5-tips-for-mastering-windows-folders/"><u>Supercharge Your System: Top 5 Tips for Mastering Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unknown-hardware-in-windows-1110/"><u>Troubleshooting Unknown Hardware in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-tune-up-discover-windows-best-speed-solutions/"><u>Turbo Tune-Up: Discover Windows' Best Speed Solutions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-logitech-g203-driver-setup-free-download-for-windows-users-on-latest-versions/"><u>Ultimate Logitech G203 Driver Setup - Free Download for Windows Users on Latest Versions</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-efficiency-quick-access-to-system-restore-in-windows-11/"><u>Unlocking Efficiency: Quick Access to System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-sam-errors-windows-edition/"><u>Unraveling the Mysteries of SAM Errors, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-task-management-easy-run-tool-integration-on-windows/"><u>Upgrade Your Task Management: Easy Run Tool Integration on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-the-fn-key-operations-and-tips/"><u>Utilizing the FN Key: Operations and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/windows-cab-files-explained-formatting-and-implementation/"><u>Windows CAB Files Explained: Formatting and Implementation</u></a></li>
</ul></div>

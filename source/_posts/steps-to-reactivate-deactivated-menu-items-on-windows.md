---
title: Steps to Reactivate Deactivated Menu Items on Windows
date: 2024-08-15T23:50:46.699Z
updated: 2024-08-16T23:50:46.699Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reactivate Deactivated Menu Items on Windows
excerpt: This Article Describes Steps to Reactivate Deactivated Menu Items on Windows
keywords: Reactivate Menu,Deactivated Menu,Windows Menu Revival,WinMenu Restoration,Menu Re-Enablement,UI Resurrection Wins,Menu Items React
thumbnail: https://thmb.techidaily.com/ea52c7c75e7b3032041ebf8f7a073a81be868964630fead8d644714b724c8d98.jpg
---

## Steps to Reactivate Deactivated Menu Items on Windows

 Right-clicking the Windows desktop will usually open the context menu, which many users need to access regularly. However, some users have reported that the right-click menu gets stuck loading forever with a spinning cursor or doesn’t display correctly. Users can’t access the context menu for the desktop when it’s not working right.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.

## 1\. Restart the File Explorer Process

 File Explorer handles the right-click context menu on the Windows desktop. Users confirm that refreshing File Explorer can sometimes fix the context menu when it’s not working. Our article about [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) explains how to apply this potential resolution with Task Manager.

![The Windows Explorer process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-process.jpg)

## 2\. Scan Your PC With System File Checker and Deployment Image Servicing Management

 Corrupted system files can be a cause for menus not displaying correctly in Windows. So, we recommend users run system image and file scans when the context menu isn’t working right.

 You can run SFC and DISM scans as covered for methods one and two in this guide to [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-sfc-scannow-command.jpg)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->

## 3\. Deactivate Tablet Mode (for Windows 10)

 The context menu loses functionality when Windows 10 is in Tablet Mode. So, check whether you've inadvertently set your PC to Tablet Mode. Our [turning off Windows 10’s tablet mode](https://www.makeuseof.com/turn-off-tablet-mode-windows-10/) provides details about how to disable that mode via the Action Center.

## 4\. Change the "Remove File Explorer" Context Menu Policy Setting

 The Windows Group Policy has a "Remove File Explorer" setting that disables the desktop’s right-click menu when enabled. If you’re a Windows Pro or Enterprise user, check that policy to see if it is enabled and disable it if it is.

 This is how you can disable that policy:

1. Press the **Win + R** shortcut to open Run.
2. Type **gpedit.msc** inside the **Open** text box and click **OK** to bring up the Group Policy Editor.
3. Next, double-click the **User Configuration** navigation option in Group Policy Editor’s sidebar.
4. Double-click **Administrative Templates** \> **Windows Components** to expand those navigation options.  
![Windows Components in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
5. Then click **File Explorer** to view its policy settings.
6. Double-click on the **Remove File Explorer’s default context menu** option.
7. Select the policy’s **Not Configured** radio button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/not-configured-radio-button.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
8. Click **Apply** to set the policy change.
9. Select **OK** to exit the Remove File Explorer’s default context menu window.

## 5\. Create a NoViewContextMenu Registry DWORD

 Some users confirm they’ve been able to fix their context menus by creating a new **NoViewContextMenu** DWORD in the **Explorer** registry key. Creating such a DWORD can reactivate the context menu.

 Although this sounds like a complex solution, it’s quite straightforward to apply. You can create a **NoViewContextMenu** DWORD like this:

1. Run the Registry Editor app by pressing **Win + S**, entering **regedit**, and selecting its search result.
2. Click on the address bar in the registry editor and input this key path:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer`
3. Right-click the **Explorer** key and select **New**.
4. Click **DWORD (32-bit) Value** on the submenu.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
5. Type **NoViewContextMenu** in the text box for the DWORD.
6. The **NoViewContextMenu** DWORD will probably be set to 0 by default when you create it. However, double-click the **NoViewContextMenu** just to check its value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-dword-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
7. Set the **NoViewContextMenu** value to **0** in the **data** box if it’s not already and click **OK**.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Modify the ContextMenuHandlers Key

 Modifying the ContextMenuHandlers key is another widely confirmed way to fix the context menu. However, this registry tweak involves deleting some keys. So, we recommend you [create a System Restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying this potential solution. Then modify the ContextMenuHandlers key as follows:

1. Launch Registry Editor and go to this key location:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shellex\ContextMenuHandlers`
2. Now delete all subkeys within the **ContextMenuHandlers** key except **New**, **Sharing**, **WorkFolders**, and **FileSyncEx**. To do so, right-click a subkey and select **Delete**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-delete-option.jpg)
3. Click **Yes** when prompted to provide confirmation.
4. Repeat the previous two steps to erase the other subkeys in **ContextMenuHandlers**, but do not delete **WorkFolders**, **FileSyncEx**, **New**, and **Sharing**.  
![The ContextMenuHandlers key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/contextmenuhandlers-key.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Exit Registry Editor and select to restart your Windows PC.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Update Your Mouse’s Driver

 The mouse is the peripheral with which users activate the context menu. Although not an especially likely cause, it’s possible your context menu isn’t working because your mouse’s driver is faulty or outdated. So, try updating the driver for your mouse. We have a guide about [finding and replacing old device drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) that provides details for how you can apply this potential fix.

![A mouse driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-download-option.jpg)

 Incidentally, you check if the context menu not working is a mouse issue by utilizing the hotkey for that menu. Try pressing the **Shift** \+ **F10** hotkey when on the desktop to see if that opens the context menu. Or select a desktop shortcut and press that keyboard shortcut. If the context menu works then, there could be an issue with your mouse or its right button.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## 8\. Perform a Clean Boot

 A conflicting third-party program might be crashing your context menu. For example, mouse managers or software packages with right-click shell extensions could be causing context menu issues. For example, Google Drive, WinZip, and 7-Zip are software packages that add right-click shell extensions.

 To eliminate such a possible cause, try clean booting your Windows PC. Applying this troubleshooting method disables third-party startup programs and services set to run automatically. Our guide to [performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) provides step-by-step instructions for how you can disable those startup items with Task Manager and System Configuration.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab3.jpg)

 When you’ve set the clean boot, restart Windows and right-click on the desktop to see if the context menu works ok. If it does, then it’s probably better to leave the boot configuration as set. However, you can try to identify what program or service was causing the issue by gradually re-enabling disabled startup apps and services until the context menu stops working again.

## 9\. Disable Third-Party Context Menu Shell Extensions With CCleaner

 You can also directly select to turn off third-party shell extensions included in the startup that might be causing context menu issues with CCleaner. So, try turning off superfluous context menu add-ons with that software as follows:

1. Go to the [CCleaner website](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2027967/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwtuOlBhBREiwA7agf1ofUbIfUK8X-GzUG-CBD%5F%5F1dyp8qqSnTPOOlQqX1d7ocUDK5BxqH-hoCw1oQAvD%5FBwE) and click **Free Download** there.
2. Activate File Explorer (simultaneously press **Win + E**) and navigate to the folder that includes the downloaded CCleaner setup file.
3. Double-click **ccsetup614.exe** to start the setup wizard.
4. Select **Install** to add the software with default installation settings.  
![The Install option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-install-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
5. Open CCleaner and click its **Tools** tab.
6. Click the **Startup** and **Context Menu** tabs.
7. Look at the Program column to identify third-party shell extensions listed there.  
![The Context Menu tab in CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-context-menu-tab-in-cccleaner.jpg)
8. Select third-party shell extensions and click **Disable** to turn them off.

## Get the Desktop Context Menu Fixed With These Resolutions

 The troubleshooting methods above are quite thorough and will likely resolve most Windows context menu issues. Lots of users have been able to fix the context menu not working by applying the registry tweak solutions.

 If the potential solutions here don’t work for you, you may need to try something more drastic, like resetting Windows or performing an in-place upgrade reinstallation.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-livestreaming-leaderboards-which-software-tops-the-chartvmixwirecast/"><u>[New] 2024 Approved  Livestreaming Leaderboards  Which Software Tops the Chart—VMix/Wirecast?</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-audience-accumulation-expedition-tutorials-1mplus-milestone-for-2024/"><u>[New] Audience Accumulation Expedition  Tutorial's 1M+ Milestone for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-beyond-hd-the-exceptional-experience-with-hp-envy-27/"><u>[New] In 2024, Beyond HD - The Exceptional Experience with HP Envy 27</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-exclusive-catalogue-free-to-use-stock-media-sites/"><u>[Updated] In 2024, Exclusive Catalogue  Free-to-Use Stock Media Sites</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-scaling-up-your-income-with-instagram-mastery/"><u>[Updated] Scaling Up Your Income with Instagram Mastery</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-textual-transformations-discovering-the-best-video-effects/"><u>[Updated] Textual Transformations - Discovering the Best Video Effects</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-top-5-solutions-to-obs-studio-video-editing/"><u>[Updated] Top 5 Solutions to OBS Studio Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-from-vpn-client-errors/"><u>Addressing Disconnected From VPN Client Errors</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-vms-with-virtualbox-70-now-for-windows-11-users/"><u>Boosting Your VMs with VirtualBox 7.0, Now for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-backup-error-in-windows-file-history-configuration/"><u>Correcting “Backup Error” In Windows File History Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-time-on-mass-file-naming-with-powertools/"><u>Cut Down Time on Mass File Naming with PowerTools</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-how-choosing-a-pc-over-a-mac-can-benefit-you-more-9/"><u>Decoding How Choosing a PC Over A Mac Can Benefit You More (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/eliciting-hidden-taskbar-recon-in-windows-11/"><u>Eliciting Hidden Taskbar Recon in Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elite-performers-top-picks-from-skate-highlights/"><u>Elite Performers  Top Picks From Skate Highlights</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-methods-for-tcpip-port-audits-on-windows/"><u>Exploring Methods for TCP/IP Port Audits on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-browsers-to-desktops-website-conversion-guide/"><u>From Browsers to Desktops: Website Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/growth-plans-for-windows-hard-drive-without-data-loss/"><u>Growth Plans for Windows Hard Drive without Data Loss</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy A25 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-11-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-10-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-everything-to-know-about-apple-id-password-requirements-for-apple-iphone-12-pro-by-drfone-ios/"><u>In 2024, Everything To Know About Apple ID Password Requirements For Apple iPhone 12 Pro</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-sites-bridging-you-with-googles-advertising-on-youtube/"><u>In 2024, Sites Bridging You with Google's Advertising on Youtube</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-your-disabled-iphone-6s-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>In 2024, Unlock Your Disabled iPhone 6s Without iTunes in 5 Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-elevated-commands-always-access-terminal-as-admin/"><u>Mastering Elevated Commands: Always Access Terminal as Admin</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-microsoft-store-eradicating-code-0x80072f30/"><u>Mastering the Microsoft Store: Eradicating Code 0X80072F30</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-browser-blues-overcome-site-blockades-with-these-tips/"><u>Microsoft Browser Blues? Overcome Site Blockades with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-deletion-warning-settings-on-pcs/"><u>Navigating Deletion Warning Settings on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-pcs-idle-state-with-scheduled-shutdowns/"><u>Optimize Your PC's Idle State with Scheduled Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nonexistent-hardware-warning-in-windows/"><u>Overcoming Nonexistent Hardware Warning in WIndows</u></a></li>
<li><a href="https://win11.techidaily.com/proven-windows-11-ways-to-boost-workflow-and-productivity-45/"><u>Proven Windows 11 Ways to Boost Workflow and Productivity (45)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-resolve-error-a00f425d-on-windows-device/"><u>Quick Guide to Resolve Error A00F425D on Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/reinvent-the-way-you-handle-aging-pcs-less-windows/"><u>Reinvent the Way You Handle Aging PCs: Less Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-a00f425d-on-windows-11-camera-app/"><u>Resolving Error Code A00F425D on Windows 11 Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/saving-yourself-from-install-error-in-discord-set-up/"><u>Saving Yourself From Install Error in Discord Set-Up</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-mastery-in-artificially-inspired-visuals-using-paint-cocreator-on-win11/"><u>Step-by-Step Mastery in Artificially Inspired Visuals Using Paint Cocreator on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-administration-in-windows-11/"><u>Streamlining User Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-broken-usb-connections-on-windows-systems/"><u>Tackling Broken USB Connections on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/the-unopened-notepad-predicament-solutions-to-make-it-open-once-more/"><u>The Unopened Notepad Predicament: Solutions to Make It Open Once More</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ultimate-guide-choosing-a-high-performance-compact-gaming-pc/"><u>Ultimate Guide: Choosing a High-Performance Compact Gaming PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-explorers-gallery-view-capability/"><u>Unlocking File Explorer's Gallery View Capability</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-why-steam-cant-synch-files-in-pc-settings/"><u>Unraveling Why Steam Can't Synch Files in PC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-redirecting-onedrive-storage-location/"><u>Win 11 - Redirecting OneDrive Storage Location</u></a></li>
</ul></div>

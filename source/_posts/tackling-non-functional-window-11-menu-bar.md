---
title: Tackling Non-Functional Window 11 Menu Bar
date: 2024-08-16T00:00:09.353Z
updated: 2024-08-17T00:00:09.353Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Non-Functional Window 11 Menu Bar
excerpt: This Article Describes Tackling Non-Functional Window 11 Menu Bar
keywords: Win11 Menu Troubleshoot,MenuBar Fix Guide,MenuLayout Optimization,UI Navigation Enhance,NFU (Non-Functional User Interface),Accessibility Menu Improvement,Window Bar Functionality
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

## Tackling Non-Functional Window 11 Menu Bar

 Right-clicking the Windows desktop will usually open the context menu, which many users need to access regularly. However, some users have reported that the right-click menu gets stuck loading forever with a spinning cursor or doesn’t display correctly. Users can’t access the context menu for the desktop when it’s not working right.

 Although desktop context menu access is seldom essential, it offers handy shortcuts, especially when you've customized it. So, it’s important to fix the desktop context menu when it’s not working. If your Windows desktop context menu isn’t functioning right, try applying the troubleshooting methods below.

## 1\. Restart the File Explorer Process

 File Explorer handles the right-click context menu on the Windows desktop. Users confirm that refreshing File Explorer can sometimes fix the context menu when it’s not working. Our article about [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) explains how to apply this potential resolution with Task Manager.

![The Windows Explorer process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-process.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Scan Your PC With System File Checker and Deployment Image Servicing Management

 Corrupted system files can be a cause for menus not displaying correctly in Windows. So, we recommend users run system image and file scans when the context menu isn’t working right.

 You can run SFC and DISM scans as covered for methods one and two in this guide to [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
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
5. Then click **File Explorer** to view its policy settings.
6. Double-click on the **Remove File Explorer’s default context menu** option.
7. Select the policy’s **Not Configured** radio button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/not-configured-radio-button.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click **Apply** to set the policy change.
9. Select **OK** to exit the Remove File Explorer’s default context menu window.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Type **NoViewContextMenu** in the text box for the DWORD.
6. The **NoViewContextMenu** DWORD will probably be set to 0 by default when you create it. However, double-click the **NoViewContextMenu** just to check its value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-dword-window.jpg)
7. Set the **NoViewContextMenu** value to **0** in the **data** box if it’s not already and click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
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
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
5. Exit Registry Editor and select to restart your Windows PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 7\. Update Your Mouse’s Driver

 The mouse is the peripheral with which users activate the context menu. Although not an especially likely cause, it’s possible your context menu isn’t working because your mouse’s driver is faulty or outdated. So, try updating the driver for your mouse. We have a guide about [finding and replacing old device drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) that provides details for how you can apply this potential fix.

![A mouse driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-download-option.jpg)

 Incidentally, you check if the context menu not working is a mouse issue by utilizing the hotkey for that menu. Try pressing the **Shift** \+ **F10** hotkey when on the desktop to see if that opens the context menu. Or select a desktop shortcut and press that keyboard shortcut. If the context menu works then, there could be an issue with your mouse or its right button.

## 8\. Perform a Clean Boot

 A conflicting third-party program might be crashing your context menu. For example, mouse managers or software packages with right-click shell extensions could be causing context menu issues. For example, Google Drive, WinZip, and 7-Zip are software packages that add right-click shell extensions.

 To eliminate such a possible cause, try clean booting your Windows PC. Applying this troubleshooting method disables third-party startup programs and services set to run automatically. Our guide to [performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) provides step-by-step instructions for how you can disable those startup items with Task Manager and System Configuration.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab3.jpg)

 When you’ve set the clean boot, restart Windows and right-click on the desktop to see if the context menu works ok. If it does, then it’s probably better to leave the boot configuration as set. However, you can try to identify what program or service was causing the issue by gradually re-enabling disabled startup apps and services until the context menu stops working again.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Disable Third-Party Context Menu Shell Extensions With CCleaner

 You can also directly select to turn off third-party shell extensions included in the startup that might be causing context menu issues with CCleaner. So, try turning off superfluous context menu add-ons with that software as follows:

1. Go to the [CCleaner website](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2027967/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwtuOlBhBREiwA7agf1ofUbIfUK8X-GzUG-CBD%5F%5F1dyp8qqSnTPOOlQqX1d7ocUDK5BxqH-hoCw1oQAvD%5FBwE) and click **Free Download** there.
2. Activate File Explorer (simultaneously press **Win + E**) and navigate to the folder that includes the downloaded CCleaner setup file.
3. Double-click **ccsetup614.exe** to start the setup wizard.
4. Select **Install** to add the software with default installation settings.  
![The Install option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-install-button.jpg)
5. Open CCleaner and click its **Tools** tab.
6. Click the **Startup** and **Context Menu** tabs.
7. Look at the Program column to identify third-party shell extensions listed there.  
![The Context Menu tab in CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-context-menu-tab-in-cccleaner.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
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
<li><a href="https://win11.techidaily.com/12-unwanted-programs-in-your-windows-environment/"><u>12 Unwanted Programs in Your Windows Environment</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-highest-qp-for-gradual-video-playback/"><u>2024 Approved  Highest QP for Gradual Video Playback</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-enable-or-disable-ntfs-file-compression-in-windows-11/"><u>4 Ways to Enable or Disable NTFS File Compression in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-apps-for-changing-the-createdmodified-date-on-a-file-on-windows/"><u>8 Apps for Changing the Created/Modified Date on a File on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-changing-esd-into-an-iso-for-windows-pcs/"><u>A Beginner's Guide to Changing ESD Into an ISO for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-managing-windows-11-default-applications/"><u>A Comprehensible Guide to Managing Windows 11 Default Applications</u></a></li>
<li><a href="https://win11.techidaily.com/a-concierge-guide-to-entering-your-windows-11-appshabitat/"><u>A Concierge Guide to Entering Your Windows 11 AppsHabitat</u></a></li>
<li><a href="https://win11.techidaily.com/a-concise-guide-to-windows-11-user-grievances-and-gripes/"><u>A Concise Guide to Windows 11 User Grievances and Gripes</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-in-the-ms-store-a-step-by-step-guide/"><u>Accelerating Downloads in the MS Store - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://win11.techidaily.com/address-vanishing-cameras-from-device-manager-list/"><u>Address Vanishing Cameras From Device Manager List</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-token-usage-in-modern-windows-systems/"><u>Addressing Invalid Token Usage in Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-mouse-dynamics-for-a-more-natural-response-in-win-1011/"><u>Adjusting Mouse Dynamics for a More Natural Response in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/administrative-task-mastery-initiating-task-manager-in-win11/"><u>Administrative Task Mastery: Initiating Task Manager in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-concealment-for-windows-11-task-view-icon/"><u>Advanced Concealment for Windows 11 Task View Icon</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-standard-pdf-display/"><u>Altering Window's Standard PDF Display</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-installation-process-via-registry/"><u>Altering Windows Installation Process via Registry</u></a></li>
<li><a href="https://win11.techidaily.com/automate-your-keyboard-setup-with-windows-11/"><u>Automate Your Keyboard Setup with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-device-naming-disputes-on-your-computer-network/"><u>Avoiding Device Naming Disputes on Your Computer Network</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-hiccup-error-0x00000000-solution/"><u>Avoiding Microsoft Store Hiccup: Error 0X00000000 Solution</u></a></li>
<li><a href="https://article-helps.techidaily.com/battle-of-the-titans-gopro-hero5-black-vs-session-for-2024/"><u>Battle of the Titans  GoPro Hero5 Black VS Session for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-overcome-steam-sync-error-on-windows/"><u>Best Practices to Overcome Steam Sync Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/beware-ais-role-in-win-11-key-generation-missteps/"><u>Beware: AI's Role in Win 11 Key Generation Missteps</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-human-interface-ai-in-windows-tomorrow/"><u>Beyond Human Interface: AI in Windows Tomorrow</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-customizing-hotkey-behavior/"><u>Boost Productivity: Customizing Hotkey Behavior</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-display-with-w11s-auto-hdr-feature/"><u>Boost Your Display with W11's Auto HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-disk-capacity-7-affordable-tricks-for-windows-enthusiasts/"><u>Boosting Disk Capacity: 7 Affordable Tricks for Windows Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ease-of-use-with-mouse-settings-in-win11/"><u>Boosting Ease of Use with Mouse Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-customized-windows-cmd/"><u>Boosting Productivity with Customized Windows Cmd</u></a></li>
<li><a href="https://win11.techidaily.com/1719336940768-cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now.</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-budget-asmr-mic-stellar-sound-value/"><u>In 2024, Best Budget ASMR Mic  Stellar Sound Value</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/innovative-editing-at-your-fingertips-complete-guide-to-vivacut-24/"><u>Innovative Editing at Your Fingertips  Complete Guide to VivaCut '24</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/navigating-through-ntfssys-blue-screen-issues-fixes-for-windows-1ve-users/"><u>Navigating Through ntfs.sys Blue Screen Issues: Fixes for Windows 1Ve Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/optimizing-corporate-correspondence-via-ai-practical-tips-and-tricks/"><u>Optimizing Corporate Correspondence via AI: Practical Tips & Tricks</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-complete-guide-to-transforming-your-footages-hue-for-2024/"><u>The Complete Guide to Transforming Your Footage's Hue for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-dji-fpv-revolution-a-review-of-eyewear-innovation/"><u>The DJI FPV Revolution  A Review of Eyewear Innovation</u></a></li>
<li><a href="https://sound-issues.techidaily.com/trouble-with-your-logitech-g933-mic-follow-these-steps-to-fix-it/"><u>Trouble with Your Logitech G933 Mic? Follow These Steps to Fix It!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleash-your-potential-with-filmoras-loved-9-traits-for-2024/"><u>Unleash Your Potential with Filmora's Loved 9 Traits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719264863745-unwanted-file-explorer-activation-stopped/"><u>Unwanted File Explorer Activation Stopped!</u></a></li>
<li><a href="https://win11.techidaily.com/1719275577489-winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them</u></a></li>
</ul></div>

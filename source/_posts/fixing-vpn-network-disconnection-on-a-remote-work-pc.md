---
title: Fixing VPN Network Disconnection on a Remote Work PC
date: 2024-08-16T00:01:41.986Z
updated: 2024-08-17T00:01:41.986Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing VPN Network Disconnection on a Remote Work PC
excerpt: This Article Describes Fixing VPN Network Disconnection on a Remote Work PC
keywords: Fix VPN Dropout,Secure VPN Connections,Remote Work VPN Issues,Prevent VPN Loss,Stable VPN Remote PC,Solve VPN Disconnects,Uninterrupted VPN Access
thumbnail: https://thmb.techidaily.com/f7eb32e30dabd1ecde240ae4f390a8ba724185aa17a13d5ef1b9d86c145dc8b7.jpg
---

## Fixing VPN Network Disconnection on a Remote Work PC

 People utilize VPNs (Virtual Private Networks) for more secure and anonymous web browsing. However, some users can’t utilize VPN connections on their Windows PCs because of an error message that says, “connection to the remote computer could not be established.” Some users see that error message within Settings when they try to connect to VPNs.

 This error will prevent you from connecting to a VPN on your Windows 11/10 PCs. Is that same error affecting your PC’s VPN connectivity? If so, this is how you can probably fix that VPN connection issue on a Windows PC.

## 1\. Run the Network Adapter Troubleshooting Tool

 Windows troubleshooters can often be useful for fixing network-related issues. The Network Adapter troubleshooter will likely be the most useful troubleshooting tool for resolving this VPN error. However, the Internet Connection troubleshooter could also address issues causing the VPN connection error.

 You can access both troubleshooters within Settings. This [how to run any Windows troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/#:~:text=Press%20Win%20%2B%20I%20to%20open,Click%20on%20Other%20troubleshooters.) article provides step-by-step instructions for opening troubleshooters in the Windows 10 or 11 Settings app. Then go through the Network Adapter or Internet Connection troubleshooter to apply any manual resolutions they recommend.

![The Network Adapter troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/network-adapter-troubleshooter.jpg)

## 2\. Turn Off the Proxy Server Setting

 An intermediary proxy server can act as a firewall for enhanced network security. However, having proxy servers enabled can cause issues for VPN connections. So, it’s recommended to [disable the "use a proxy server" setting](https://www.makeuseof.com/windows-11-disable-proxy/) to eliminate that potential cause for this VPN error.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-defender-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Reconfigure Your VPN Connection’s Security Settings

 This VPN error message suggests that you try reconfiguring some network settings to resolve the issue. Changing VPN connection security settings could feasibly resolve this issue for some users. Try changing your VPN’s connection’s security settings like this:

1. Launch Run (simultaneously press the **Win + R** keys) and input "ncpa.cpl" in that accessory’s **Open** box.
2. Click **OK** in Run to bring up a Network Connections window.
3. Then right-click on your VPN connection and select **Properties**.
4. Click **Security** in the VPN properties window.
5. Select the **Point to Point Tunnelling Protocol** option on the **Type of VPN** drop-down menu.  
![The Type of VPN drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/vpn-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click the **Allow these protocols** radio button.
7. Select the **Challenge Handbrake Authentication Protocol (CHAP)** checkbox.
8. Next, click the **Microsoft CHAP Version 2** checkbox to select that option.
9. Click **OK** to set the new VPN security settings.

 Misconfigured settings in your VPN client software can also feasibly cause connection issues. To remedy that, try resetting your VPN client software settings to default. Look for and select an option within your VPN software that generally restores default settings.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 4\. Disable the Windows Firewall

 Windows Defender Firewall might be causing this error by blocking the VPN connection. To ensure WDF isn’t blocking your VPN connection, try temporarily [disabling Windows Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Then return to Settings to see if the “Connection to the remote computer could not be established” error persists.

 If this works, don’t leave the firewall off. Instead, add your VPN connection to Windows Defender Firewall’s allowed list. To do that, you’ll need to select the **Private** and **Public** checkboxes for your VPN connection, as covered within this guide to [allowing apps through Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/).

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-defender-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 5\. Disable Third-Party Security Software Packages

 Many third-party security (antivirus) software packages also have integrated firewalls that can block VPN connections. If there’s third-party security software installed on your PC, turn off its firewall component to see if that makes any difference to your VPN connection. Then set up a firewall exception for your VPN connection within your security software if that does resolve the issue.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 6\. Reinstall the WAN Miniport Devices

 Reinstalling WAN Miniport devices is a potential resolution many users confirm fixes the “Connection to the remote computer could not be established.” Applying this potential solution will reinstall the drivers for virtual network adapters that have variable protocols, which often resolves this VPN error. You can reinstall WAN Miniport devices like this:

1. First, right-click on the Windows taskbar icon (**Start** button) and select **Device Manager**.
2. Click the little arrow beside **Network adapters** to view all devices for that category.
3. Right-click on the WAN Miniport (IKEv2) adapter and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/uninstall-device-option.jpg)
4. Press **Uninstall** within the confirmation dialog box.  
![The Uninstall button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/uninstall-button.jpg)
5. Repeat the previous two steps for all WAN Miniport adapters shown within Device Manager.
6. When you’ve uninstalled all the WAN Miniport devices, click the **Action** menu.  
![The Scan for hardware changes option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/scan-for-hardware-changes-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
7. Select the **Scan for hardware changes** option to reinstall the WAN Miniport devices.

 Then return to Settings and try connecting with your VPN again.

## 7\. Reset Your PC’s Network Settings

 A network reset will reinstall all your PC’s network adapters. So, this potential resolution could have a similar effect to the preceding one, and some users have confirmed it to work. However, a network reset also restores network components to default settings.

 You can reset network adapter settings by inputting and executing a series of netsh and ipconfig commands. However, it’s more straightforward to apply this fix by clicking the **Reset now** button in Settings. Check out our [how to reset your network settings](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for further details about how you can access that option.

![The Reset now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/reset-now-button.jpg)

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## 8\. Reinstall Your VPN Software

 Reinstallation of your VPN software might be necessary if none of the other potential solutions here work for you. Applying such a solution will likely address software issues causing this VPN connection error. You’ll also update your VPN software by installing its latest version.

 You can remove your VPN client software within Programs or Features or Settings as outlined in this guide to [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Make sure you also remove any additional extras installed with your VPN client, such as network TAP adapters. Resetting your PC’s network settings will also probably uninstall VPN software.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/programs-and-features2.jpg)
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then open the official publisher download page for your VPN software. Select to download the latest VPN client software version for Windows 11/10 from there. Run the downloaded VPN software installer to reinstall.

## Re-establish Your VPN Connection on Windows

 Those potential fixes for the “Connection to the remote computer could not be established” error will probably re-establish your VPN connection. In many cases, reinstalling WAN Miniport adapters or disabling proxy servers will often do the trick. However, you might need to try alternative resolutions here to get this VPN connection issue resolved.

 This error will prevent you from connecting to a VPN on your Windows 11/10 PCs. Is that same error affecting your PC’s VPN connectivity? If so, this is how you can probably fix that VPN connection issue on a Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-navigate-to-the-5-preferred-android-ps2-emulator-apps-for-2024/"><u>[New] Navigate to the 5 Preferred Android PS2 Emulator Apps for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-personalize-phone-chimes-a-whatsapp-tone-builders-manual/"><u>[New] Personalize Phone Chimes  A WhatsApp Tone Builder's Manual</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-crafting-the-perfect-youtube-channel-url-a-quick-guide/"><u>[Updated] 2024 Approved  Crafting the Perfect YouTube Channel Url  A Quick Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-maximizing-your-impact-with-periscope-live/"><u>[Updated] Maximizing Your Impact with Periscope Live</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-tailoring-your-obs-feeds-for-best-social-media-impact/"><u>[Updated] Tailoring Your OBS Feeds for Best Social Media Impact</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win11s-notepad-with-virtuoso-helper/"><u>Accelerate Win11's Notepad with Virtuoso Helper</u></a></li>
<li><a href="https://fox-http.techidaily.com/achieving-vibrant-colors-srgb-techniques/"><u>Achieving Vibrant Colors  Srgb Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-usage-of-computational-resources-by-unrealcefsubprocess/"><u>Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ais-talent-at-mixing-the-chatgpt-challenge/"><u>AI’s Talent at Mixing: The ChatGPT Challenge</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-fatal-windows-errors-the-0xf0831-guide/"><u>Avoiding Fatal Windows Errors: The 0xF0831 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-with-d3d11-compatible-gpus-in-win11win10/"><u>Avoiding Pitfalls with D3D11-Compatible GPUs in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-dxgierror-windows-devices-reattached/"><u>Combat the DXGI_ERROR: Windows Devices Reattached</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-classics-windows-11s-pathway-to-photos-folder/"><u>Connecting Classics: Windows 11'S Pathway to Photos Folder</u></a></li>
<li><a href="https://fox-helps.techidaily.com/diving-deep-into-gopro-variants-comprehensive-guide-for-2024/"><u>Diving Deep Into Gopro Variants  Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-cannot-locate-gpeditmsc-windows-problems/"><u>Essential Fixes for Cannot Locate Gpedit.msc Windows Problems</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-unveils-enhanced-user-experience-layouts/"><u>Facebook Unveils Enhanced User Experience Layouts</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-frozen-windows-volume-backup-service/"><u>Fixes for Frozen Windows Volume Backup Service</u></a></li>
<li><a href="https://win11.techidaily.com/free-notetaking-on-windows-easy-and-effective/"><u>Free Notetaking on Windows: Easy and Effective</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-best-graphics-experience-amd-rx-6800-xt-drivers-download-guide-for-all-windows-users/"><u>Get the Best Graphics Experience: AMD RX 6800 XT Drivers Download Guide for All Windows Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-infinix-note-30-vip-racing-edition-screen-sharing-drfone-by-drfone-android/"><u>How To Do Infinix Note 30 VIP Racing Edition Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-fatal-glitches-fixing-xbox-game-pass-error-0x00000001-in-windows-11/"><u>How to Eliminate Fatal Glitches: Fixing Xbox Game Pass Error 0X00000001 in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-nokia-150-2023-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Nokia 150 (2023)</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-or-malfunctioning-hardware-drivers-with-windows-device-manager-in-windows-7-by-drivereasy-guide/"><u>Identify missing or malfunctioning hardware drivers with Windows Device Manager in Windows 7</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-of-the-best-6-superior-signature-background-removers/"><u>In 2024, Best of the Best  6 Superior Signature Background Removers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fall-guys-network-woes-on-windows-systems/"><u>Mastering Fall Guys Network Woes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-calendar-a-step-by-step-guide/"><u>Mastering Windows 11 Calendar: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-schedule-with-winning-windows-to-dos/"><u>Mastering Your Schedule with Winning Windows To-Dos</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-nuances-of-winstall-for-grouped-windows-11-installs/"><u>Navigate the Nuances of Winstall for Grouped Windows 11 Installs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-access-to-system-fixes-windows-10-and-11-key-setups/"><u>Strategic Access to System Fixes: Windows 10 & 11 Key Setups</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-checks-a-guide-for-updating-context-menus/"><u>Streamlining System Checks: A Guide for Updating Context Menus</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-advantages-of-using-claude-3-why-its-time-to-move-on-from-chatgpt/"><u>The Advantages of Using Claude 3 - Why It's Time to Move On From ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-full-potential-of-windows-customizations-via-winbubble/"><u>Unleash the Full Potential of Windows Customizations via WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-rdp-access-quickly-in-the-latest-windows/"><u>Unlock RDP Access Quickly in the Latest Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-capabilities-with-easy-installation-of-msixbundle-packages/"><u>Unlock Windows Capabilities with Easy Installation of MSixBundle Packages</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-requires-elevation-puzzle-win-11s-error-740-solution/"><u>Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/why-are-other-processes-aligned-with-edge/"><u>Why Are Other Processes Aligned with Edge?</u></a></li>
</ul></div>

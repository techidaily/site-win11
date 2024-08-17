---
title: 3 Essential Methods to Enable Telnet in Win11
date: 2024-08-15T23:20:58.211Z
updated: 2024-08-16T23:20:58.211Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Essential Methods to Enable Telnet in Win11
excerpt: This Article Describes 3 Essential Methods to Enable Telnet in Win11
keywords: Win11 Telnet Setup,Enabling Windows 11 Telnet,Telnet Access in Win11,Win11 Connect via Telnet,Methods for Win11 Telnet,Activating Telnet on Win11,Secure Telnet Win11
thumbnail: https://thmb.techidaily.com/dd4233ccec15666d6d616a1b1df2dfb0cda2d2ae21f58fe6b6f759379250d50d.jpg
---

## 3 Essential Methods to Enable Telnet in Win11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://extra-information.techidaily.com/new-10-must-know-tips-for-nba-stream-quality/"><u>[New] 10 Must-Know Tips for NBA Stream Quality</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-premiere-music-collections-for-visual-media-for-2024/"><u>[New] Premiere Music Collections for Visual Media for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-analyzing-per-view-gain-for-content-making-on-video-platforms/"><u>[Updated] In 2024, Analyzing Per-View Gain for Content Making on Video Platforms</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-shooting-in-the-dark-elevating-iphone-photos-with-shadows/"><u>2024 Approved  Shooting in the Dark  Elevating iPhone Photos with Shadows</u></a></li>
<li><a href="https://win11.techidaily.com/5-hacks-for-accessing-windows-repair-options/"><u>5 Hacks for Accessing Windows Repair Options</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-video-driver-crash-on-win1110/"><u>Addressing Video Driver Crash on Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://fox-http.techidaily.com/chuckle-chest-premium-selection-of-gratuitous-gags-for-2024/"><u>Chuckle Chest  Premium Selection of Gratuitous Gags for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-windows-users-generative-erase-wonders/"><u>Clean Slate for Windows Users: Generative Erase Wonders</u></a></li>
<li><a href="https://printer-issues.techidaily.com/code-b200-resolution-achieved/"><u>Code B200 Resolution Achieved</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-ai-tools-in-windows/"><u>Efficient Installation of AI Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-clear-iphones-network-configuration-a-step-by-step-guide/"><u>How to Clear iPhone's Network Configuration: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-correct-problems-with-your-itunes-audio-configuration/"><u>How To Correct Problems With Your iTunes Audio Configuration</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-13-mini-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone 13 mini Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-from-console-to-screen-efficient-recording-strategies/"><u>In 2024, From Console to Screen  Efficient Recording Strategies</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimal-zoom-for-your-videos-top-10-editor-guide/"><u>In 2024, Optimal Zoom for Your Videos - Top 10 Editor Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-windows-11s-error-codes/"><u>Navigating Through the Maze of Windows 11'S Error Codes</u></a></li>
<li><a href="https://extra-support.techidaily.com/perfect-your-audio-journey-iphoneipad-podcasting-secrets-unveiled-for-2024/"><u>Perfect Your Audio Journey  IPhone/iPad Podcasting Secrets Unveiled for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/powerpoint-tips-adding-and-capturing-speech-sounds/"><u>PowerPoint Tips  Adding and Capturing Speech Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-predominant-rainmeter-malfunctions-in-windows/"><u>Remedying Predominant Rainmeter Malfunctions in Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-issues-with-the-witcher-3-computer-version-freezingcrashing/"><u>Resolving Issues with the Witcher 3 Computer Version Freezing/Crashing</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-graphics-restoration-on-latest-windows-oses/"><u>Simplifying Graphics Restoration on Latest Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-mkv-conversion-to-mp4-in-windows-systems/"><u>Simplifying MKV Conversion to MP4 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11-sign-in-complexity/"><u>Simplifying Windows 11 Sign-In Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/solving-issues-with-ccleaner-not-working-on-windows-1011/"><u>Solving Issues with CCleaner Not Working on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-prepare-win11-in-vmware-17-player/"><u>Step-by-Step Guide to Prepare Win11 in VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-secure-entry-into-windows-admin-console/"><u>Steps for Secure Entry Into Windows' Admin Console</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-blank-screen-issues-after-attempting-to-connect/"><u>Tackling Blank Screen Issues After Attempting to Connect</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-to-iphone-composition-choosing-right-angles-for-2024/"><u>The Ultimate Guide to iPhone Composition  Choosing Right Angles for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-on-apple-iphone-11-pro-by-drfone-ios/"><u>Unlock Apple ID without Phone Number On Apple iPhone 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/unveiling-mystery-behind-invisible-facebook-vids-with-12-steps-for-2024/"><u>Unveiling Mystery Behind Invisible Facebook Vids with 12 Steps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
</ul></div>

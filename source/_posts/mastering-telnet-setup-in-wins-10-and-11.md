---
title: Mastering Telnet Setup in Wins 10 & 11
date: 2025-02-11T21:28:34.128Z
updated: 2025-02-16T04:38:26.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Telnet Setup in Wins 10 & 11
excerpt: This Article Describes Mastering Telnet Setup in Wins 10 & 11
keywords: WinTelSetup10,WinTelSetup11,SecureWinTel,Win10TelConnection,Win11SecureTelNet,Win10TelExpertise,TelnetProWins10
thumbnail: https://thmb.techidaily.com/33bb4081d4eeefa2b002761f140e6d8a1ab23c4b8fc2690daa04e9c88bdd81bd.jpg
---

## Mastering Telnet Setup in Wins 10 & 11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  

![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

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

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-unrivaled-recording-experience-from-leading-apps/"><u>[New] 2024 Approved Unrivaled Recording Experience From Leading Apps</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ultitask-mastery-in-media-co-watching-channels-with-ease-for-2024/"><u>[New] Multitask Mastery in Media Co-Watching Channels with Ease for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-enhancing-video-aesthetics-with-bb-and-lc-overlays-on-facebook/"><u>[Updated] In 2024, Enhancing Video Aesthetics with BB and LC Overlays on Facebook</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-seamless-transition-of-video-files-to-facebook-for-pcandroid/"><u>[Updated] In 2024, Seamless Transition of Video Files to Facebook for PC/Android</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-transform-your-videos-first-impression-with-these-fonts/"><u>[Updated] In 2024, Transform Your Video's First Impression with These Fonts</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/como-convertir-archivos-wmv-en-formatos-asf-gratis-online-usando-el-servicio-de-movavi-video-editor/"><u>Cómo Convertir Archivos WMV en Formatos ASF Gratis Online Usando El Servicio De Movavi Video Editor</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-file-explorers-default-tabs/"><u>How to Silence File Explorer's Default Tabs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-13-ultra-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi 13 Ultra to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlocking-youtube-simplified-methods-for-cc-and-subtitle-integration/"><u>In 2024, Unlocking YouTube Simplified Methods for CC and Subtitle Integration</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-a-novel-framework-redefining-admin-access-control/"><u>Introducing a Novel Framework: Redefining Admin Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-your-way-through-files-in-win-os-max-156/"><u>Navigate Your Way Through Files in Win OS (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-data-integrity-in-windows-systems-weekly/"><u>Preserving Data Integrity in Windows Systems, Weekly</u></a></li>
<li><a href="https://win11.techidaily.com/ready-set-go-virtualbox-on-win-starts-with-deps-checks/"><u>Ready, Set, Go! VirtualBox on Win Starts With Deps Checks</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-gpo-management-windows-11-guide/"><u>Simplify GPO Management: Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-reading-enabling-text-interaction-on-pdfs-windows-style/"><u>Simplify Reading: Enabling Text Interaction on PDFs, Windows Style</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unlocking-speed-a-review-of-extollos-lansocket-1500-with-fast-network-and-power-transmission-features/"><u>Unlocking Speed: A Review of Extollo's LANSocket #1500 with Fast Network and Power Transmission Features</u></a></li>
</ul></div>


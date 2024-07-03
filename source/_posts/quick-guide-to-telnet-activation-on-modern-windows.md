---
title: Quick Guide to Telnet Activation on Modern Windows
date: 2024-06-25T11:33:40.584Z
updated: 2024-06-26T11:33:40.584Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Telnet Activation on Modern Windows
excerpt: This Article Describes Quick Guide to Telnet Activation on Modern Windows
keywords: Quick Telnet Windows,Activate Telnet Prog,Telnet Windows Guide,Enable Windows Telnet,Windows Telnet Setup,Fast Telnet Methods,Modern Win Telnet On
thumbnail: https://thmb.techidaily.com/ef64597bda93820e24d8ab2d0a8cbf446e80301b9ceb1303c686c48229c6eca3.jpg
---

## Quick Guide to Telnet Activation on Modern Windows

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

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
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

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
<li><a href="https://win11.techidaily.com/addressing-d3d11-compatible-gpu-faults-in-w11-and-w10/"><u>Addressing D3D11-Compatible GPU Faults in W11 & W10</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-down-your-laptop-keyboard-with-simple-steps-in-win10win11/"><u>Quiet Down Your Laptop Keyboard with Simple Steps in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-the-context-menu-with-divine-commands/"><u>Infuse the Context Menu with Divine Commands</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-code-a-secure-window-for-hardware-unhook-in-win11/"><u>How to Code a Secure Window for Hardware Unhook in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-mouse-lagging-in-star-wars-battlefront-2-on-windows-try-these-8-fixes/"><u>Is Your Mouse Lagging in Star Wars Battlefront 2 on Windows? Try These 8 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/curing-frozen-windows-desktop-context-options/"><u>Curing Frozen Windows Desktop Context Options</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-windows-activation-error-0x8007251d-and-how-do-you-fix-it/"><u>What Is the Windows Activation Error 0X8007251D and How Do You Fix It?</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pc-revival-unearthing-windows-best-eight-methods/"><u>Quick PC Revival: Unearthing Windows' Best Eight Methods</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-htc-u23-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your HTC U23 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-split-videos-like-a-pro-the-best-free-tools-for-2024/"><u>New Split Videos Like a Pro The Best Free Tools for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-the-top-rated-free-video-stabilization-software-a-comprehensive-guide/"><u>2024 Approved The Top-Rated Free Video Stabilization Software A Comprehensive Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-realme-c55-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Realme C55 | Dr.fone</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-top-7-video-language-converter-online-free-for-2024/"><u>Updated Top 7 Video Language Converter Online Free for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-top-7-imovie-alternatives-for-android-you-can-pick/"><u>In 2024, Top 7 iMovie Alternatives for Android You Can Pick</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-art-of-matchmaking-in-the-youtube-collaboration-arena/"><u>In 2024, The Art of Matchmaking in the YouTube Collaboration Arena</u></a></li>
<li><a href="https://techidaily.com/hard-reset-samsung-galaxy-s21-fe-5g-2023-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Samsung Galaxy S21 FE 5G (2023) in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-10-nano-drones-for-experienced-pilots/"><u>[New] Prime 10 Nano Drones for Experienced Pilots</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-frame-your-moment-iphone-apps-for-efficient-photo-cropping/"><u>[New] 2024 Approved  Frame Your Moment  IPhone Apps for Efficient Photo Cropping</u></a></li>
</ul></div>

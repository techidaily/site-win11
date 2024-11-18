---
title: Telnet Setup Simplified for Win11 Computers
date: 2024-11-16T20:17:56.537Z
updated: 2024-11-18T07:10:11.067Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Telnet Setup Simplified for Win11 Computers
excerpt: This Article Describes Telnet Setup Simplified for Win11 Computers
keywords: Win11 Telnet Guide,Simple Win11 Telnet,Windows Telnet Setup,Easy Win11 Connectivity,Win11 Network Access,Telnet Configuration Win11,Basic Win11 Telnet Tutorial
thumbnail: https://thmb.techidaily.com/1c82bb77bafb99b9b6611b5302d1fb010d446c70d3f6bad7daef0045c02e4cb1.png
---

## Telnet Setup Simplified for Win11 Computers

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148647/16836" target="_top" id="2148647">
  <img src="//a.impactradius-go.com/display-ad/16836-2148647" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148647/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/2024-approved-unveiling-the-hidden-power-of-windows-11/"><u>2024 Approved Unveiling the Hidden Power of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bring-back-missing-bluetooth-on-windows/"><u>How to Bring Back Missing Bluetooth on Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-vivo-v29-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Vivo V29</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/inside-look-at-your-lg-televisions-channels-what-you-must-understand/"><u>Inside Look at Your LG Television's Channels - What You Must Understand</u></a></li>
<li><a href="https://win11.techidaily.com/overlooked-wonders-of-windows-11-the-essential-skills/"><u>Overlooked Wonders of Windows 11 - The Essential Skills</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-honor-90-lite-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Honor 90 Lite</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-stuck-apps-camera-request-error-0xa00f4243/"><u>Unblocking Stuck App's Camera Request: Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/uninstall-and-re-install-restoring-windows-update-service/"><u>Uninstall and Re-Install: Restoring Windows Update Service</u></a></li>
<li><a href="https://os-tips.techidaily.com/1723620254672-when-your-iphone-battery-fails-explore-these-smart-repair-techniques/"><u>When Your iPhone Battery Fails, Explore These Smart Repair Techniques!</u></a></li>
</ul></div>


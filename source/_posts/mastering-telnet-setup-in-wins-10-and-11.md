---
title: Mastering Telnet Setup in Wins 10 & 11
date: 2025-03-02T20:44:58.253Z
updated: 2025-03-04T17:42:30.085Z
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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-what-does-the-signature-blue-glyph-on-messenger-stand-for/"><u>[New] 2024 Approved What Does the Signature Blue Glyph on Messenger Stand For?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-instagram-tips-how-to-perfectly-flip-videos-on-devices/"><u>[New] In 2024, Instagram Tips How to Perfectly Flip Videos on Devices</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-top-windows-10-capture-apps-ultimate-guide-for-2024/"><u>[New] Top Windows 10 Capture Apps Ultimate Guide for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-premiere-video-tools-for-iphone-for-2024/"><u>[Updated] Premiere Video Tools for iPhone for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capturing-clarity-perfecting-image-description-via-text-in-pcmac/"><u>Capturing Clarity Perfecting Image Description via Text in PC/Mac</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-x709-issue-windows-fix-guide/"><u>Correcting X709 Issue: Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/elite-selection-optimal-windows-options-for-switch-gaming/"><u>Elite Selection: Optimal Windows Options for Switch Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-security-8-ways-to-bypass-denials/"><u>Enhancing Windows Security: 8 Ways to Bypass Denials</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/first-steps-in-gopro-gear-selection/"><u>First Steps in GoPro Gear Selection</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/gli-strategici-passaggi-di-conversione-da-file-avi-a-mkv-metodi-favolosi-ed-economici/"><u>Gli Strategici Passaggi Di Conversione Da File AVI a MKV: Metodi Favolosi Ed Economici!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-vivo-y100-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Vivo Y100 Phones? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-vivo-s17-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Vivo S17 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-honor-v-purse-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Honor V Purse to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-cleaning-windows-temporaries/"><u>Mastering the Art of Cleaning Windows' Temporaries</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wordpads-activation-on-your-system/"><u>Mastering WordPad's Activation on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/native-windows-methods-to-emulate-data-existence/"><u>Native Windows Methods to Emulate Data Existence</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-capacity-analysis/"><u>Streamlining System Capacity Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-group-policies-for-specific-users-stepwise-approach/"><u>Tailored Group Policies for Specific Users: Stepwise Approach</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-improve-windows-roblox-performance-speed/"><u>Tips to Improve Windows Roblox Performance Speed</u></a></li>
</ul></div>


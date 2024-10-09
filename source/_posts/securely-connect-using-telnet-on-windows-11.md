---
title: Securely Connect Using Telnet on Windows 11
date: 2024-10-06T17:08:43.120Z
updated: 2024-10-08T18:55:03.259Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Connect Using Telnet on Windows 11
excerpt: This Article Describes Securely Connect Using Telnet on Windows 11
keywords: WinTelNetSecure,SecureWinTelConnect,SecureTelNet11,SecureWindows11,TelnetSecurityWin,SafeWinTelAccess,WindowsTelnetGuard
thumbnail: https://thmb.techidaily.com/7232672881e7d137d3952f765be2610288c45b29a2009d979134d6c02c0bbdb8.jpg
---

## Securely Connect Using Telnet on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148647/16836" target="_top" id="2148647">
  <img src="//a.impactradius-go.com/display-ad/16836-2148647" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148647/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/updated-srt-conversion-simplified-subtitles-transformation/"><u>[Updated] SRT Conversion Simplified Subtitles Transformation</u></a></li>
<li><a href="https://solve-latest.techidaily.com/1-convert-avi-files-to-mkv-format-gratis-step-by-step-guide-using-vlc-and-handbrake/"><u>1. Convert AVI Files to MKV Format Gratis: Step-by-Step Guide Using VLC and Handbrake</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-personal-vocalization-changing-your-tone-for-stories-and-reels/"><u>2024 Approved Personal Vocalization Changing Your Tone for Stories & Reels</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/a-step-by-step-tutorial-on-video-angles-using-vlc-for-2024/"><u>A Step-by-Step Tutorial on Video Angles Using VLC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-steps-for-pre-use-disk-formatting-error/"><u>Corrective Steps for Pre-Use Disk Formatting Error</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-windows-network-knowledge-with-ping-mastery/"><u>Elevating Your Windows Network Knowledge with Ping Mastery</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-embrace-facebooks-latest-dating-service/"><u>How to Embrace Facebook's Latest Dating Service</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-harnessing-online-platforms-beyond-youtube-to-30plus-communities/"><u>In 2024, Harnessing Online Platforms Beyond YouTube to 30+ Communities</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-could-not-create-snaps-in-windows-admin-tools/"><u>Overcoming 'Could Not Create' Snaps in Windows Admin Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-yellow-tint-restore-true-color-on-windows/"><u>Overcoming Yellow Tint: Restore True Color on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-missing-items-within-file-explorer/"><u>Reviving Missing Items Within File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-sessions-confirm-pcs-webcam-and-mic-beforehand/"><u>Seamless Sessions: Confirm PC's Webcam & Mic Beforehand</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-secure-windows-against-unauthorized-removable-storage/"><u>Steps to Secure Windows Against Unauthorized Removable Storage</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-switch-off-gpgpu-scheduling-on-the-winos-platform/"><u>Techniques: Switch Off GPGPU Scheduling on the WINOS Platform</u></a></li>
<li><a href="https://win11.techidaily.com/win11-printer-glitch-fixes-ad-ds-and-print-issues-explained/"><u>Win11 Printer Glitch Fixes: AD DS & Print Issues Explained</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/worlds-pioneer-risc-v-laptop-receives-impressive-overhaul-now-boasts-increased-core-count-turbocharged-clock-speed-at-2-ghz-and-advanced-ai-capabilities/"><u>World's Pioneer RISC-V Laptop Receives Impressive Overhaul - Now Boasts Increased Core Count, Turbocharged Clock Speed at 2 GHz, and Advanced AI Capabilities!</u></a></li>
</ul></div>


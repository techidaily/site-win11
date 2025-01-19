---
title: Mastering Telnet Setup in Wins 10 & 11
date: 2025-01-18T01:06:14.178Z
updated: 2025-01-18T22:40:12.604Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-tips.techidaily.com/n-2024-youtube-time-rewind-mastery-in-media-refreshes/"><u>[New] In 2024, YouTube Time Rewind Mastery in Media Refreshes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/aukey-30-usb-hub-assessment-unadorned-elegance-meets-practicality/"><u>Aukey 3.0 USB Hub Assessment: Unadorned Elegance Meets Practicality</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ing-a-successful-online-presence-wirecast-streaming-to-youtube-for-2024/"><u>Building a Successful Online Presence WireCast Streaming to Youtube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-nvidia-geforce-notaxc0f1103f-error/"><u>Correcting Windows Nvidia GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Tecno Spark Go (2023)? | Dr.fone</u></a></li>
<li><a href="https://win-cheats.techidaily.com/identifying-and-troubleshooting-sluggish-pc-performance-a-guide-by-yl-computing/"><u>Identifying and Troubleshooting Sluggish PC Performance: A Guide by YL Computing</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-lava-yuva-3-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Lava Yuva 3? Fix Now | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-honor-magic-5-lite-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Honor Magic 5 Lite Phones</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-turn-off-corner-shaping/"><u>Mastering Windows 11: Turn Off Corner Shaping</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-search-backup-procedure/"><u>Navigate to Windows 11 Search Backup Procedure</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-user-error-in-windows-1111/"><u>Overcoming Unauthorized User Error in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/post-install-windows-heres-how-to-get-online/"><u>Post-Install Windows? Here's How to Get Online</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-exception-breakpoint-errors/"><u>Strategies to Address Windows Exception Breakpoint Errors</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-slow-motion-spectrum-top-cams-reviewed-by-experts-for-2024/"><u>The Slow-Motion Spectrum Top Cams Reviewed by Experts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rediscovering-missing-panes-top-tips-and-hacks-for-windows-users/"><u>The Ultimate Guide to Rediscovering Missing Panes: Top Tips and Hacks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-optimizing-windows-lockscreen-with-spotlight/"><u>Tips for Optimizing Windows Lockscreen with Spotlight</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/top-3-free-ssd-cloning-tools-compatible-with-windows-11-10-8-and-7-best-of-the-year/"><u>Top 3 Free SSD Cloning Tools Compatible with Windows 11, 10, 8 & 7 - Best of the Year</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-high-performance-components-a-look-at-toms-hardware-recommendations/"><u>Unveiling High-Performance Components: A Look at Tom's Hardware Recommendations</u></a></li>
</ul></div>


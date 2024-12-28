---
title: Mastering Telnet Setup in Wins 10 & 11
date: 2024-12-21T05:37:51.396Z
updated: 2024-12-28T04:08:39.669Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-navigating-content-sharing-youtube-standards-vs-creative-commons/"><u>[New] 2024 Approved Navigating Content Sharing YouTube Standards Vs. Creative Commons</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-unlocking-potential-master-dvd-burning-with-your-mac/"><u>[New] 2024 Approved Unlocking Potential Master DVD Burning with Your Mac</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-effective-email-delivery-feedback-on-windows-machines/"><u>Enabling Effective Email Delivery Feedback on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-custom-pin-lengths-for-windows-users/"><u>Enhance Accessibility: Custom PIN Lengths for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/essential-preparations-what-you-need-prior-to-windows-overhaul/"><u>Essential Preparations: What You Need Prior To Windows Overhaul</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/fast-and-simple-setup-get-your-pioneer-dj-ddj-sx2-drivers-now/"><u>Fast and Simple Setup: Get Your Pioneer DJ DDJ-SX2 Drivers Now</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-90-lite-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor 90 Lite to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-elevate-your-channel-hit-the-10000-view-mark-fast/"><u>In 2024, Elevate Your Channel Hit the 10,000 View Mark Fast!</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-audio-collections-for-screen-clips/"><u>In 2024, Top Audio Collections for Screen Clips</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-vivo-y55s-5g-2023-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Vivo Y55s 5G (2023) Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11.techidaily.com/pros-choice-top-video-trimming-apps-for-windows-pcs/"><u>Pro's Choice: Top Video Trimming Apps for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/smartly-sorted-7-preferred-windows-photos-apps/"><u>Smartly Sorted: 7 Preferred Windows Photos Apps</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frequent-file-explorer-freezes-in-windows-11/"><u>Solving Frequent File Explorer Freezes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-ux-a-blueprint-of-essential-taskbar-amendments-in-windows-11/"><u>Streamlining UX: A Blueprint of Essential Taskbar Amendments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-nighttime-paints-dark-aesthetics/"><u>Transition to Nighttime: Paint's Dark Aesthetics</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-and-fixing-the-hp-code-43-error-in-your-printer/"><u>Understanding and Fixing the HP Code 43 Error in Your Printer</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-the-ultimate-guide-to-windows-powertoy-features/"><u>Unleash Potential: The Ultimate Guide to Windows PowerToy Features</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-here-weve-selected-some-of-the-best-online-video-compressors-for-compressing-webm-videos-with-best-quality/"><u>Updated In 2024, Here Weve Selected some of the Best Online Video Compressors for Compressing WebM Videos with Best Quality</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-honor-x8b-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Honor X8b Phone Network-Ready</u></a></li>
</ul></div>


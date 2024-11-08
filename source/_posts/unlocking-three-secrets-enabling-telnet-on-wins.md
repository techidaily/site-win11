---
title: "Unlocking Three Secrets: Enabling Telnet on Wins"
date: 2024-11-02T20:51:22.042Z
updated: 2024-11-07T18:34:07.643Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Three Secrets: Enabling Telnet on Wins"
excerpt: "This Article Describes Unlocking Three Secrets: Enabling Telnet on Wins"
keywords: WinTelnet Basics,EnableTelnet Windows,SecretWinTelnetAccess,UnlockWinTelNetSecrets,TelnetSetupGuideWin,WinsConnectEasyMethod,SecureWinTelnetConnection
thumbnail: https://thmb.techidaily.com/c7a57ea0c6d875a784d917881bf9f1dac3c811b03454856c62819bb5612b0808.jpg
---

## Unlocking Three Secrets: Enabling Telnet on Wins

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

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352557/5172" target="_top" id="352557">
  <img src="//a.impactradius-go.com/display-ad/5172-352557" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352557/5172" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-top-picks-in-the-market-for-cheap-but-high-quality-screens/"><u>[New] Top Picks in the Market for Cheap but High-Quality Screens</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unveiling-the-secrets-to-a-flawless-fb-live-session/"><u>[New] Unveiling the Secrets to a Flawless FB Live Session</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-secure-your-facetime-discussions-with-screen-record/"><u>[Updated] In 2024, Secure Your FaceTime Discussions with Screen Record</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-audioanalyzer-reaction-to-recordings/"><u>2024 Approved AudioAnalyzer Reaction to Recordings</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instas-power-players-a-guide-to-your-niches-movers-and-shakers/"><u>2024 Approved Insta’s Power Players A Guide to Your Niche's Movers & Shakers</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-unwanted-edge-desktop-buttons/"><u>Disabling Unwanted Edge Desktop Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-this-file-has-no-app-windows-issue/"><u>Eliminating 'This File Has No App' Windows Issue</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/guide-complete-comment-installer-le-logiciel-de-montage-video-libre-pour-votre-lecteur-dvd-en-une-journee/"><u>Guide Complète : Comment Installer Le Logiciel De Montage Vidéo Libre Pour Votre Lecteur DVD en Une Journée</u></a></li>
<li><a href="https://win11.techidaily.com/guide-finding-the-storage-for-your-desktop-pics/"><u>Guide: Finding the Storage for Your Desktop Pics</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-techs-leap-into-the-win11-era-a-roadmap/"><u>Legacy Tech's Leap Into the Win11 Era: A Roadmap</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/next-gen-processors-faceoff-the-ryzen-5-9600x-vs-ryzen-n-7-9700x-review-for-ultimate-gaming-experience-on-zen-5-architecture/"><u>Next-Gen Processors Faceoff: The Ryzen 5 9600X Vs. Ryzen N 7 9700X Review for Ultimate Gaming Experience on Zen 5 Architecture</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-screen-quality-resetting-graphics-in-windows-11/"><u>Optimize Screen Quality: Resetting Graphics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-stranded-status-on-xbox-for-pc-a-practical-approach/"><u>Solving ‘Stranded’ Status on Xbox for PC: A Practical Approach</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-to-the-not-supported-interface-error/"><u>Swift Solutions to the Not-Supported Interface Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-essential-guide-to-choosing-a-free-internet-phone-service-in-202-communication-tools-best-free-calls-apps-for-this-year/"><u>The Essential Guide to Choosing a Free Internet Phone Service in 202 # Communication Tools: Best Free Calls Apps for This Year!</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-managing-deletion-alerts-in-windows-os/"><u>Tips for Managing Deletion Alerts in Windows OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-picks-downloading-templates-from-youtube-vids-for-2024/"><u>Top Picks Downloading Templates From YouTube Vids for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-pubgs-network-errors-for-a-smoother-gaming-experience/"><u>Troubleshooting PUBG's Network Errors for a Smoother Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-taskbar-chat-discontinuation-what-does-this-mean-for-us/"><u>Windows 11 Taskbar Chat Discontinuation: What Does This Mean for Us?</u></a></li>
</ul></div>


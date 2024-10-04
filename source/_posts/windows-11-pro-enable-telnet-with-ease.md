---
title: "Windows 11 Pro: Enable Telnet with Ease"
date: 2024-09-27T01:22:02.023Z
updated: 2024-10-03T20:40:32.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Pro: Enable Telnet with Ease"
excerpt: "This Article Describes Windows 11 Pro: Enable Telnet with Ease"
keywords: Windows 11 Telnet Setup,Windows 11 Pro Easy Telnet,Enabling Telnet in Win11 Pro,Windows 11 Pro Telnet Access,Pro Telnet Feature on Win11,Windows 11 Pro Telnet Function,Easy Win11 Pro Telnet
thumbnail: https://thmb.techidaily.com/39eb12846caac832ee1b1d85070e2dd4cb557f02287ca2d451303bdd76b5dd20.jpg
---

## Windows 11 Pro: Enable Telnet with Ease

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
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

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-final-cut-pro-x-achieving-perfect-vertical-video-for-instagram-for-2024/"><u>[New] Final Cut Pro X Achieving Perfect Vertical Video for Instagram for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-bridging-platforms-for-broad-sharing-instagram-and-facebook/"><u>[New] In 2024, Bridging Platforms for Broad Sharing Instagram & Facebook</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ites-bridging-you-with-googles-advertising-on-youtube-for-2024/"><u>[New] Sites Bridging You with Google's Advertising on Youtube for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-optimize-viewing-experience-on-netflix-platforms/"><u>[Updated] How to Optimize Viewing Experience on Netflix Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/playstation/"><u>「PlayStationのロイロゲームレコーダー使い方：詳細ガイド」</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-minecraft-logo-designs-for-youtube-channels/"><u>2024 Approved Minecraft Logo Designs for YouTube Channels</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/enhancing-content-reach-keeping-creative-commons-engagement-high-for-2024/"><u>Enhancing Content Reach Keeping Creative Commons Engagement High for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-samsung-galaxy-a25-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Samsung Galaxy A25 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-ways-disabling-closed-captions-in-vlc-player-top-3-methods/"><u>Quick & Easy Ways: Disabling Closed Captions in VLC Player - Top 3 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-audio-extraction-from-dvds-speedy-software-solutions/"><u>Quick Guide to Audio Extraction From DVDs - Speedy Software Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/record-voice-clips-using-windows-snipping-tool-a-complete-explanation/"><u>Record Voice Clips Using Windows' Snipping Tool - A Complete Explanation!</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-honor-magic-5-pro-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Honor Magic 5 Pro Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/simple-tricks-effective-methods-to-reduce-email-attachments-by-compressing-videos/"><u>Simple Tricks: Effective Methods to Reduce Email Attachments by Compressing Videos</u></a></li>
<li><a href="https://win11.techidaily.com/solve-your-firefox-video-problems-with-these-8-proven-strategies/"><u>Solve Your Firefox Video Problems with These 8 Proven Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-webm-videos-to-mp4-on-windows-11/"><u>Step-by-Step Guide: Converting WebM Videos to MP4 on Windows 11</u></a></li>
</ul></div>


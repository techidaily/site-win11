---
title: "Telnet Setup: Win11 & Win11 Tips"
date: 2024-11-06T21:41:42.970Z
updated: 2024-11-07T19:29:59.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Telnet Setup: Win11 & Win11 Tips"
excerpt: "This Article Describes Telnet Setup: Win11 & Win11 Tips"
keywords: Win11 Telnet Basics,Telnet Win11 Guide,Secure Win11 Telnet,Win11 Networking Setup,Windows 11 Connectivity,Win11 Remote Access Tips,Telnet Client for Win11
thumbnail: https://thmb.techidaily.com/41b376d29e85724c5481e57f7a36ad6deb299d08d21887a298dcedb2ce73aa51.jpg
---

## Telnet Setup: Win11 & Win11 Tips

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
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
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

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-a-beginners-roadmap-for-instagram-reels-mastery/"><u>[New] In 2024, A Beginner's Roadmap for Instagram Reels Mastery</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-essential-guide-to-the-top-5-windows-snipper-tools/"><u>[New] In 2024, Essential Guide to The Top 5 Windows Snipper Tools</u></a></li>
<li><a href="https://program-issues.techidaily.com/solved-fallout-3-not-launching-2024-tips/"><u>[Solved] Fallout 3 Not Launching | 2024 Tips</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-efficient-tweet-strategy-embrace-aspect-ratio-specifications/"><u>[Updated] 2024 Approved Efficient Tweet Strategy Embrace Aspect Ratio Specifications</u></a></li>
<li><a href="https://win11.techidaily.com/mkvmp3/"><u>完全ガイド：MKV形式のビデオから高品質なMP3音声ファイルへの変換手順</u></a></li>
<li><a href="https://win11.techidaily.com/iuacgombqeobquodkplusodhplusocquoduplusocquodvoodhplusocoplusocquodleocoeocpoodqplusobrueiuuiqjeobqpluswheimgshjgrpjg7zjg4fjg4pjgqjg4hjgqfjg4pjgqvjg7zmjqjlp77/"><u>最適なビデオ・オーディオファイルの確認に必要!コーデックチェッカー推奨:映像･音声用</u></a></li>
<li><a href="https://win11.techidaily.com/dvdfire/"><u>DVDコンテンツをFireタブレットで表示する手順及び再生が不可能な場合の対策</u></a></li>
<li><a href="https://win11.techidaily.com/easily-download-youtube-videos-as-mp3-a-free-tool-guide/"><u>Easily Download YouTube Videos as MP3: A Free Tool Guide</u></a></li>
<li><a href="https://win-online.techidaily.com/effizientes-wiederauffinden-geloschter-bilder-auf-twitter-die-einfachen-schritte-zum-recovery/"><u>Effizientes Wiederauffinden Gelöschter Bilder Auf Twitter: Die Einfachen Schritte Zum Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-techniques-for-transforming-flv-media-files-into-streamlined-mp4s/"><u>Effortless Techniques for Transforming FLV Media Files Into Streamlined MP4s</u></a></li>
<li><a href="https://fox-access.techidaily.com/eminent-exchanges-a-curated-list-of-top-reddit-posts/"><u>Eminent Exchanges A Curated List of Top Reddit Posts</u></a></li>
<li><a href="https://win11.techidaily.com/free-guide-converting-wma-audio-files-to-m4a-format-using-windows/"><u>Free Guide: Converting WMA Audio Files to M4A Format Using Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-apple-iphone-13-when-phone-is-broken-by-drfone-ios/"><u>In 2024, How to Turn Off Find My Apple iPhone 13 when Phone is Broken?</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/pcdvd/"><u>PCやスマートフォンに移行できるDVDへのビデオコピー手順</u></a></li>
<li><a href="https://games-able.techidaily.com/this-app-lets-you-play-nintendo-classics-on-your-iphone-heres-how/"><u>This App Lets You Play Nintendo Classics on Your iPhone: Here's How</u></a></li>
</ul></div>


---
title: "Streamline Connectivity: How to Enable Telnet in Windows OS"
date: 2024-09-05T08:28:55.004Z
updated: 2024-09-06T08:28:55.004Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamline Connectivity: How to Enable Telnet in Windows OS"
excerpt: "This Article Describes Streamline Connectivity: How to Enable Telnet in Windows OS"
keywords: Enabling Telnet Windows,Telnet Windows OS,Streamline Telnet Access,Connect Telnet Windows,Telnet Enablement WinOS,Optimize Telnet Usage,Telnet Windows Setup
thumbnail: https://thmb.techidaily.com/7e53aeacfe9180f7bf103bd851c0952fea27590b967ba6821cf8991af471fa5a.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Streamline Connectivity: How to Enable Telnet in Windows OS

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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-counterclockwise-playback-in-instagram-videos/"><u>[Updated] 2024 Approved  Counterclockwise Playback in Instagram Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-explore-fauna-fun-top-12-android-simulation-games/"><u>[Updated] 2024 Approved  Explore Fauna Fun  Top 12 Android Simulation Games</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-snaps-in-zooms-camera-feature/"><u>[Updated] 2024 Approved  Mastering Snaps in Zoom's Camera Feature</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-elevate-content-with-properly-sized-videos-on-instagram-for-2024/"><u>[Updated] Elevate Content with Properly Sized Videos on Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-evasion-techniques-for-youtube-bans-for-2024/"><u>[Updated] Evasion Techniques for YouTube Bans for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-unlocking-slow-motion-magic-in-instagram-reels/"><u>[Updated] In 2024, Unlocking Slow Motion Magic in Instagram Reels</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-7-tips-to-make-your-tasty-cooking-videos/"><u>2024 Approved  7 Tips to Make Your Tasty Cooking Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-through-top-6-ideal-helmet-harnesses-for-gopros/"><u>2024 Approved  Navigating Through Top 6 Ideal Helmet Harnesses for GoPros</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-lava-yuva-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-to-filter-kids-web-activity/"><u>Configuring Windows 11 to Filter Kids' Web Activity</u></a></li>
<li><a href="https://win11.techidaily.com/cure-voice-command-issues-reactivation-techniques-for-win11/"><u>Cure Voice Command Issues: Reactivation Techniques for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fast-focus-furious-fighting-efficient-gameplay-fixes-for-bf2/"><u>Fast Focus, Furious Fighting: Efficient Gameplay Fixes for BF2</u></a></li>
<li><a href="https://howto.techidaily.com/fix-realme-c33-2023-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Realme C33 2023 Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-external-monitor-not-detected-issue-in-windows/"><u>Fixing External Monitor Not Detected Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-most-out-of-wsl-2-on-modern-windows-dev-systems/"><u>Get the Most Out of WSL 2 on Modern Windows Dev Systems</u></a></li>
<li><a href="https://win11.techidaily.com/hands-on-steps-for-buying-adobe-reader-in-microsoft-store/"><u>Hands-On Steps for Buying Adobe Reader in Microsoft Store</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-14-pro-max-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 14 Pro Max To Other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-xiaomi-13t-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Xiaomi 13T Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-video-player-face-off-vlc-versus-mpc/"><u>In 2024, Free Video Player Face-Off  VLC Versus MPC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-tecno-camon-30-pro-5g-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Tecno Camon 30 Pro 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-or-minimize-windows-11-taskbar/"><u>Maximize or Minimize Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-asana-setbacks-a-guide-for-windows-users/"><u>Navigating Asana Setbacks: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/old-meets-new-again-seven-core-windows-characteristics-evolving/"><u>Old Meets New Again: Seven Core Windows Characteristics Evolving</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-infinix-gt-10-pro-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Infinix GT 10 Pro? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-stay-connected-eight-ways-to-enhance-win11-point/"><u>Reconnect and Stay Connected: Eight Ways to Enhance Win11' Point</u></a></li>
<li><a href="https://games-able.techidaily.com/rectifying-the-issue-error-code-262-on-roblox/"><u>Rectifying the Issue: Error Code 262 on Roblox</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-unresponsive-xbox-on-windows-with-ease/"><u>Resolve Unresponsive Xbox on Windows with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-alerts-on-desktop-applets/"><u>Restoring Alerts on Desktop Applets</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-installation-blockers-for-effective-win-11-uninstalls/"><u>Sidestep Installation Blockers for Effective Win 11 Uninstalls</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frustrating-asana-issues-with-a-step-by-step-guide/"><u>Solving Frustrating Asana Issues with a Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stop-chromes-spontaneous-tab-triggers-on-windows-desktop/"><u>Stop Chrome's Spontaneous Tab Triggers on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-decrease-cpu-strain-from-tiworkerexe-processes/"><u>Strategies to Decrease CPU Strain From TiWorker.exe Processes</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-fixing-windows-error-0xc00000f/"><u>Swift Solution to Fixing Windows Error 0Xc00000f</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unsupported-device-format-required-in-windows/"><u>Tackling Unsupported Device: Format Required in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rotating-images-on-win11/"><u>The Ultimate Guide to Rotating Images on Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-considerations-for-enhancing-your-4k-cinematic-quality-for-2024/"><u>Top Considerations for Enhancing Your 4K Cinematic Quality for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-the-impact-of-season-8-updates-on-fortnites-frame-rate-and-gameplay-experience/"><u>Understanding the Impact of Season 8 Updates on Fortnite's Frame Rate and Gameplay Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-of-old-computers-without-windows/"><u>Unleash Potential of Old Computers Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-efficient-directory-creation-with-newest-windows-oses/"><u>Unleash the Power of Efficient Directory Creation with Newest Windows OSes</u></a></li>
</ul></div>

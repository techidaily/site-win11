---
title: "Step-by-Step: Telnet Enablement in Win11"
date: 2024-07-02T13:01:38.117Z
updated: 2024-07-03T13:01:38.117Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Telnet Enablement in Win11"
excerpt: "This Article Describes Step-by-Step: Telnet Enablement in Win11"
keywords: Win11 Telnet Setup Guide,Enabling Telnet Windows 11,Stepwise Telnet Activation WS11,Win11 Telnet Configuration Tutorial,Telnet in Windows 11 Easy Steps,Enable Telnet Service WS11,Win11 Guide
thumbnail: https://thmb.techidaily.com/e77b802386df347968174243d9eec6b1ff5aaa13a757fb94ecaebe8d1775e8b5.jpg
---

## Step-by-Step: Telnet Enablement in Win11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

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

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
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
<li><a href="https://win11.techidaily.com/unblocking-the-blocked-fixing-windows-access-issues/"><u>Unblocking the Blocked: Fixing Windows Access Issues</u></a></li>
<li><a href="https://win11.techidaily.com/improve-cs-global-offensive-speed-and-precision/"><u>Improve CS Global Offensive Speed and Precision</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-top-8-troubleshooting-steps/"><u>Mastering Windows: Top 8 Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unrecognized-hardware-issue-on-windows-1110/"><u>Solving ‘Unrecognized Hardware’ Issue on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-routines-installing-app-shortcuts-in-desktop-menu/"><u>Convenient Routines: Installing App Shortcuts in Desktop Menu</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-chrome-profile-errors-for-windows-users/"><u>Unraveling Chrome Profile Errors for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-login-validity-and-failures/"><u>Assessing Windows Login Validity and Failures</u></a></li>
<li><a href="https://win11.techidaily.com/1719301836134-clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now!</u></a></li>
<li><a href="https://win11.techidaily.com/simple-fixes-resetting-windows-setup-post-reboot/"><u>Simple Fixes: Resetting Windows Setup Post-Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-fast-approach-downloading-tweets-video-content-for-mobile-use/"><u>[Updated] In 2024, Fast Approach  Downloading Tweets’ Video Content for Mobile Use</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-explore-cost-free-cross-platform-virtual-communication-software/"><u>[New] Explore Cost-Free, Cross-Platform Virtual Communication Software</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-video-mastery-unlocked-the-top-5-online-techniques-to-shorten-vimeo-content/"><u>[New] Video Mastery Unlocked  The Top 5 Online Techniques to Shorten Vimeo Content</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-spark-20c-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Spark 20C</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-xiaomi-civi-3-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Xiaomi Civi 3 to Roku | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfersync-notes-from-apple-iphone-12-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer/Sync Notes from Apple iPhone 12 to iPad | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-expert-recommendations-free-chat-apps-with-screen-viewing/"><u>2024 Approved  Expert Recommendations  Free Chat Apps with Screen Viewing</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-track-analyze-improve-top-motion-tracking-apps-for-athletes-and-more-for-2024/"><u>Updated Track, Analyze, Improve Top Motion Tracking Apps for Athletes and More for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/adobe-premiere-pro-tutorial-eliminate-camera-shake-and-rolling-shutter/"><u>Adobe Premiere Pro Tutorial Eliminate Camera Shake and Rolling Shutter</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-10-essential-aspect-ratio-resizer-tools-you-need/"><u>2024 Approved 10 Essential Aspect Ratio Resizer Tools You Need</u></a></li>
</ul></div>

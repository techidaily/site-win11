---
title: Unlocking Secure Telnet Access on Modern Windows
date: 2024-09-11T09:45:04.437Z
updated: 2024-09-12T09:45:04.437Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Secure Telnet Access on Modern Windows
excerpt: This Article Describes Unlocking Secure Telnet Access on Modern Windows
keywords: Secure Telnet Windows,Telnet Security Windows,Windows Telnet Protocol,Modern Windows Telnet,Windows Telnet Access,Enhancing Windows Telnet,Telnet Secure Connection Windows
thumbnail: https://thmb.techidaily.com/cdded6aa8f500657d1cc67ca7b77cb926c32d80c757bf8e50b4e15a0eac70eb2.jpg
---

## Unlocking Secure Telnet Access on Modern Windows

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115911/19272" target="_top" id="2115911">
  <img src="//a.impactradius-go.com/display-ad/19272-2115911" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115911/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-top-8-online-learning-paths-for-newcomers-to-video/"><u>[Updated] 2024 Approved Top 8 Online Learning Paths for Newcomers to Video</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-spectra-adjustment-suite/"><u>2024 Approved Spectra Adjustment Suite</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-oneplus-nord-ce-3-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/adding-tunes-to-your-ios-clips-three-no-cost-ways-explored/"><u>Adding Tunes to Your iOS Clips – Three No-Cost Ways Explored</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tips-for-dealing-with-system-calls-in-windows/"><u>Comprehensive Tips for Dealing With System Calls in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-win11s-systray-with-caps-lock-and-num-key-icons/"><u>Customizing Win11's SysTray with Caps Lock & Num Key Icons</u></a></li>
<li><a href="https://win11.techidaily.com/file-organization-breakthroughs-with-simultaneous-window-folders/"><u>File Organization Breakthroughs with Simultaneous Window Folders</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-vivo-y36-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-netflix-app-when-it-stops-working-in-windows/"><u>How to Fix the Netflix App When It Stops Working in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-dull-to-dynamic-a-pros-guide-to-shade-shifting/"><u>In 2024, From Dull to Dynamic A Pro's Guide to Shade Shifting</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-iphone-14-plus-drfone-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-windows-settings-app-crashing-try-these-fixes/"><u>Is the Windows Settings App Crashing? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-customizing-desktop-pictures-in-windows/"><u>Master the Art of Customizing Desktop Pictures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-correction-windows-11-wow-mishaps/"><u>Mastering Error Correction: Windows 11 WoW Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-speech-to-text-the-whisper-desktop-way/"><u>Mastering Speech-to-Text: The Whisper Desktop Way</u></a></li>
<li><a href="https://win11.techidaily.com/mending-misidentified-gaming-status-on-discord-pc-edition/"><u>Mending Misidentified Gaming Status on Discord, PC Edition</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-reactivate-nonfunctional-nvidia-cp/"><u>Methods to Reactivate Nonfunctional Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-ai-hub-revolutionizing-retail-shopping/"><u>Microsoft AI Hub: Revolutionizing Retail Shopping</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-default-save-issues-in-modern-windows/"><u>Preventing Default Save Issues in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-for-windows-11s-software-folder-restarts/"><u>Quick-Fix Guide for Windows 11'S Software Folder Restarts</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-d3d11-compatible-graphics-errors-in-win11win10/"><u>Resolving D3D11 Compatible Graphics Errors in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-read-error-on-windows-os/"><u>Resolving Disk Read Error on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-installing-kali-into-your-windows-ecosystem/"><u>Step by Step: Installing Kali Into Your Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-dns-flushing-in-modern-windows/"><u>Step-by-Step DNS Flushing in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-the-roblox-must-close-warning-in-windows/"><u>Steps to Eliminate the 'Roblox Must Close' Warning in Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/stop-instant-video-capture-effortlessly-using-quicktime-for-2024/"><u>Stop Instant Video Capture Effortlessly Using QuickTime for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-backup-cortanas-digital-footprint-windows/"><u>Strategies to Backup Cortana's Digital Footprint (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/stream-gaming-secrets-integrating-intelligence-with-intel/"><u>Stream Gaming Secrets: Integrating Intelligence with Intel</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamline-caption-insertion-photos-app-tutorials-for-win-11-for-2024/"><u>Streamline Caption Insertion Photos App Tutorials for WIN 11 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-background-services-on-windows/"><u>Streamlining Background Services on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-non-storage-feedback/"><u>Tackling Windows Camera Non-Storage Feedback</u></a></li>
<li><a href="https://win11.techidaily.com/the-skillful-technique-to-obscure-window-11-search/"><u>The Skillful Technique to Obscure Window 11 Search</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-srt-primer-for-enthusiasts-for-2024/"><u>The Ultimate SRT Primer for Enthusiasts for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-itel-p40plus-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Itel P40+ for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-six-reasons-for-switching-to-win11-from-macos/"><u>Top Six Reasons for Switching to Win11 From macOS</u></a></li>
<li><a href="https://win11.techidaily.com/track-down-absent-control-settings-on-your-new-pc/"><u>Track Down Absent Control Settings on Your New PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-persistent-windows-volume-mixer/"><u>Troubleshooting Non-Persistent Windows Volume Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x800f082f-with-dism/"><u>Troubleshooting Windows Error 0X800F082F with DISM</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-mastering-github-desktop-for-windows-based-developers/"><u>Tutorial: Mastering GitHub Desktop for Windows-Based Developers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-mastering-the-art-of-selecting-multiple-emails-in-gmail/"><u>Ultimate Guide: Mastering the Art of Selecting Multiple Emails in Gmail</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-giants-identifying-heavy-disk-space-usage-on-pcs/"><u>Uncovering Giants: Identifying Heavy Disk Space Usage on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-1011-remote-errors-quickly/"><u>Unraveling Windows 10/11 Remote Errors Quickly</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-8-best-professional-audio-editing-software-for-powerful-editing/"><u>Updated 2024 Approved 8 Best Professional Audio Editing Software for Powerful Editing</u></a></li>
<li><a href="https://win11.techidaily.com/win-operating-system-customize-how-you-handle-file-deletions/"><u>Win Operating System: Customize How You Handle File Deletions</u></a></li>
</ul></div>


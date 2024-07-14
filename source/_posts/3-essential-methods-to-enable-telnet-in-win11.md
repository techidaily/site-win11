---
title: 3 Essential Methods to Enable Telnet in Win11
date: 2024-07-13T11:15:02.972Z
updated: 2024-07-14T11:15:02.972Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Essential Methods to Enable Telnet in Win11
excerpt: This Article Describes 3 Essential Methods to Enable Telnet in Win11
keywords: Win11 Telnet Setup,Enabling Windows 11 Telnet,Telnet Access in Win11,Win11 Connect via Telnet,Methods for Win11 Telnet,Activating Telnet on Win11,Secure Telnet Win11
thumbnail: https://thmb.techidaily.com/dd4233ccec15666d6d616a1b1df2dfb0cda2d2ae21f58fe6b6f759379250d50d.jpg
---

## 3 Essential Methods to Enable Telnet in Win11

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
<li><a href="https://win11.techidaily.com/a-compreenas-of-the-most-reliable-window-pomodoros-for-work/"><u>A Compreenas of The Most Reliable Window Pomodoros for Work</u></a></li>
<li><a href="https://win11.techidaily.com/1719352483219-resurrect-computer-sounds-immediate-action-steps/"><u>Resurrect Computer Sounds – Immediate Action Steps!</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719330298923-self-host-your-local-free-windows-based-chatgpt-clone-using-gpt4all/"><u>Self-Host Your Local, FREE Windows-Based ChatGPT Clone Using GPT4All.</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-the-cant-switch-out-of-s-mode-issue-in-windows-11-or-10/"><u>9 Ways to Fix the “Can’t Switch Out of S Mode” Issue in Windows 11 or 10</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/mac-snapshot-strategies-revealed-the-top-5-innovative-approaches-for-2024/"><u>Mac Snapshot Strategies Revealed  The Top 5 Innovative Approaches for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-essential-how-to-guide-for-filming-anywhere-anytime/"><u>[New] 2024 Approved  The Essential How-To Guide for Filming Anywhere, Anytime</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-oppo-a1x-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719320743244-windows-users-run-a-cost-free-locally-operated-gpt-model/"><u>Windows Users: Run a Cost-Free, Locally Operated GPT Model</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-mend-windows-1011-discord-errors/"><u>A Step-by-Step Approach to Mend Windows 10/11 Discord Errors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/grasping-the-glossary-of-virtual-worlds-for-2024/"><u>Grasping the Glossary of Virtual Worlds for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-typing-mastering-windows-powertoys/"><u>Accelerate Typing: Mastering Windows PowerToys</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-numbers-game-estimating-income-from-viral-content/"><u>2024 Approved  The Numbers Game  Estimating Income From Viral Content</u></a></li>
<li><a href="https://win11.techidaily.com/a-tutorial-on-windows-media-player-launching/"><u>A Tutorial on Windows Media Player Launching</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-preserving-your-win-11-push-notification-functionality/"><u>A Guide to Preserving Your Win 11 Push Notification Functionality</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-video-editing-on-chromebook-a-step-by-step-guide-to-using-any-app/"><u>2024 Approved Video Editing on Chromebook A Step-by-Step Guide to Using Any App</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-free-video-viewing-software-guide-top-16/"><u>[Updated] Best Free Video Viewing Software Guide - Top 16</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-enhance-clarity-of-online-dialogues-with-discords-voicemod-feature-for-2024/"><u>[New] Enhance Clarity of Online Dialogues with Discord's VoiceMod Feature for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-the-negative-side-of-low-end-windows-licenses/"><u>A Deep Dive Into the Negative Side of Low-End Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-fix-the-windows-terminal-not-opening/"><u>6 Ways to Fix the Windows Terminal Not Opening</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-keeping-your-tasks-visible-and-high-priority/"><u>A Guide to Keeping Your Tasks Visible and High-Priority</u></a></li>
<li><a href="https://win11.techidaily.com/1719337262601-cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly.</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-elevating-your-presence-a-guide-to-discord-broadcasts/"><u>[New] Elevating Your Presence  A Guide to Discord Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/1719349600813-troubleshoot-unlock-handbrake-on-widows/"><u>Troubleshoot: Unlock HandBrake on Widows!</u></a></li>
<li><a href="https://win11.techidaily.com/1719336940768-cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now.</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-to-completely-erase-data-on-iphone-12-mini-to-avoid-privacy-leak-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Guide to Completely Erase Data on iPhone 12 mini to Avoid Privacy Leak | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-vulnerability-alerts/"><u>A Comprehensive Look at Windows’ Vulnerability Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/1719374553725-new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/"><u>New Era of Connectivity: Windows for iPhones, iPads and PCs Just Dropped</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-the-best-apps-to-master-sound-transformation-for-2024/"><u>Unveiling the Best Apps to Master Sound Transformation for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-mastering-instagrams-filter-system-free-at-your-fingertips-for-2024/"><u>[Updated] Mastering Instagram's Filter System – Free, at Your Fingertips for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-game-magic-discover-4-ways-to-preserve-your-gaming-sessions-for-2024/"><u>In-Game Magic  Discover 4 Ways to Preserve Your Gaming Sessions for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-2022-olympic-sprint-ice-key-moments-and-winners/"><u>[New] 2022 Olympic Sprint Ice  Key Moments and Winners</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-activatedeactivate-windows-low-power-mode/"><u>A Quick Guide: Activate/Deactivate Windows' Low-Power Mode</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-360-degree-shoot-selecting-your-perfect-model/"><u>2024 Approved  Ultimate 360-Degree Shoot  Selecting Your Perfect Model</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-honor-magic-vs-2-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Honor Magic Vs 2 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-tailoring-sound-fades-within-logic-pro-settings/"><u>[Updated] Tailoring Sound Fades Within Logic Pro Settings</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-reviving-stuck-windows-itunes/"><u>A Comprehensible Guide to Reviving Stuck Windows iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/5-strategies-for-switching-out-of-unwanted-night-mode/"><u>5 Strategies for Switching Out of Unwanted Night Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-plan-for-reclaiming-your-disconnected-ps4-link/"><u>A Step-by-Step Plan for Reclaiming Your Disconnected PS4 Link</u></a></li>
<li><a href="https://win11.techidaily.com/8-mistakes-you-should-avoid-making-as-a-beginner-to-windows-11/"><u>8 Mistakes You Should Avoid Making as a Beginner to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-fix-the-secure-boot-state-unsupported-error-in-windows/"><u>5 Ways to Fix the Secure Boot State Unsupported Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/30-minute-guide-to-resolving-windows-onedrive-fails/"><u>30 Minute Guide to Resolving Windows OneDrive Fails</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-winning-path-with-efficient-play/"><u>Accelerate Your Winning Path with Efficient Play</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-discords-ultimate-romance-hubs-for-2024/"><u>[New] Discord's Ultimate Romance Hubs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-out-of-recovery-or-dfu-mode-on-iphone-se-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery or DFU Mode on iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-judicious-use-of-ping-in-windows-operations/"><u>A Guide to Judicious Use of Ping in Windows Operations</u></a></li>
<li><a href="https://win11.techidaily.com/6-simple-time-management-and-productivity-apps-for-windows/"><u>6 Simple Time Management and Productivity Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-or-disable-the-delete-confirmation-dialog-on-windows/"><u>3 Ways to Enable or Disable the Delete Confirmation Dialog on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-peak-auto-clickers-hotkeys-plus-high-performance/"><u>5 Peak Auto Clickers: Hotkeys + High Performance</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-easing-into-your-youtube-watches-3-methods-50-chars/"><u>[Updated] In 2024, Easing Into Your YouTube Watches  3 Methods (50 Chars)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-the-15-most-influential-books-spotted-by-booktok-followers/"><u>[Updated] 2024 Approved  The 15 Most Influential Books Spotted by BookTok Followers</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-overview-using-nearby-share-effectively/"><u>A Comprehensive Overview: Using Nearby Share Effectively</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-step-by-step-guide-to-enhancing-old-photos-and-videos-with-ig-effects/"><u>[New] In 2024, Step-by-Step Guide to Enhancing Old Photos and Videos with IG Effects</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-adding-virtual-gaming-archives-into-playnite/"><u>A Comprehensive Guide to Adding Virtual Gaming Archives Into Playnite</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-flat-to-360-comparing-googles-cardboard-and-samsungs-gear-for-2024/"><u>From Flat to 360  Comparing Google's Cardboard & Samsung's Gear for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719360575372-trouble-on-windows-discover-assistance-methods/"><u>Trouble on Windows? Discover Assistance Methods!</u></a></li>
<li><a href="https://win11.techidaily.com/1719328494393-uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present!</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719370702854-unlock-adobe-photoshop-on-windows-11-and-11/"><u>Unlock Adobe Photoshop on Windows 11 & 11,</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-accelerate-your-videos-10-free-speed-changer-apps-for-ios-and-android/"><u>Updated In 2024, Accelerate Your Videos 10 Free Speed Changer Apps for iOS and Android</u></a></li>
<li><a href="https://win11.techidaily.com/1719356384376-mastery-over-mute-shift-key-trouble/"><u>Mastery Over Mute Shift Key Trouble</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/best-16-youtube-intro-makers-to-bring-you-more-views/"><u>Best 16 YouTube Intro Makers to Bring You More Views</u></a></li>
</ul></div>

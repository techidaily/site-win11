---
title: Quick Guide to Telnet Activation on Modern Windows
date: 2024-07-13T10:24:59.326Z
updated: 2024-07-14T10:24:59.326Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Telnet Activation on Modern Windows
excerpt: This Article Describes Quick Guide to Telnet Activation on Modern Windows
keywords: Quick Telnet Windows,Activate Telnet Prog,Telnet Windows Guide,Enable Windows Telnet,Windows Telnet Setup,Fast Telnet Methods,Modern Win Telnet On
thumbnail: https://thmb.techidaily.com/ef64597bda93820e24d8ab2d0a8cbf446e80301b9ceb1303c686c48229c6eca3.jpg
---

## Quick Guide to Telnet Activation on Modern Windows

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
<li><a href="https://fox-direct.techidaily.com/10-best-sites-to-download-free-slideshow-templates-for-2024/"><u>10 Best Sites to Download Free Slideshow Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-drive-letters-reasons-and-redeeming-solutions-explored/"><u>Windows Without Drive Letters: Reasons and Redeeming Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-compatible-fingerprint-in-windows/"><u>Troubleshooting No Compatible Fingerprint in Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/a-beginners-primer-to-ps4-gameplay-screenshots-and-streaming/"><u>A Beginner's Primer to PS4 Gameplay Screenshots and Streaming</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-capturing-your-lenovo-display-with-ease/"><u>[New] In 2024, Capturing Your Lenovo Display with Ease</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-from-your-iphone-12-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status From Your iPhone 12</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-captivating-captions-writing-copy-that-drives-engagement-and-views/"><u>[New] In 2024, Captivating Captions  Writing Copy That Drives Engagement and Views</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-unrecognized-disk-issue-a-comprehensive-guide-for-windows-11-users/"><u>Understanding 'Unrecognized Disk' Issue: A Comprehensive Guide for Windows 11 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171243140-chatgpt-now-available-dive-into-these-6-games/"><u>ChatGPT Now Available - Dive Into These 6 Games!</u></a></li>
<li><a href="https://win11.techidaily.com/remove-hyper-v-from-windows-11-setup/"><u>Remove Hyper-V From Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/win-volume-adjustment-reviving-dull-edges/"><u>Win Volume Adjustment: Reviving Dull Edges</u></a></li>
<li><a href="https://win11.techidaily.com/reconfiguring-fn-keys-for-optimal-windows-performance/"><u>Reconfiguring FN Keys for Optimal Windows Performance</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/removing-hitchhiking-devices-win-1011-printer-uninstallation/"><u>Removing Hitchhiking Devices: Win 10/11 Printer Uninstallation</u></a></li>
<li><a href="https://extra-resources.techidaily.com/facebook-video-freeze-up-solutions-for-secure-browser-users/"><u>Facebook Video Freeze-Up Solutions for Secure Browser Users</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-every-second-counts-with-easy-tiktok-grabs/"><u>[Updated] Every Second Counts with Easy TikTok Grabs</u></a></li>
<li><a href="https://win11.techidaily.com/rethinking-upgrades-windows-11s-improvement-focus/"><u>Rethinking Upgrades: Windows 11’S Improvement Focus</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-a-new-pdf-reader-standard-on-os/"><u>Instituting a New PDF Reader Standard on OS</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-day-wins-best-time-management-solutions/"><u>Streamline Your Day: Win's Best Time Management Solutions</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-samsung-galaxy-s23-tactical-editions-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Samsung Galaxy S23 Tactical Editions Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11.techidaily.com/stutter-no-more-essential-9-tips-to-ensure-fluid-video-on-pcs/"><u>Stutter No More: Essential 9 Tips to Ensure Fluid Video on PCs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-on-apple-iphone-11-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide on Apple iPhone 11 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/next-gen-virtual-reality-top-8-metaverse-tech-for-2024/"><u>Next-Gen Virtual Reality  Top 8 Metaverse Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-fast-track-control-windows-taskbar-with-hotkeys/"><u>The Fast Track: Control Windows Taskbar with Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-computing-experience-best-windows-devices-2024/"><u>Ultimate Computing Experience - Best Windows Devices 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-simplified-social-syncing-from-instagram-to-facebook/"><u>[New] Simplified Social Syncing  From Instagram To Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secure-windows-server-settings/"><u>Unlocking Secure Windows Server Settings</u></a></li>
<li><a href="https://win11.techidaily.com/prime-virtually-powered-platforms-for-windows-11-users/"><u>Prime Virtually-Powered Platforms for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/maneuvering-through-typical-anydesk-frustrations-on-windows/"><u>Maneuvering Through Typical AnyDesk Frustrations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcoming-stuck-windows-update-fixer/"><u>Swiftly Overcoming Stuck Windows Update Fixer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-program-compatibility-troubleshooter/"><u>Mastering Windows 11'S Program Compatibility Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/instant-spooler-restart-methods-for-windows/"><u>Instant Spooler Restart Methods for Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-shutdown-of-windows-privacy-tools/"><u>Navigating the Shutdown of Windows Privacy Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-remote-display-issue-darkened-screen/"><u>Resolving Windows Remote Display Issue: Darkened Screen</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-stabilize-windows-configuration-app/"><u>Quick Fixes to Stabilize Windows Configuration App</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-oppo-find-x6-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Oppo Find X6 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-depth-guide-to-live-photos-and-full-screen-videos-on-iphones/"><u>In 2024, In-Depth Guide to Live Photos and Full-Screen Videos on iPhones</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-improve-your-virtual-engagement-mastering-snap-photography/"><u>[Updated] Improve Your Virtual Engagement  Mastering Snap Photography</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/social-network-power-play-understanding-igtv-vs-youtubes-dynamics/"><u>Social Network Power Play  Understanding IGTV Vs. YouTube's Dynamics</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-top-5-tunefab-screen-recording-tips-and-tricks/"><u>[New] In 2024, Top 5 Tunefab Screen Recording Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-panel-settings/"><u>Unlock Full Control of Windows Panel Settings</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-system-backups-to-standard-configurations/"><u>Reverting System Backups to Standard Configurations</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-direct-live-broadcasting-obs-to-instagram/"><u>2024 Approved  Direct Live Broadcasting  OBS to Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-advanced-tools-for-improved-admin-workflows-in-windows/"><u>Leveraging Advanced Tools for Improved Admin Workflows in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-oneplus-nord-ce-3-lite-5g-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My OnePlus Nord CE 3 Lite 5G Wont Charge | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-lava-storm-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Lava Storm 5G phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-transfer-in-google-chrome-now-easier-on-windows/"><u>Mastering File Transfer in Google Chrome, Now Easier on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-rdp-connection-issues-in-modern-oses/"><u>Unblocking RDP Connection Issues in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-error-0x80073d26/"><u>Unraveling the Mystery of Windows' Error 0X80073D26</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-discovering-the-premium-free-plugins-the-top-10-list-sound-engineers-for-2024/"><u>New Discovering the Premium Free Plugins The Top 10 List Sound Engineers for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-oppo-reno-9a-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Oppo Reno 9A Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-definitive-guide-to-crafting-videos-on-youtube/"><u>2024 Approved  The Definitive Guide to Crafting Videos on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-silencing-windows-11-operations/"><u>Ultimate Guide: Silencing Windows 11 Operations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wsreset-troubleshooting-in-windows-environments/"><u>Mastering WSReset Troubleshooting in Windows Environments</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-complete-curve-editing-manual-for-photoshop/"><u>The Complete Curve Editing Manual for Photoshop</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-realme-gt-5-pro-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Realme GT 5 Pro to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-harmonizing-your-browsing-experience-with-automatic-youtube-playback-on-facebook-for-2024/"><u>[Updated] Harmonizing Your Browsing Experience with Automatic YouTube Playback on Facebook for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-augmented-reality-on-android-a-step-towards-future-viewing/"><u>2024 Approved  Augmented Reality on Android - A Step Towards Future Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-11s-search-bar-unseen/"><u>How to Keep Windows 11'S Search Bar Unseen</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-creating-compelling-thumbnails-that-stand-out/"><u>2024 Approved  Creating Compelling Thumbnails that Stand Out</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-disable-microsoft-edge-tab-preloading-in-windows-11/"><u>4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-for-temporary-profiles-on-windows/"><u>Innovative Approaches for Temporary Profiles on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-captureitease-2023s-best-screen-recording-tools/"><u>[Updated] In 2024, CaptureItEase  2023'S Best Screen Recording Tools</u></a></li>
<li><a href="https://win11.techidaily.com/sound-superchargers-4-applications-boosting-windows-audio-capacity/"><u>Sound Superchargers: 4 Applications Boosting Windows' Audio Capacity</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-tecno-camon-30-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-foodiehits-leading-tiktok-food-bloggers-for-2024/"><u>[Updated] FoodieHits  Leading TikTok Food Bloggers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-clutter-windows-generative-erasure/"><u>Say Goodbye to Clutter: Windows' Generative Erasure</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-routes-for-customizing-windows-11-settings-app/"><u>Reboot Routes for Customizing Windows 11 Settings App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-error-troubleshooting-e84-edition/"><u>Mastering Steam Error Troubleshooting: E84 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functionality-in-windows-voice-only-bluetooth-speaker/"><u>Restoring Full Functionality in Windows: Voice-Only Bluetooth Speaker</u></a></li>
</ul></div>

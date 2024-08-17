---
title: "Step-by-Step: Telnet Enablement in Win11"
date: 2024-08-16T00:03:12.485Z
updated: 2024-08-17T00:03:12.485Z
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
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
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->

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
<li><a href="https://digital-screen-recording.techidaily.com/new-fixing-blank-sequences-during-obs-recording-for-2024/"><u>[New] Fixing Blank Sequences During OBS Recording for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-proven-practice-for-preserving-playthroughs-tips-and-tricks-for-recording-roblox-gameplay-on-a-mac/"><u>[New] In 2024, Proven Practice for Preserving Playthroughs  Tips & Tricks for Recording Roblox Gameplay on a Mac</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lens-legends-top-six-selecting-high-quality-4k-dslrs/"><u>[New] Lens Legends' Top Six  Selecting High-Quality 4K DSLRs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-optimizing-team-calls-prepost-meeting-screen-customization/"><u>[New] Optimizing Team Calls  Pre/Post-Meeting Screen Customization</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-quickfacebookvidextractor-pro/"><u>[Updated] 2024 Approved  QuickFacebookVidExtractor Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-a-comprehensive-guide-to-business-on-snapchat/"><u>[Updated] A Comprehensive Guide to Business on Snapchat</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-premiere-pro-speed-blackouts/"><u>2024 Approved  Premiere Pro Speed Blackouts</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-lava-blaze-2-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Lava Blaze 2? Fix Now | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-infinix-smart-8-hd-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advance-your-task-management-with-windows-flow-launcher/"><u>Advance Your Task Management with Windows' Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-victory-in-original-diablo/"><u>Beginner’s Blueprint to Victory in Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/boost-safety-measures-include-trusted-sites-on-windows-11/"><u>Boost Safety Measures: Include Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-performance-with-smart-use-of-windows-11s-bar/"><u>Boosted Performance with Smart Use of Windows 11'S Bar</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-security-account-manager-failures/"><u>Combatting Security Account Manager Failures</u></a></li>
<li><a href="https://extra-information.techidaily.com/decoding-quantum-hdr-for-creative-success/"><u>Decoding Quantum HDR for Creative Success</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-wsl-error-4294967295-a-comprehensive-guide/"><u>Eliminating WSL Error 4294967295: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-linking-win-prefixes-and-ms-logins/"><u>Enhancing User Experience: Linking Win Prefixes & MS Logins</u></a></li>
<li><a href="https://win11.techidaily.com/explore-versatility-the-best-10-uses-for-windows-powertoys-tools/"><u>Explore Versatility: The Best 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://win11.techidaily.com/extracting-tabbed-files-windows-11-quick-guide/"><u>Extracting Tabbed Files: Windows 11 Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fix-cluttered-desktop-with-removal-of-win11s-focus-icons/"><u>Fix Cluttered Desktop with Removal of Win11's Focus Icons</u></a></li>
<li><a href="https://win11.techidaily.com/1719265267578-fixing-winsplit-display-issues-now/"><u>Fixing WinSplit Display Issues Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-hp-z440-workstation-graphics-card-drivers-free-downloads-available-now/"><u>Get the Newest HP Z440 Workstation Graphics Card Drivers – Free Downloads Available Now!</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-embedding-google-play-into-windows-11/"><u>Guide to Embedding Google Play Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/holiday-harmony-delightful-wrapped-apps-through-ms-store/"><u>Holiday Harmony: Delightful Wrapped Apps Through MS Store</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-monitor-1-and-2-in-windows/"><u>How to Change Monitor 1 and 2 in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-samsung-galaxy-xcover-7-lock-screen-password-by-drfone-android/"><u>How To Change Samsung Galaxy XCover 7 Lock Screen Password?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-10-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-install-the-latest-ios-beta-version-on-iphone-6s-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-magic-5-lite-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor Magic 5 Lite to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/linking-legacy-and-modernity-initiating-windows-11-with-a-window-7-code/"><u>Linking Legacy and Modernity: Initiating Windows 11 with a Window 7 Code</u></a></li>
<li><a href="https://win11.techidaily.com/1719361152872-lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever!</u></a></li>
<li><a href="https://win11.techidaily.com/making-vintage-windows-computers-more-elderly-friendly/"><u>Making Vintage Windows Computers More Elderly Friendly</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-key-features-and-uses/"><u>Microsoft Family Safety: Key Features and Uses</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-gpu-capabilities-the-6-best-testers-in-windows/"><u>Navigate Through GPU Capabilities: The 6 Best Testers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/real-time-viewing-capturing-every-moment-of-the-2024-athens-games-online/"><u>Real-Time Viewing: Capturing Every Moment of the 2024 Athens Games Online</u></a></li>
<li><a href="https://win11.techidaily.com/revive-typical-windows-explore-view-configuration/"><u>Revive Typical Windows Explore View Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-photo-viewer-a-step-by-step-guide-for-11-users/"><u>Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamlining-360-degree-video-editing-workflow-in-premiere-pro-for-2024/"><u>Streamlining 360-Degree Video Editing Workflow in Premiere Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swift-pc-exploration-via-everythingapp/"><u>Swift PC Exploration via EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-high-cpu-usage-in-setups/"><u>Taming the Beast: High CPU Usage in Setups</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-avoiding-mistakes-in-windows-11/"><u>The Beginner's Guide to Avoiding Mistakes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-version-numbering-in-windows/"><u>The Essence of Version Numbering in Windows</u></a></li>
<li><a href="https://buynow-help.techidaily.com/uncovering-the-secrets-behind-uniden-rs-sturdy-build-and-remarkable-range-functionality/"><u>Uncovering the Secrets Behind Uniden Rˈs Sturdy Build and Remarkable Range Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-digital-gateway-easy-desktop-connectivity-with-win-11/"><u>Unlocking the Digital Gateway: Easy Desktop Connectivity with Win 11</u></a></li>
</ul></div>

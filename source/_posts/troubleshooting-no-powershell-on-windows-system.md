---
title: "Troubleshooting: No PowerShell on Windows System"
date: 2024-07-13T10:48:57.458Z
updated: 2024-07-14T10:48:57.458Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: No PowerShell on Windows System"
excerpt: "This Article Describes Troubleshooting: No PowerShell on Windows System"
keywords: PowerShell Zero Start,Windows No PS,Troubleshoot PowerShell,PC Without PowerShell,Fix No PS Windows,Boot Issue PowerShell,System Non-PS Operational
thumbnail: https://thmb.techidaily.com/33139754522d3393b0a998cc016bffa1b55254150a3f5abcd672e5d0c2f8e9f3.jpg
---

## Troubleshooting: No PowerShell on Windows System

 PowerShell is a handy tool that lets you automate tasks, troubleshoot various errors, and manage a variety of Windows settings. But what if it suddenly goes missing from your computer?

 If you use PowerShell frequently, it can be aggravating when Windows cannot find it. Thankfully, it’s possible to restore the missing PowerShell with a few troubleshooting tips. In this post, we'll walk you through all of them.

## 1\. Make Sure Windows PowerShell Is Enabled

 On Windows, you can enable or disable optional features and programs from the Control Panel. To start, you need to ensure that PowerShell isn’t disabled on your computer. Here’s how to check.

1. Press**Win + R** to open the Run dialog.
2. Type**control** in the box and press**Enter** to open Control Panel.
3. Click the drop-down menu in the top right corner to select**Large icons** .
4. Go to**Programs and Features** .
5. Click the**Turn Windows features on or off** link from the left pane.
6. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
7. In the Windows Features dialog, locate**Windows PowerShell** and select its checkbox.
8. Click**OK** to save the changes.  
![Enable PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-PowerShell-on-Windows.jpg)

 Restart your computer after this (see [how to restart a Windows computer](https://www.makeuseof.com/windows-restart-methods/) ) and then try to launch PowerShell using the search menu.

## 2\. Launch PowerShell Using Run Command or File Explorer

 If you are unable to open PowerShell via the search menu, you can try using the Run dialog box. Press**Win + R** to open the Run dialog. Type**powershell** in the box and press**Enter** . If you want to launch PowerShell with admin rights, press**Ctrl + Shift + Enter** instead.

![Open PowerShell via Run Command on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Open-PowerShell-via-Run-Command-on-Windows.jpg)

 You can also open PowerShell from the File Explorer address bar. To do so, press**Win + E** to open File Explorer. Type**PowerShell** in the address bar and press**Enter** .

## 3\. Create a Desktop Shortcut for PowerShell

 Windows may fail to open PowerShell if it does not know the exact file path to the PowerShell executable file. If that’s the case, you can manually locate the PowerShell executable file on your computer and create a desktop shortcut for it. Here are the steps for doing the same.

1. Right-click on the**Start icon** to open the Power User menu and select**File Explorer** from the list.
2. Navigate to**This PC** .
3. Head over to**C: > Windows > SysWOW64** and locate**WindowsPowerShell** folder.
4. Open the WindowsPowerShell folder and go to the**v1.0** folder.
5. Double-click on the PowerShell executable file and see if it works. If it does, right-click on it and select**Send to > Desktop (create shortcut)** .  
![Create Desktop Shortcut for PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-for-PowerShell-on-Windows.jpg)

 You can then use the newly created desktop shortcut to launch PowerShell. For added convenience, you can assign a keyboard shortcut to PowerShell. To learn more about this, check our guide on [how to assign keyboard shortcuts to programs in Windows](https://www.makeuseof.com/windows-keyboard-shortcuts-programs/) .

## 4\. Scan Your Computer for Corrupted System Files

 Damaged or corrupted system files can also interfere with Windows operations and prevent PowerShell from launching. Fortunately, your Windows PC comes with a few built-in tools, such as SFC (System File Checker) and DISM (or Deployment Image Servicing and Management) that can help you with such issues. If Windows suffers from system file corruption, running these tools will fix the problem.

To run the SFC scan on Windows:

1. Click the magnifying glass icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** in the search box and select**Run as administrator** from the right panel.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type**SFC /scannow** in the console and press**Enter** .

 The SFC scan will start verifying the integrity of your system files and fix any issues with them. The scan might take a while, so be patient.

 Next, you need to run the DISM scan. This is another diagnostic tool that Windows offers. It can automatically detect any issues with the system image and fix them. If you want to learn more about them, check out our guide on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 To run DISM,[open Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) again. Paste the following command in the console and press**Enter** .

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/DISM-Scan-Windows.jpg)

 Wait for the command to execute successfully, and then restart your PC. Following that, see if Windows can find PowerShell on your computer.

## 5\. Update Windows PowerShell

 If Windows still can't find PowerShell at this point, there could be a problem with the PowerShell app itself. You can try updating the PowerShell app to see if that makes any difference.

To update PowerShell on Windows:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. When the User Account Control (UAC) prompt shows up, select**Yes** .
4. Type the following command and press**Enter** .  
`winget install --id Microsoft.Powershell --source winget`  
![Update PowerShell on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-PowerShell-on-Windows.jpg)

 Windows will download and install the most recent version of PowerShell. Following that, you should be able to access PowerShell.

 Using Command Prompt isn't the only way to update PowerShell on Windows. If you want to learn other methods, check our guide on [how to install or update PowerShell on Windows](https://www.makeuseof.com/windows-11-powershell-install-update/) .

## 6\. Create a New User Account

 It's possible that the PowerShell not opening problem is limited to your current user account. In that case, you can create and switch to a new user account and see if that works.

To create a new user account on Windows, use these steps.

1. Open the start menu and click the**gear icon** to open the Settings app.
2. Navigate to**Accounts** .
3. Select**Other users** .
4. Click the**Add account** button.
5. Click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign-In](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Microsoft-Account-Sign-In.jpg)

 Sign in with your newly created account, and see if Windows can find PowerShell now.

## Access Windows PowerShell Again

 Hopefully, one of the above fixes has proven useful, and you're able to access PowerShell once again. If not, you may have to consider resetting your Windows computer as a last resort.

 PowerShell isn't the only command-line tool available on Windows. You can also use the Command Prompt to communicate with your system.


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
<li><a href="https://win11.techidaily.com/create-a-distinctive-color-scheme-in-wt-terminal/"><u>Create a Distinctive Color Scheme in WT Terminal</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-navigating-the-zoom-interface-like-a-pro-in-win11/"><u>In 2024, Navigating the Zoom Interface Like a Pro in Win11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-metaverse-marvels-top-10-sci-fi-films-unveiling-extraordinary-worlds/"><u>[New] Metaverse Marvels  Top 10 Sci-Fi Films Unveiling Extraordinary Worlds</u></a></li>
<li><a href="https://win11.techidaily.com/transition-windows-calculator-to-dark-mode/"><u>Transition Windows Calculator to Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-cab-files-explanations-and-steps-for-installation/"><u>Understanding Windows Cab Files: Explanations & Steps for Installation</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-evaluating-acid-pro-open-source-rivals-explored-for-2024/"><u>[New] Evaluating ACID Pro  Open-Source Rivals Explored for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-foremost-set-of-3-virtual-mp3-sound-increaser-utilities/"><u>The Foremost Set of 3 Virtual MP3 Sound Increaser Utilities</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-thousands-already-found-15-best-sites-to-watch-cartoons-online-free-and-so-can-you/"><u>New Thousands Already Found 15 Best Sites to Watch Cartoons Online Free And So Can You</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-buy-youtube-likes-does-it-really-help-boost-your-channel/"><u>In 2024, Buy YouTube Likes? Does It Really Help Boost Your Channel?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/customizing-facebook-memories-with-look-back-edits-for-2024/"><u>Customizing Facebook Memories with Look Back Edits for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-the-great-video-editor-debate-sony-vegas-vs-adobe-premiere-pro-2023-comparison/"><u>New 2024 Approved The Great Video Editor Debate Sony Vegas vs Adobe Premiere Pro 2023 Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-dormant-pane-windows-6-tips-for-win11-users/"><u>Triggering Dormant Pane Windows: 6 Tips for Win11 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-by-step-approach-to-boosting-typing-on-a-steam-deck/"><u>A Step-by-Step Approach to Boosting Typing on a Steam Deck</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-realme-c67-5g-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Realme C67 5G</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-the-critical-windows-c0000022-bug/"><u>Confronting the Critical Windows C0000022 Bug</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-samsung-galaxy-a14-4g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Samsung Galaxy A14 4G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-app-management-on-windows-11-os/"><u>Speedy App Management on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-on-end-task-feature-in-windows-11-ui/"><u>Steps to Turn On End Task Feature in Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-files-and-directories-in-modern-windows/"><u>Aligning Files & Directories in Modern Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-motorola-defy-2-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Motorola Defy 2 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-risks-of-using-cheap-windows-activation-keys/"><u>6 Risks of Using Cheap Windows Activation Keys</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-cortana-commands-in-windows-11/"><u>Troubleshooting Non-Functional Cortana Commands in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-potential-your-custom-hotkey-journey/"><u>Unlocking Windows Potential: Your Custom Hotkey Journey</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-app-migration-from-older-windows-versions/"><u>Unveiling the Art of App Migration From Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/4-early-stages-of-pc-failure-know-when-to-act/"><u>4 Early Stages of PC Failure, Know When To Act</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-whatsapp-video-integration-for-twitter-content/"><u>[Updated] In 2024, WhatsApp Video Integration for Twitter Content</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-missing-tab-button-on-your-machine/"><u>Unveiling the Missing Tab Button on Your Machine</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-mysteries-a-guide-to-finding-and-fixing-error-messages-using-commands/"><u>Unraveling Windows Mysteries: A Guide to Finding and Fixing Error Messages Using Commands</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-lava-blaze-2-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Lava Blaze 2 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/swift-disconnection-methods-non-operational-printer-removal/"><u>Swift Disconnection Methods: Non-Operational Printer Removal</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-of-pcs-integrating-enhanced-run-utility-for-windows/"><u>Unleash Potential of PCs: Integrating Enhanced Run Utility for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-pin-verification-errors-on-w11w10-systems/"><u>Solutions for Fixing PIN Verification Errors on W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-update-error-0x8024800c/"><u>Solutions for Windows Update Error 0X8024800C</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Motorola Edge+ (2023)? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-alternatives-round-up-top-3-contenders/"><u>In 2024, YouTube Alternatives Round-Up  Top 3 Contenders</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-display-selecting-premium-timers-and-savers/"><u>Upgrade Your Display: Selecting Premium Timers & Savers</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-task-juggling-skills-a-guide-to-mastering-windows-11-multitasking/"><u>Step Up Your Task Juggling Skills: A Guide to Mastering Windows 11 Multitasking</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-error-code-0x000-on-your-windows-11-devices-xbox-game-pass/"><u>Swiftly Resolving Error Code 0X000_ on Your Windows 11 Devices' Xbox Game Pass</u></a></li>
</ul></div>

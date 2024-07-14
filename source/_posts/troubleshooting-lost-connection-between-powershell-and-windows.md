---
title: "Troubleshooting: Lost Connection Between PowerShell and Windows"
date: 2024-07-13T10:42:05.648Z
updated: 2024-07-14T10:42:05.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Lost Connection Between PowerShell and Windows"
excerpt: "This Article Describes Troubleshooting: Lost Connection Between PowerShell and Windows"
keywords: PowerShell Connect Issue,WinXPsyConnectivity,FixPowerShellLink,RestorePSWindowsLink,RecoverPSConnection,ResolveWinPSLoss,ReestablishPSLinkage
thumbnail: https://thmb.techidaily.com/6ab11e94b8a02777808e732d5f2080be3cb5bc04d41c7f6aa8db8cb93929f141.jpg
---

## Troubleshooting: Lost Connection Between PowerShell and Windows

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
<li><a href="https://win11.techidaily.com/access-and-conquer-mastering-windows-11-printer-control-max-50-chars/"><u>Access and Conquer: Mastering Windows 11 Printer Control (Max 50 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-creativity-discovering-the-latest-in-microsoft-paint/"><u>Elevate Creativity: Discovering the Latest in Microsoft Paint</u></a></li>
<li><a href="https://win11.techidaily.com/repair-restore-function-keys-in-windows-11/"><u>Repair: Restore Function Keys in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-sifting-through-mr-beasts-bank-statements/"><u>In 2024, Sifting Through Mr. Beast's Bank Statements</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-the-ultimate-checklist-how-to-choose-a-video-to-audio-converter-that-works/"><u>2024 Approved The Ultimate Checklist How to Choose a Video to Audio Converter That Works</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-capture-quality-in-nintendo-switch-life-for-2024/"><u>[New] Capture Quality in Nintendo Switch Life for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-integrating-end-screen-elements-with-vimeo/"><u>2024 Approved  Integrating End Screen Elements with Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-lost-windows-secrets-for-restoring-hidden-panes-on-win-1011-with-ease/"><u>Reclaim Your Lost Windows! Secrets for Restoring Hidden Panes on Win 10/11 with Ease</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-itel-p55t-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Itel P55T Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11.techidaily.com/instant-spooler-restart-methods-for-windows/"><u>Instant Spooler Restart Methods for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-down-your-laptop-keyboard-with-simple-steps-in-win10win11/"><u>Quiet Down Your Laptop Keyboard with Simple Steps in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-code-0x0001-glitches-in-ge-and-windows-os/"><u>Strategies to Address Code 0X0001 Glitches in GE & Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-open-exes-without-issues/"><u>Troubleshooting Windows: Open EXEs Without Issues</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-search-failures-immediately/"><u>Addressing Windows 11 Search Failures Immediately</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevate-your-marketing-game-free-50-youtube-adornments-here/"><u>2024 Approved  Elevate Your Marketing Game - Free 50 YouTube Adornments Here</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-code-0x80d03801-in-microsoft-store-on-windows-pc/"><u>How to Fix Error Code 0X80d03801 in Microsoft Store on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-enabling-additional-av-software-on-windows/"><u>Techniques for Enabling Additional AV Software on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/get-across-taskbar-and-tile-adjustments-fast/"><u>Get Across Taskbar & Tile Adjustments Fast</u></a></li>
<li><a href="https://win11.techidaily.com/reel-in-efficiency-with-these-premium-video-editors-on-window-11/"><u>Reel-In Efficiency with These Premium Video Editors on Window 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-video-editing-mastery-a-beginners-guide-to-online-download-and-editing/"><u>New 2024 Approved Video Editing Mastery A Beginners Guide to Online Download and Editing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-could-not-create-the-java-virtual-machine-error-on-windows/"><u>How to Fix the “Could Not Create the Java Virtual Machine” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-for-temporary-profiles-on-windows/"><u>Innovative Approaches for Temporary Profiles on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-channel-to-checkbook-conversion-the-path-from-adsense-to-banking/"><u>[Updated] In 2024, Channel to Checkbook Conversion  The Path From AdSense to Banking</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-11s-search-bar-unseen/"><u>How to Keep Windows 11'S Search Bar Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-mute-reactivate-slack-alerts-in-win-11/"><u>Troubleshoot Mute: Reactivate Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-disconnect-error-for-malwarebytes-services-in-windows-11/"><u>Remedying Disconnect Error for Malwarebytes Services in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-your-windows-backup-preferences/"><u>Resetting Your Windows Backup Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/direct-pc-access-through-smb-protocols-mobile/"><u>Direct PC Access Through SMB Protocols (Mobile)</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-dxgidll-quick-fixes-for-the-missing-file/"><u>Win11 & Dxgi.dll: Quick Fixes for the Missing File</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-pc-finder-power-with-everythingapp/"><u>Supercharge PC Finder Power with EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-nullifying-windows-tracking-mechanism/"><u>Techniques for Nullifying Windows' Tracking Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screen-interaction-proficient-use-of-windows-narrator-shortcuts/"><u>Streamlined Screen Interaction: Proficient Use of Windows Narrator Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-best-free-4k-video-editors-you-should-try/"><u>Updated In 2024, Best Free 4K Video Editors You Should Try</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-file-lifecycle-in-windows-11-set-up-autodelete-protocols/"><u>Efficient File Lifecycle in Windows 11: Set Up Autodelete Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-media-player-server-crashes/"><u>Remedying Media Player Server Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-for-effective-app-packages-control-using-winget-on-win11/"><u>Top Tips for Effective App Packages Control Using Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reconnecting-windows-remotes-resolving-unacceptable-links/"><u>Reconnecting Windows Remotes: Resolving Unacceptable Links</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-seamless-link-for-windows-steam-streaming/"><u>Restoring Seamless Link for Windows Steam Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://extra-information.techidaily.com/future-filming-top-15-video-cameras-to-watch/"><u>Future Filming – Top 15 Video Cameras to Watch</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-series-pros-and-cons/"><u>Deciphering Windows N Series: Pros & Cons</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-pinnacle-of-plotting-the-worlds-best-8-schools-for-writers/"><u>[Updated] Pinnacle of Plotting  The World's Best 8 Schools for Writers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/comprehensive-insights-into-polarrs-photo-tools/"><u>Comprehensive Insights Into Polarr's Photo Tools</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-access-post-error-code-22-fixing-a-locked-down-pc-in-windows-11/"><u>Restoring Access Post-Error Code 22: Fixing a Locked Down PC in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-conversations-testing-microphones-and-cameras-in-windows/"><u>Smooth Conversations: Testing Microphones & Cameras in Windows</u></a></li>
</ul></div>

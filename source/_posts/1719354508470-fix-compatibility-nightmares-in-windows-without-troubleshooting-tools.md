---
title: Fix Compatibility Nightmares in Windows without Troubleshooting Tools.
date: 2024-07-13T09:47:53.707Z
updated: 2024-07-14T09:47:53.707Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Compatibility Nightmares in Windows without Troubleshooting Tools.
excerpt: This Article Describes Fix Compatibility Nightmares in Windows without Troubleshooting Tools.
keywords: Win-Compat Fix,No Tool Troubles,Windows Fix Issues,Bypass CompTools,Nightmare FreeWin,Easy WinFix,AvoidCompTooling
thumbnail: https://thmb.techidaily.com/f78a12d6fa260b60593d7d84df0572fbc03e543ca8c86ab396fe09af56299ebf.jpg
---

## Fix Compatibility Nightmares in Windows without Troubleshooting Tools

 The Program Compatibility Troubleshooter is a tool from Microsoft that checks for and resolves compatibility issues when running older applications on newer versions of Windows. However, sometimes the troubleshooter fails to work as expected.

 If you're facing this issue, there are several possible causes and ways to fix it. Let's look into them below.

## 1\. Check For Corrupted System Files

 Corrupted system files can cause the Program Compatibility Troubleshooter not to work correctly. To ensure all your system files are functioning properly, run the built-in System File Checker utility on Windows. Here's how to do it:

1. Right-click on**Start** and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC appears on the screen, click**Yes** to grant privileges.  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In Command Prompt type the below command and hit Enter:  
`sfc /scannow`

 Wait for the scan to finish. This may take several minutes and your PC may restart once or twice during the process. Once the scan is completed, check if the Program Compatibility Troubleshooter works now.

## 2\. Repair Corrupted System Image

 If the System File Checker was unable to repair corrupt system files, you can use the DISM tool from Command Prompt to fix them. Here's how to do it:

1. Use one of the many [ways to run Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) to get an elevated prompt running.  
![Run DISM Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-dism-command.jpg)
2. In Command Prompt, type the below command and hit**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

 The DISM tool will start scanning the system for corruption. It can take up to 20 minutes, but it is worth waiting because it can repair a lot of system issues. Once the scan is completed, restart your computer and check if the issue is fixed.

## 3\. Uninstall Third-Party Security Software

 Sometimes, certain third-party security software can interfere with the Program Compatibility Troubleshooter and cause it to not work. Uninstalling these programs should help.

1. Right-click on Start and select**Installed apps** .
2. Search for your security software in the list of installed programs.
3. Then click the three dots and select**Uninstall** .

 Follow the on-screen instructions to remove the program from your PC. Once done, restart your PC and try running the Program Compatibility Troubleshooter again.

## 4\. Restart the Diagnostic Policy Service

 The Diagnostic Policy Service is responsible for allowing the Program Compatibility Troubleshooter to work properly. If it's not running, restarting it should help the troubleshooter function normally.

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**services.msc** in the text box and click**OK** .
3. Look for the**Diagnostic Policy Service** and double-click it.  
![Restart Diagnostic Policy Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-diagnostic-policy-service.jpg)
4. In the Diagnostic Policy Service Properties window, set the Startup type to**Automatic** and click**Start** .
5. Next, click**Apply** and**OK** to save the changes.

 Now restart your PC and try running the Program Compatibility Troubleshooter again to see if it works.

## 5\. Run the Troubleshooter in Safe Mode

 If you are still experiencing this issue, try running the Program Compatibility Troubleshooter in safe mode. This will help you troubleshoot any compatibility issues more effectively.

To do this, follow the below steps:

1. Start your PC in safe mode (see [how to start Windows in safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) for instructions).
2. Once in safe mode,[run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) and check if it works. If so, it means that one of your installed programs is causing the issue. Try uninstalling them and see if the issue is fixed.

## 6\. Reset Windows

 If all else fails, you can try [resetting Windows to its default settings](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will reinstall Windows and get rid of any potential issues that may be causing the troubleshooter to not work.

## Fixing Program Compatibility Troubleshooter Problems on Windows

 If the Program Compatibility Troubleshooter is not working on your computer, read this guide. The steps here will help you fix this issue and have the tool working and running again.


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
<li><a href="https://win11.techidaily.com/step-by-step-to-delete-onedrive-icon-in-windows-explore/"><u>Step-by-Step to Delete OneDrive Icon in Windows Explore</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hear-the-difference-change-your-playstation-sound/"><u>In 2024, Hear the Difference  Change Your PlayStation Sound</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-powershell-security-controls/"><u>The Ultimate Guide to PowerShell Security Controls</u></a></li>
<li><a href="https://howto.techidaily.com/my-videos-arent-playing-on-nokia-105-classic-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Nokia 105 Classic – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-top-15-best-screenshot-software-windows-and-mac/"><u>[New] In 2024, Top 15 Best Screenshot Software [Windows & Mac]</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-seamless-warhammer-gaming-on-windows-stop-stuttering/"><u>Achieving Seamless Warhammer Gaming on Windows: Stop Stuttering</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-fixed-gif-sizes-in-discord-for-windows-11-users/"><u>Unraveling the Mystery of Fixed GIF Sizes in Discord (for Windows 11 Users)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-secrets-to-preventing-photo-app-problems-in-windows-11/"><u>2024 Approved  Secrets to Preventing Photo App Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/must-know-factors-a-consumers-checklist-for-buying-a-win-laptop/"><u>Must-Know Factors: A Consumer's Checklist for Buying a Win Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-connectivity-problems-with-fall-guys-on-pc/"><u>Resolving Connectivity Problems with Fall Guys on PC</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-aggregatorhostexe-functions-and-safe-practices/"><u>Understanding Windows' AggregatorHost.exe: Functions & Safe Practices</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-for-windows-11s-slow-poke-problem/"><u>Quick Cure for Windows 11'S Slow Poke Problem</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-seizing-photographic-segments-from-videos-in-windows-11/"><u>In 2024, Seizing Photographic Segments From Videos in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-many-viewers-equates-to-profit-decoding-youtubes-earnings-formula/"><u>[New] How Many Viewers Equates to Profit? Decoding YouTube's Earnings Formula</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-to-safety-entering-windows-11-safe-mode-easily/"><u>Stepwise to Safety: Entering Windows 11 Safe Mode Easily</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-tutorial-to-edit-windows-files-metadata-dates/"><u>The Complete Tutorial to Edit Windows Files' Metadata Dates</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolving-white-paper-output-on-hp-printer/"><u>Resolving White Paper Output on HP Printer</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-maximizing-user-experience-for-live-streams-on-discord-platform/"><u>[Updated] 2024 Approved  Maximizing User Experience for Live Streams on Discord Platform</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-xiaomi-civi-3-frp-by-drfone-android/"><u>Full Guide to Bypass Xiaomi Civi 3 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-nirvana-mastering-visual-organization-in-obsidian/"><u>Notetaking Nirvana: Mastering Visual Organization in Obsidian</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-highlight-settings-in-windows-11/"><u>Navigating Highlight Settings in Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unleash-photos-on-instagram-with-ease-follow-this-guide-for-2024/"><u>[New] Unleash Photos on Instagram with Ease – Follow This Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-telnet-activation-on-modern-windows/"><u>Quick Guide to Telnet Activation on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/renewing-lockout-count-post-failed-sign-ins-in-w10w11/"><u>Renewing Lockout Count Post-Failed Sign-Ins in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/surges-subdued-mastering-the-art-of-cpu-management-in-rm/"><u>Surges Subdued: Mastering the Art of CPU Management in RM</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-easy-customization-free-youtube-visual-templates-for-2024/"><u>[Updated] Easy Customization  Free YouTube Visual Templates for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-breaking-through-boundaries-with-hdr-in-editing/"><u>2024 Approved  Breaking Through Boundaries with HDR in Editing</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ero-cost-youtube-meetings-easy-to-host/"><u>[New] Zero Cost Youtube Meetings  Easy to Host</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-path-not-found-in-windows-os/"><u>Troubleshooting PATH Not Found in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-pc-graphics-with-optimal-vram-settings/"><u>Transform Your PC Graphics with Optimal VRAM Settings</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-focus-on-the-main-sound-in-video-capturing-free-advice-for-2024/"><u>[New] Focus on the Main Sound in Video Capturing (Free Advice) for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-revisiting-video-broadcast-choices-post-wirecast/"><u>[Updated] Revisiting Video Broadcast Choices Post-Wirecast</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-win11-terminal-back-to-basics/"><u>Reverting Win11 Terminal Back to Basics</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-crafting-an-engaging-tiktok-closing-credits/"><u>[New] 2024 Approved  Crafting An Engaging TikTok Closing Credits</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-getting-started-with-mac-video-editing-tips-for-choosing-the-best-software/"><u>New 2024 Approved Getting Started with Mac Video Editing Tips for Choosing the Best Software</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-samsung-galaxy-a15-4g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Samsung Galaxy A15 4G Phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-sticky-note-access/"><u>Unlocking Windows 11 Sticky Note Access</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-get-creative-with-these-free-video-effect-apps-for-mobile-for-2024/"><u>New Get Creative with These Free Video Effect Apps for Mobile for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-inverted-text-input-windows-wise/"><u>Strategies for Fixing Inverted Text Input Windows-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-wasteful-usage-by-core-system-processes/"><u>Reducing Wasteful Usage by Core System Processes</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-guide-to-uninstall-printers-from-win11/"><u>Strategic Guide to Uninstall Printers From Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-lost-default-windows-11-power-settings/"><u>Reinstating Lost Default Windows 11 Power Settings</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-rpc-failures-with-ease/"><u>Troubleshooting Windows RPC Failures with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-safest-free-software-download-sites-for-windows/"><u>The 10 Safest Free Software Download Sites for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-clear-signals-its-time-for-windows-reset/"><u>5 Clear Signals It's Time for Windows Reset</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-advanced-techniques-for-audio-detachment-in-newly-updated-mkv-files-mkv-2023/"><u>New In 2024, Advanced Techniques for Audio Detachment in Newly Updated MKV Files (MKV-2023)</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-dns-on-windows-11/"><u>Step-by-Step: Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-novice-to-experienced-6-strategies-for-quick-verification-on-instagram-for-2024/"><u>[Updated] From Novice to Experienced  6 Strategies for Quick Verification on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/best-in-class-window-videomodding-tools-our-top-picks/"><u>Best-in-Class Window Videomodding Tools: Our Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-java-installer-problems-on-a-windows-pc/"><u>Remedying Java Installer Problems on a Windows PC</u></a></li>
</ul></div>

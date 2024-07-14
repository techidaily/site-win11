---
title: "Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers"
date: 2024-07-13T10:27:57.946Z
updated: 2024-07-14T10:27:57.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers"
excerpt: "This Article Describes Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers"
keywords: Disable Windows Restrictions,Remove Signature Blocks,Enable Unsigned Driver Installation,Bypass Windows Security,Add Unapproved Software,Deactivate System Protection,Ignore File Validation
thumbnail: https://thmb.techidaily.com/efc3f590fc068b65cc8e4c4fda82884c66683db0be7b320fd391a90a34b6fb91.jpg
---

## Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/power-tools-for-pc-mastery-command-prompt-edition-of-win-registry-edits/"><u>Power Tools for PC Mastery: Command Prompt Edition of Win Registry Edits</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-watch-hulu-outside-us-on-oneplus-12-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-volume-adjustment-issues-in-windows-os/"><u>Mastering Volume Adjustment Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-error-code-0x8000fffd-on-pcs/"><u>Mastering Fixes for Error Code 0X8000FFFD on PCs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-plex-vs-studio-prodigies-for-2024/"><u>[New] Plex vs Studio Prodigies for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-10-most-affordable-cloud-vendors-listed/"><u>Top 10 Most Affordable Cloud Vendors Listed</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-uncovering-the-roars-of-legends-the-ultimate-collection-of-monster-audio/"><u>In 2024, Uncovering the Roars of Legends The Ultimate Collection of Monster Audio</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Oppo Find N3? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/should-you-embrace-windows-11s-secure-environment/"><u>Should You Embrace Windows 11'S Secure Environment?</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solving-full-screen-glitches-in-sonic-frontiers-windows-11/"><u>Solving Full-Screen Glitches in Sonic Frontiers (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-samsung-flow-linking-winpc-and-galaxy-device/"><u>Mastering Samsung Flow: Linking WinPC & Galaxy Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovative-virtual-bike-trails-unveiled-for-2024/"><u>Innovative Virtual Bike Trails Unveiled for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/unraveling-the-favorites-15-top-rated-books-in-booktoks-limelight/"><u>Unraveling the Favorites  15 Top-Rated Books in BookTok’s Limelight</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-quick-guide-to-mac-screen-taking-techniques/"><u>2024 Approved  Quick Guide to MAC Screen Taking Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-startup-item-disappearance/"><u>Identifying & Fixing Startup Item Disappearance</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-apple-iphone-15-plus-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From Apple iPhone 15 Plus</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-many-attempts-to-unlock-apple-iphone-6-by-drfone-ios/"><u>How Many Attempts To Unlock Apple iPhone 6</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-cut-your-videos-for-free-the-top-5-tools-we-love/"><u>New In 2024, Cut Your Videos for Free The Top 5 Tools We Love</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-group-policy-changes-on-a-windows-system/"><u>Navigating Group Policy Changes on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-it-administrator-cant-do-more-warning-in-winsec/"><u>Resolving 'IT Administrator Can’t Do More' Warning in WinSec</u></a></li>
<li><a href="https://win11.techidaily.com/running-advanced-ai-on-windows-devices/"><u>Running Advanced AI on Windows Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-on-iphone-12-mini-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 On iPhone 12 mini</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-syma-x8c-evaluation/"><u>2024 Approved  In-Depth Syma X8C Evaluation</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-biometric-settings-of-w11-for-domains/"><u>Mastering the Biometric Settings of W11 for Domains</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-11-file-transfers-that-halt/"><u>How to Resolve Windows 11 File Transfers That Halt</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/4-ways-to-unlock-iphone-13-pro-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>4 Ways to Unlock iPhone 13 Pro to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-banishing-auditory-distractions-a-guide-on-audacitys-noise-reduction/"><u>2024 Approved  Banishing Auditory Distractions  A Guide on Audacity's Noise Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-gaming-on-win-11-via-play-store-linkup/"><u>Seamless Android Gaming on Win 11 via Play Store Linkup</u></a></li>
<li><a href="https://win11.techidaily.com/make-windows-11-shine-a-holiday-system-guide/"><u>Make Windows 11 Shine: A Holiday System Guide</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-galaxy-performance-through-seamless-integration-in-windows-11/"><u>Optimizing Galaxy Performance Through Seamless Integration in Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-becoming-an-instagram-editor-extraordinaire/"><u>2024 Approved  Becoming an Instagram Editor Extraordinaire</u></a></li>
<li><a href="https://win11.techidaily.com/ignoring-the-windows-lsa-protection-deactivation/"><u>Ignoring the Windows LSA Protection Deactivation</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-breakdown-of-youtubes-monetization-update-for-2024/"><u>[Updated] Breakdown of YouTube's Monetization Update for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-mobile-and-desktop-video-player/"><u>2024 Approved  Best Mobile and Desktop Video Player</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-pc-data-access-everythingapp-utilization/"><u>Rapid PC Data Access: EverythingApp Utilization</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-dead-audio-a-step-by-step-guide-to-tech-sound/"><u>Resurrect Dead Audio: A Step-by-Step Guide to Tech Sound</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-keyboard-errors-fixing-function-keys-on-windows-11/"><u>Resolve: Keyboard Errors - Fixing Function Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-thumbnails-dimensions-on-desktop/"><u>Personalize Thumbnails: Dimensions on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/five-keys-to-a-streamlined-firewall-configuration/"><u>Five Keys to a Streamlined Firewall Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/stop-blue-screen-bsos-quick-fix-strategies-for-win11/"><u>Stop Blue Screen BSOS: Quick Fix Strategies for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-the-disappeared-disk-space-issue/"><u>Rectify the Disappeared Disk Space Issue</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevate-your-media-projects-utilizing-story-remix-in-windows-photos/"><u>Elevate Your Media Projects  Utilizing Story Remix in Windows Photos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-agriculture-amalgamations-best-friendly-farmers-game-roster/"><u>[New] In 2024, Agriculture Amalgamations  Best Friendly Farmer's Game Roster</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-kinemaster-way-to-enthralling-transitions/"><u>The Kinemaster Way to Enthralling Transitions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-time-warp-unlocking-freeze-frames-and-slow-motion-in-fcpx/"><u>New Time Warp Unlocking Freeze Frames and Slow Motion in FCPX</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-essential-guide-to-mastering-asmr-experience/"><u>[New] Essential Guide to Mastering ASMR Experience</u></a></li>
</ul></div>

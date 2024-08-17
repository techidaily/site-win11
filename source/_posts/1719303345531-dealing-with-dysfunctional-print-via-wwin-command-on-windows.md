---
title: Dealing with Dysfunctional Print via WWin Command on Windows
date: 2024-08-15T23:22:47.059Z
updated: 2024-08-16T23:22:47.059Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with Dysfunctional Print via WWin Command on Windows
excerpt: This Article Describes Dealing with Dysfunctional Print via WWin Command on Windows
keywords: Printer Functionality Windows,WinPrint Management,Dysfunctional Print Fix,Windows WinCmd Troubleshoot,Resolve WWin Errors,Command Line Print Help,Optimize Print on Windows
thumbnail: https://thmb.techidaily.com/543a8e6d7f06f3d9129829edd8982dbf9c6a6048e52160481e81c4276bc515b3.jpg
---

## Dealing with Dysfunctional Print via WWin Command on Windows

 When you press **Win + P** on Windows, you should see a flyout appear that contains options to switch your display. But, sometimes, when you press this shortcut, nothing happens, leaving you unable to change displays easily and quickly. Luckily, we're going to show you some fixes you can try to get the **Win + P** shortcut to work again.

## 1\. Troubleshoot the Keyboard

 Before we get to the other fixes, we highly recommend you try [troubleshooting the keyboard](https://www.makeuseof.com/fix-keyboard-keys-not-working-windows/). This includes checking if the keys are damaged, running the Keyboard Troubleshooter, and updating and reinstalling the keyboard driver.

 For the **Win + P** shortcut in particular, if updating and reinstalling the keyboard driver doesn't work, we recommend doing the same to the display driver as well.

 Another generic fix you can try is [performing an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to find and replace any corrupted or damaged system files on your PC that can cause **Win** \+ **P** to not work. Also, if you managed to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) when the shortcut was working, you can revert your PC's settings to that restore point to potentially fix the issue.

## 2\. Turn Off Game Mode

 Game Mode on Windows is a feature that turns off programs and tasks running in the background. That way, your PC has more resources to dedicate toward a smooth gaming experience. However, this feature is known to cause conflicts with the keyboard, and you can fix this by turning it off.

 To do that, press **Win** \+ **S** to bring up Windows Search, type **game mode settings** in the text box, and then click on **Game Mode settings** when it appears in the results.

![Game Mode settings in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/game-mode-settings-windows-search.jpg)

 If the **Game Mode** toggle is **On**, click on it to set it to the **Off** position.

![Turn Off the Game Mode From Game Mode Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/1-turn-off-the-game-mode-from-game-mode-settings-in-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 Now, try the **Win + P** shortcut again to see if the display switch options will show up.

## 3\. Make Sure the Action Center Is Working

 If the Action Center (Quick Settings on Windows 11) isn't working, it can cause the **Win + P** shortcut to not work. Try clicking on the Action Center and see if it will come up. If it doesn't, you can learn [how to fix the Action Center](https://www.makeuseof.com/windows-11-action-center-not-opening/)[when it is not opening](http://www.makeuseof.com/windows-11-action-center-not-opening/).

 Usually, it could just be that you, someone else, or a virus has somehow disabled the Action Center. In that case, you just need to re-enable it to get the shortcut to work again. If the reason is a virus, fire up your antivirus and scan your PC.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Try a Different User Account

 If your user account on Windows is corrupted, it can cause certain things to not work, including the **Win + P** shortcut. To verify whether your account is the problem or not, sign out and sign in to a different user account on your PC. Then, try the shortcut on the other user account, and if it works, you can use that one when you need to bring up the display switch options.

 Don't have another user account on your Windows computer? If that's the case, you can learn how to [create a local account on Windows 10](https://www.makeuseof.com/ways-to-create-local-user-account-windows/) or [create a local account on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/). Afterward, you can test if the shortcut is working on the user account you just created.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Create a Display Switch Shortcut

 If nothing you've done so far has worked, it might be time to use a workaround. One thing you can do is create a display switch shortcut that you can use to switch the display on your Windows PC.

 To do that, right-click an empty part of your Desktop and select **New > Shortcut**.

![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 The table below shows the locations of the various shortcuts for the display options:

| Display Option     | Shortcut Location                               |
| ------------------ | ----------------------------------------------- |
| PC screen only     | %windir%\\System32\\DisplaySwitch.exe /internal |
| Duplicate          | %windir%\\System32\\DisplaySwitch.exe /clone    |
| Extend             | %windir%\\System32\\DisplaySwitch.exe /extend   |
| Second screen only | %windir%\\System32\\DisplaySwitch.exe /external |

 Depending on the option you want to use, enter the appropriate shortcut location in the text box of the Create Shortcut wizard and click **Next**.

![entering the shortcut path for display switch in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-shortcut-display-switch-shortcut.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 Give the display switch shortcut a name and click **Finish**.

![naming the display switch shortcut in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/naming-display-switch-shortcut.jpg)

 You will find the display switch shortcut on the desktop, and when you double-click it, it will switch to the desired display option. You can create display switches for each option if you want.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## Get Win + P Working Again on Windows

 When you want to switch displays on Windows, the **Win + P** shortcut comes in handy. If it's not working, you can try the fixes above to get it to work. And if nothing helps, try creating a display switch shortcut as we've shown you.

 If you don't want to use the display switch shortcut, and you're sure there's nothing wrong with your keyboard, you can try the nuclear option: resetting your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-unhindered-movie-enjoyment-no-cost-video-player-pcmac/"><u>[New] In 2024, Unhindered Movie Enjoyment - No Cost VIDEO Player (PC/Mac)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-short-length-film-plot-plan/"><u>[Updated] Short-Length Film Plot Plan</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-which-video-sharing-platform-prevails-analyzing-igtv-vs-youtube/"><u>[Updated] Which Video Sharing Platform Prevails? Analyzing IGTV Vs. YouTube</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-blending-beats-into-bits-the-sound-savvy-image/"><u>2024 Approved  Blending Beats Into Bits  The Sound-Savvy Image</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-rated-components-for-smooth-live-transmissions/"><u>2024 Approved  Top-Rated Components for Smooth Live Transmissions</u></a></li>
<li><a href="https://win11.techidaily.com/7-game-changing-windows-11-additions-in-moment-22h2/"><u>7 Game-Changing Windows 11 Additions in Moment #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-utilities-to-update-file-timestamps/"><u>7 Windows Utilities To Update File Timestamps</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-rectifying-mmc-snap-in-failures/"><u>A Guide to Rectifying MMC Snap-In Failures</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-controls-filter-key-management-in-windows/"><u>Accessible Controls: Filter Key Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-device-disabled-error-code-22-on-windows-11/"><u>Addressing and Fixing Device Disabled (Error Code 22) on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/changing-file-formats-on-windows-os/"><u>Changing File Formats on Windows OS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-captivating-titles-with-ae/"><u>Crafting Captivating Titles with AE</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://buynow-info.techidaily.com/detailed-analysis-of-the-monoprice-drawing-pad-high-quality-for-less/"><u>Detailed Analysis of the Monoprice Drawing Pad: High Quality for Less</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-system-update-warnings/"><u>Disabling Windows System Update Warnings</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-voice-typing-hiccup-with-windows-error-code-x80049dd3-solution/"><u>Eliminating the Voice Typing Hiccup with Window's Error Code X80049DD3 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-disabled-status-on-windows-pcs/"><u>Fixing Grammarly Disabled Status on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-intel-wi-fi-ax201-on-pcs/"><u>Fixing Non-Operational Intel Wi-Fi AX201 on PCs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-backup-and-migrate-conversations-from-chatgpt/"><u>How to Backup and Migrate Conversations From ChatGPT</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oneplus-ace-3-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from OnePlus Ace 3 to New Android? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-seeking-a-true-witchs-tongue-are-vocal-changer-apps-legit-find-substitutes/"><u>In 2024, Seeking a True Witch's Tongue  Are Vocal Changer Apps Legit? Find Substitutes</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-vivo-v29-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Vivo V29? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-windows-11-boots-a-triad-of-tips/"><u>Mastering Faster Windows 11 Boots: A Triad of Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-removing-false-device-notifications/"><u>Mastering the Art of Removing False Device Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-restoring-ccleaner-on-win11/"><u>Mastering the Art: Restoring CCleaner on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-integrating-dynamic-desktop-backgrounds/"><u>Mastering Windows 11: Integrating Dynamic Desktop Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-warhammer-40k-boltgun-stopping-stutter-issues-on-pc/"><u>Mastery Over Warhammer 40K Boltgun: Stopping Stutter Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-mouse-precision-and-reduce-system-lag/"><u>Maximize Mouse Precision and Reduce System Lag</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-is-adding-ai-copilot-to-the-windows-11-taskbar-to-help-with-everything/"><u>Microsoft Is Adding AI Copilot to the Windows 11 Taskbar to Help With Everything</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-through-fake-words-discovering-and-using-gptzero-for-ai-text-detection/"><u>Navigating Through Fake Words - Discovering and Using GPTZero for AI Text Detection</u></a></li>
<li><a href="https://win11.techidaily.com/nine-no-go-areas-for-novice-windows-11-users/"><u>Nine No-Go Areas for Novice Windows 11 Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/odins-progeny-clash-of-titans/"><u>Odin’s Progeny  Clash of Titans</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-legacy-computer-for-windows-11-via-to-go-and-rufus/"><u>Optimize Your Legacy Computer for Windows 11 via To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-marketplace-colour-glitches/"><u>Rectifying Windows Marketplace Colour Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-failures-restoring-java-on-windows-devices/"><u>Resolving Failures: Restoring Java on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-volume-preferences-after-software-changes/"><u>Restoring Lost Volume Preferences After Software Changes</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-efficient-storage-controlling-ntfs-compression-in-win11/"><u>Secure & Efficient Storage: Controlling NTFS Compression in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-uninterrupted-usage-in-your-windows-dashboard/"><u>Secure Uninterrupted Usage in Your Windows Dashboard</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-wireless-gaming-setup-dualshock-on-pc/"><u>Simple Steps to Wireless Gaming: Setup DualShock on PC</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-windows-11-update-combat-error-0x30017/"><u>Smoothing Windows 11 Update: Combat Error 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-instructions-fully-removing-wsl/"><u>Step-By-Step Instructions: Fully Removing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11-cannot-open-for-writing/"><u>Steps to Overcome Windows 11: Cannot Open For Writing</u></a></li>
<li><a href="https://win11.techidaily.com/tech-renaissance-atlasos-for-obsolete-systems/"><u>Tech Renaissance: AtlasOS for Obsolete Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tango-dancing-devices-androidwindows-synchro/"><u>Tech Tango: Dancing Devices - Android/Windows Synchro</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-forgotten-directx-apps-with-dxvk-support/"><u>Transforming Forgotten DirectX Apps with DXVK Support</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1011s-aural-output-via-audacity/"><u>Troubleshooting Windows 10/11'S Aural Output, via Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-recommended-games-on-windows-11-screen/"><u>Turn Off Recommended Games on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unclouding-your-display-secrets-to-a-sharp-windows-11-screen/"><u>Unclouding Your Display: Secrets to a Sharp Windows 11 Screen</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlock-creative-potential-with-premium-effects-extensions-for-2024/"><u>Unlock Creative Potential with Premium Effects Extensions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-assistance-best-free-tools-for-a-win11-revamp/"><u>Unmatched Assistance: Best Free Tools for a Win11 Revamp</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-workings-of-windows-component-services/"><u>Unveiling the Workings of Windows Component Services</u></a></li>
<li><a href="https://win11.techidaily.com/win1110-nat-transition-altering-type-effectively/"><u>Win11/10 NAT Transition: Altering Type Effectively</u></a></li>
</ul></div>

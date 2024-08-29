---
title: "Proactive Windows Care: Self-Updates + GPU Switching Routine"
date: 2024-08-28T00:51:08.807Z
updated: 2024-08-29T00:51:08.807Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Proactive Windows Care: Self-Updates + GPU Switching Routine"
excerpt: "This Article Describes Proactive Windows Care: Self-Updates + GPU Switching Routine"
keywords: Proactive PC Updates,Windows Update Guide,Regular System Checks,Dynamic GPU Settings,Optimized PC Health,Efficient OS Maintenance,Routine Hardware Upgrade
thumbnail: https://thmb.techidaily.com/f4b94a6052a83b6c87620891bae2ef1d10a06ae6e718f7d201b09964291e2b88.jpg
---

## Proactive Windows Care: Self-Updates + GPU Switching Routine

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.
5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.


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
<li><a href="https://vimeo-videos.techidaily.com/new-ace-all-round-strategies-maximizing-efficiency-in-acquiring-and-storing-vimeo-videos-for-2024/"><u>[New] Ace All-Round Strategies  Maximizing Efficiency in Acquiring & Storing Vimeo Videos for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-dissection-facebook-video-formats/"><u>[New] Dissection  Facebook Video Formats</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-amplify-your-video-content-with-precision-insights-from-social-blade-and-youtube/"><u>[New] In 2024, Amplify Your Video Content with Precision Insights From Social Blade & YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-essential-techniques-for-yt-video-tweaking-with-wm-maker/"><u>[New] In 2024, Essential Techniques for YT Video Tweaking with WM Maker</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-instantaneous-picture-viewing-on-windows-11/"><u>[New] Instantaneous Picture Viewing on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-top-10-terraria-game-boosters/"><u>[New] Top 10 Terraria Game Boosters</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2023s-leading-cost-free-fb-picture-and-video-developer-tools-for-2024/"><u>[Updated] 2023'S Leading, Cost-Free FB Picture and Video Developer Tools for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-top-social-strategies-android-and-iphones-most-effective-fb-apps/"><u>[Updated] 2024 Approved  Top Social Strategies  Android & iPhone's Most Effective FB Apps</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-quality-audio-awaits-with-these-premium-asmr-mics/"><u>[Updated] In 2024, Quality Audio Awaits with These Premium ASMR Mics</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/1715859984282-updated-quick-guide-to-incor-written-as-a-python-list-which-represents-the-30-titles-above-the-elements-of-this-list-should-be-strings-that-are-already-comp/"><u>[Updated] Quick Guide to Incor Written as a Python List, Which Represents the 30 Titles Above. The Elements of This List Should Be Strings that Are Already Complete Sentences and Adhere to the Given Constraints. Ensure No Title Exceeds 156 Characters.</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-ultimate-guide-to-screen-capture-in-macos/"><u>[Updated] The Ultimate Guide to Screen Capture in macOS</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-tecno-spark-10c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-reversing-live-on-twitch-a-top-ten-guide/"><u>2024 Approved  Reversing Live on Twitch  A Top Ten Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-unlock-the-secrets-of-youtube-monetization-key-viewer-numbers/"><u>2024 Approved  Unlock the Secrets of YouTube Monetization  Key Viewer Numbers</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-y78t-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/blur-unwanted-parts-of-your-videos-with-these-mobile-apps/"><u>Blur Unwanted Parts of Your Videos with These Mobile Apps</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-with-ease-understanding-microsofts-phone-link-app/"><u>Connecting with Ease: Understanding Microsoft's Phone Link App</u></a></li>
<li><a href="https://win11.techidaily.com/delaying-windows-11-shutdown-techniques-for-active-processestasks/"><u>Delaying Windows 11 Shutdown: Techniques for Active Processes/Tasks</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/delving-into-tseries-streaming-revenue-model-on-youtube/"><u>Delving Into TSeries' Streaming Revenue Model on YouTube</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elite-film-shooting-devices-with-smooth-motion/"><u>Elite Film Shooting Devices with Smooth Motion</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/essential-guide-to-economical-multiplatform-video-conferencing-software-for-2024/"><u>Essential Guide to Economical, Multiplatform Video Conferencing Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/evaluate-your-needs-best-windows-11-choice-between-home-and-pro/"><u>Evaluate Your Needs: Best Windows 11 Choice Between Home and Pro</u></a></li>
<li><a href="https://fox-direct.techidaily.com/expert-analysis-the-full-spectrum-of-bublcam-360/"><u>Expert Analysis  The Full Spectrum of Bublcam 360</u></a></li>
<li><a href="https://tech-revival.techidaily.com/explore-these-5-ai-powered-scripters-to-spark-creativity-in-writing/"><u>Explore These 5 AI-Powered Scripters to Spark Creativity in Writing</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unclog-printer-usage-jams-in-win11/"><u>Guide to Unclog Printer Usage Jams in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-out-a-no-logo-screen-in-win1011/"><u>How to Clear Out a No-Logo Screen in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-10-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 10 & 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-smart-8-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Smart 8 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-and-connect-chrome-in-your-os-firewallantivirus-settings/"><u>How to Unblock and Connect Chrome in Your OS Firewall/Antivirus Settings</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-f5-pro-5g-phone-without-google-account-by-drfone-android/"><u>How to Unlock Poco F5 Pro 5G Phone without Google Account?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-nokia-c12-plus-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Nokia C12 Plus Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-note-30-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Infinix Note 30 Bootloader Easily</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-mastering-reverse-image-scanning-on-instagram-photos/"><u>In 2024, Mastering Reverse Image Scanning on Instagram Photos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-unveiling-the-secrets-of-professional-free-youtube-transcription/"><u>In 2024, Unveiling the Secrets of Professional Free YouTube Transcription</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsofts-filter-key-functionality/"><u>Mastering Microsoft's Filter Key Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-frozen-windows-update-issue/"><u>Mastery Over Frozen Windows Update Issue</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-failed-geforce-scans-on-pcs-running-windows/"><u>Navigating Failed GeForce Scans on PCs Running Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-drivers-a-step-by-step-guide/"><u>Overhauling Windows Drivers: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-windows-11-ceasing-background-tasks/"><u>Quiet Windows 11: Ceasing Background Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-misdirected-mouse-motion-in-windows-systems/"><u>Rectify Misdirected Mouse Motion in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frustrating-apex-legends-crashes-in-win11/"><u>Resolving Frustrating Apex Legends Crashes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-wsl-the-4294967295-error-explained/"><u>Resolving WSL: The 4294967295 Error Explained</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-vanishing-steam-icon-graphics/"><u>Reviving Vanishing Steam Icon Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-photo-correction-mastering-background-removal/"><u>Seamless Photo Correction: Mastering Background Removal</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-ai-risks-when-crafting-your-win-11-code/"><u>Sidestep AI Risks When Crafting Your Win 11 Code</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-customizing-windows-explorer-again/"><u>Simple Steps: Customizing Windows Explorer Again</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-unlock-device-driver-access-in-windows-11/"><u>Strategies to Unlock Device Driver Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-with-w11-pinning-tips/"><u>Streamline Your Desktop with W11 Pinning Tips</u></a></li>
<li><a href="https://win11.techidaily.com/sync-issue-resolved-windows-time-coordination/"><u>Sync Issue Resolved: Windows Time Coordination</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-free-desktop-password-generators-for-windows/"><u>The 7 Best Free Desktop Password Generators for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-stealth-attacker-uncovered-defending-windows-against-wacatacbml/"><u>The Stealth Attacker Uncovered: Defending Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://win11.techidaily.com/transition-tactics-replacing-older-software-with-windows-11/"><u>Transition Tactics: Replacing Older Software with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-control-panel-errors/"><u>Troubleshooting Windows Control Panel Errors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-system-call-failures-in-windows-11/"><u>Troubleshooting: Resolving System Call Failures in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-unveiling-their-differences/"><u>Windows Terminal & PowerShell: Unveiling Their Differences</u></a></li>
<li><a href="https://win11.techidaily.com/windows-tips-for-distinguishing-between-hdd-and-ssd/"><u>Windows Tips for Distinguishing Between HDD and SSD</u></a></li>
<li><a href="https://win11.techidaily.com/winning-workflows-6-top-time-management-apps-reviewed/"><u>Winning Workflows: 6 Top Time Management Apps Reviewed</u></a></li>
</ul></div>

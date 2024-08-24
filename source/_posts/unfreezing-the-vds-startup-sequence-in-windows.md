---
title: Unfreezing the VDS Startup Sequence in Windows
date: 2024-08-23T06:11:52.397Z
updated: 2024-08-24T06:11:52.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unfreezing the VDS Startup Sequence in Windows
excerpt: This Article Describes Unfreezing the VDS Startup Sequence in Windows
keywords: Unfreeze WinVDS,Windows VDS Start,VDS Boot Fix,VDS Boot Sequence,BootVDS Issue,VDS Startup Solution,Windows VDS Freezing
thumbnail: https://thmb.techidaily.com/c48fccee15d64e7778fd76c19af1e8a44abed6b45fe483336543f1981668afa0.jpg
---

## Unfreezing the VDS Startup Sequence in Windows

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-best-of-the-best-android-calls-with-more-than-just-two/"><u>[New] Best of the Best  Android Calls with More Than Just Two</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-capturing-unrooted-audio-4-easy-steps-for-android-for-2024/"><u>[New] Capturing Unrooted Audio  4 Easy Steps for Android for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-low-cost-pc-unlock-with-ideal-obs-settings/"><u>[New] In 2024, Low-Cost PC - Unlock with Ideal OBS Settings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-quick-screen-cut-and-paste-in-winoses/"><u>[New] Quick Screen Cut & Paste in WinOSes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-instagram-stories-incorporating-natural-bokeh-effects/"><u>2024 Approved  Instagram Stories  Incorporating Natural Bokeh Effects</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-why-does-imovie-crop-my-videos/"><u>2024 Approved  Why Does iMovie Crop My Videos?</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-live-shopping-success-secrets-unveiling-strategies-from-real-case-studies/"><u>2024 Approved Live Shopping Success Secrets Unveiling Strategies From Real Case Studies</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-realme-c67-4g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Realme C67 4G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/aggregate-of-top-20-chatgpt-question-and-response-examples/"><u>Aggregate of Top 20 ChatGPT Question and Response Examples</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-itel-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Itel .</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-zero-error-win11s-onedrive-sign-in-woes-eliminated/"><u>Conquering Zero-Error: Win11's OneDrive Sign-In Woes Eliminated</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-dism-commands-for-win11-os-revival/"><u>Dissecting Dism Commands for Win11 OS Revival</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-driver-not-working-on-your-windows-1011-pc/"><u>Eliminate Driver Not Working on Your Windows 10/11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-device-recognition-post-sleep-cycle/"><u>Fine-Tuning Device Recognition Post-Sleep Cycle</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win-10-and-11-intruder-exceptions-error-message/"><u>Fixing Win 10 & 11 Intruder Exceptions Error Message</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-nokia-g42-5g-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Nokia G42 5G?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-successfully-fix-windows-update-error-xc004f050/"><u>How to Successfully Fix Windows Update Error XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-restart-a-users-guide-for-quick-start-in-windows-11/"><u>How to Swiftly Restart: A User’s Guide for Quick Start in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-honor-x9a-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Honor X9a Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-minisculecam-record-evaluation-and-comparisons/"><u>In 2024, MinisculeCam Record Evaluation & Comparisons</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-twittersphere-treasure-trove/"><u>In 2024, The Twittersphere Treasure Trove</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-transforming-industries-with-virtual-reality-applications/"><u>In 2024, Transforming Industries with Virtual Reality Applications</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-honor-100-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-comprehensive-removal-of-wsl-from-win-11-pcs/"><u>Master Plan: Comprehensive Removal of WSL From Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-pc-sound-with-windows-11s-advanced-mixer-features/"><u>Master Your PC Sound with Windows 11'S Advanced Mixer Features</u></a></li>
<li><a href="https://win11.techidaily.com/memory-cache-mastery-in-windows-systems/"><u>Memory Cache Mastery in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/missing-bluetooth-in-win-11-strategies-for-quick-recovery/"><u>Missing Bluetooth in Win 11: Strategies for Quick Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/probing-windows-entry-status-victory-or-defeat-stories/"><u>Probing Windows Entry Status: Victory or Defeat Stories</u></a></li>
<li><a href="https://win11.techidaily.com/propel-audio-innovations-setting-up-dolby-atmos-for-pcs/"><u>Propel Audio Innovations: Setting up Dolby Atmos for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-resolving-package-could-not-be-opened-on-win11-10/"><u>Quick Steps for Resolving 'Package Could Not Be Opened' On Win11, 10</u></a></li>
<li><a href="https://win11.techidaily.com/quick-launch-application-strategies-on-windows-11/"><u>Quick-Launch Application Strategies on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/retuning-windows-11-energy-settings-from-loss/"><u>Retuning Windows 11 Energy Settings From Loss</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-response-restoration-nvlddmkm-fixed/"><u>Screen Response Restoration: Nvlddmkm Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-verifying-your-windows-11-temp-files/"><u>Steps for Verifying Your Windows 11 Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-from-pushing-high-contrast/"><u>Stop Windows From Pushing High Contrast</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-failed-connections-between-win10win11-and-nvidia/"><u>Tackling Failed Connections Between Win10/Win11 and Nvidia</u></a></li>
<li><a href="https://win11.techidaily.com/the-compreenas-guide-to-managing-files-without-renaming-directories-on-win-11/"><u>The Compreenas Guide to Managing Files Without Renaming Directories on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-windows-n-versions-decision-making-factors/"><u>The Essence of Windows N Versions: Decision-Making Factors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-metaverse-memes-and-diy-humor-mastery-for-2024/"><u>The Ultimate Guide to Metaverse Memes and DIY Humor Mastery for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshoot-no-more-discords-update-fiasco-corrected-for-optimal-performance/"><u>Troubleshoot No More: Discord's Update Fiasco Corrected for Optimal Performance</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-high-resource-consumption-due-to-unrealcefsubprocess/"><u>Troubleshooting Windows' High Resource Consumption Due to UnrealCEFSubprocess</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-on-iphone-se-2020-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide on iPhone SE (2020) iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-efficiency-grouped-installs-with-winstall-on-windows-11/"><u>Unleashing Efficiency: Grouped Installs with Winstall on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlimited-entertainment-on-the-road-using-hotel-or-dorm-mobile-hotspots-with-your-roku-device/"><u>Unlimited Entertainment on the Road: Using Hotel or Dorm Mobile Hotspots with Your Roku Device</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722960731876-update-your-nvidia-quadro-rtx-4000-with-the-newest-drivers-here/"><u>Update Your Nvidia Quadro RTX #4000 with the Newest Drivers Here!</u></a></li>
<li><a href="https://win11.techidaily.com/vintage-games-journey-from-backups-to-windows-11-pics/"><u>Vintage Games Journey: From Backups to Windows 11 Pics</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
---
title: "Guide: Disabling Laptop's Hardware Keys on Windows PC"
date: 2024-08-15T23:55:36.075Z
updated: 2024-08-16T23:55:36.075Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Disabling Laptop's Hardware Keys on Windows PC"
excerpt: "This Article Describes Guide: Disabling Laptop's Hardware Keys on Windows PC"
keywords: Hardware Key Disable,Wi-Fi Key Off,BIOS Security Lock,Laptop Secure PC,Windows Input Halt,Hardware Keypad Turnoff,Device Safety Setup,PC Security Guide,Hardware Lock Windows,Laptop Controls Halt,Keyboard Disable Procedures
thumbnail: https://thmb.techidaily.com/017337439b4f792b0246468061b8e1aa8f8f36d01cdf2619fb3c06685fc0972f.jpg
---

## Guide: Disabling Laptop's Hardware Keys on Windows PC

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-a-comprehensive-guide-to-business-on-snapchat/"><u>[New] In 2024, A Comprehensive Guide to Business on Snapchat</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-effortlessly-transform-youtube-tunes-to-mp3-with-mac/"><u>[New] In 2024, Effortlessly Transform YouTube Tunes to MP3 with Mac</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-getting-to-grips-with-bandicam-your-guide-through-2023s-updates/"><u>[New] In 2024, Getting to Grips with Bandicam – Your Guide Through 2023'S Updates</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-photographers-pathway-transitioning-from-camera-to-computer-screen/"><u>[Updated] 2024 Approved  The Photographer's Pathway  Transitioning From Camera to Computer Screen</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-free-up-your-time-with-these-5-chrome-plugins-for-fb-video-downloads-for-2024/"><u>[Updated] Free Up Your Time with These 5 Chrome Plugins for FB Video Downloads for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-leading-free-cam-stream-and-recorder-tool/"><u>[Updated] In 2024, Leading Free Cam Stream & Recorder Tool</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-microscreenmugger-assessment-report/"><u>[Updated] MicroScreenMugger Assessment Report</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-advanced-scheduling-with-premium-recording-software/"><u>2024 Approved  Advanced Scheduling with Premium Recording Software</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-microsoft-hololens-review-a-glimpse-of-holographic-future/"><u>2024 Approved  Microsoft HoloLens Review- a Glimpse of Holographic Future</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-the-ultimate-guide-to-top-10-tiktok-gamers/"><u>2024 Approved  The Ultimate Guide to Top 10 TikTok Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-windows-voice-recording/"><u>A Step-By-Step Guide to Windows Voice Recording</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-efficiency-via-powertoys/"><u>Accelerate Keyboard Efficiency via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-the-search-function-in-windows-11-for-you/"><u>Adapting the Search Function in Windows 11 for You</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-uncertainty-check-cpu-generation-on-windows-8-ways/"><u>Avoid Uncertainty – Check CPU Generation on Windows (8 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-demystified-how-to-resolve-windows-crashes-quickly/"><u>Blue Screen Demystified: How To Resolve Windows Crashes Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-error-8007000e-effortless-solutions-for-windows-users/"><u>Bypassing Error 8007000E: Effortless Solutions for Windows Users</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-oppo-find-n3-flip-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Oppo Find N3 Flip to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-re-establishing-managed-status-on-windows-11/"><u>Comprehensive Guide for Re-Establishing Managed Status on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-technologies-in-microsofts-ai-hub/"><u>Demystifying the Technologies in Microsoft's AI Hub</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-greyed-out-display-changes-on-windows-system/"><u>Eliminate Greyed-Out Display Changes on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-microsofts-smartguard-in-win-10/"><u>Enabling/Disabling Microsoft's SmartGuard in Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-reliable-voice-commands-for-valorant-gaming/"><u>Ensuring Reliable Voice Commands for Valorant Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-requires-privilege-error-code-0x80070522-in-windows-devices/"><u>Eradicating Requires Privilege Error (Code 0X80070522) in Windows Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/excellent-text-plugin-compendium/"><u>Excellent Text Plugin Compendium</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-abrupt-device-removal-errors-dxgi/"><u>Fixing Abrupt Device Removal Errors (DXGI)</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-oppo-a78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-reopen-stuck-adobe-photoshop-in-windows/"><u>Guidelines to Reopen Stuck Adobe Photoshop in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-poco-c51-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Poco C51 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-12-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 12 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-gallery-in-file-explorer-in-windows-11/"><u>How to Enable the Gallery in File Explorer in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-spark-interest-and-boost-views-on-instagram-videos-for-2024/"><u>How to Spark Interest & Boost Views on Instagram Videos for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-infinix-hot-40i-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Infinix Hot 40i to iPod | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ignite-creative-spark-choosing-from-the-best-6-nft-services-for-2024/"><u>Ignite Creative Spark  Choosing From the Best 6 NFT Services for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy XCover 6 Pro Tactical Edition to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-mastering-your-mac-a-complete-guide-to-leveraging-preview-features/"><u>In 2024, Mastering Your Mac  A Complete Guide to Leveraging Preview Features</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-10-audio-playback-accelerators-for-phones/"><u>In 2024, Top 10 Audio Playback Accelerators for Phones</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-canary-your-security-ally/"><u>Intro to Windows Canary: Your Security Ally</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-windows-11-desktop-sparkle-with-lively-wallpaper-art/"><u>Make Your Windows 11 Desktop Sparkle with Lively Wallpaper Art</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/mastering-facebook-broadcasts-android-and-ios-tips-for-2024/"><u>Mastering Facebook Broadcasts  Android & iOS Tips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-pc-power-for-distributed-video-conversion-by-tdarr/"><u>Optimize PC Power for Distributed Video Conversion by Tdarr</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-boot-failures-8-fixes-for-virtual-machines-on-wm11os/"><u>Overcome Boot Failures: 8 Fixes for Virtual Machines on WM11OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-windows-laptop-lag-on-dual-screens/"><u>Overcoming the Hurdle of Window's Laptop Lag on Dual Screens</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/quick-solution-how-to-stop-outriders-from-frequently-freezing/"><u>Quick Solution: How to Stop Outriders From Frequently Freezing</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-overcoming-geforce-x0001-on-w10w11-pcs/"><u>Quick Tips: Overcoming GeForce X0001 on W10/W11 PCs</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolve-freeze-problem-windows-pointer/"><u>Resolve Freeze Problem: Windows Pointer</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-visibility-to-system-startups-on-win-os/"><u>Restoring Visibility to System Startups on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-reviving-windows-or-beyond/"><u>Rethink Reviving: Windows or Beyond?</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-non-functional-email-banners-for-office-users/"><u>Reviving Non-Functional Email Banners for Office Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/revolutionize-your-gameplay-with-this-gratuitous-voice-alterer-for-2024/"><u>Revolutionize Your Gameplay with This Gratuitous Voice Alterer for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/seamlessly-casting-your-favorite-shows-a-guide-on-linking-disneyplus-with-chromecast/"><u>Seamlessly Casting Your Favorite Shows: A Guide on Linking Disney+ with Chromecast</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sector-mastering-windows-methods-for-adapter-velocity-check/"><u>Speed Sector: Mastering Windows Methods for Adapter Velocity Check</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-addressing-windows-non-response-to-powershell-command/"><u>Steps for Addressing Windows Non-Response to PowerShell Command</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sharing-with-the-top-5-software-picks-for-pcs/"><u>Streamlined Sharing with the Top 5 Software Picks for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-typing-experience-changing-layouts-on-windows-11/"><u>Tailoring Your Typing Experience: Changing Layouts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-picks-for-integrating-frame-elements-with-images/"><u>Top Picks for Integrating Frame Elements with Images</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/transform-your-memories-into-engaging-facebook-slides/"><u>Transform Your Memories Into Engaging Facebook Slides</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-administrator-experience-via-terminals-every-time/"><u>Unhindered Administrator Experience via Terminals Every Time</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now</u></a></li>
<li><a href="https://data-wizards.techidaily.com/1720671600114-video-file-issues-after-stellar-repairing/"><u>Video File Issues After Stellar Repairing.</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tech-tutorial-how-to-launch-calculator/"><u>Windows 11 Tech Tutorial: How to Launch Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-unlock-the-secrets-of-measuring-ethernet-speeds/"><u>Windows Wonders: Unlock the Secrets of Measuring Ethernet Speeds</u></a></li>
</ul></div>

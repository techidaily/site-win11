---
title: "Tech Tip: Quiet Down Windows' Hardware Keys"
date: 2024-08-23T06:06:24.502Z
updated: 2024-08-24T06:06:24.502Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Tip: Quiet Down Windows' Hardware Keys"
excerpt: "This Article Describes Tech Tip: Quiet Down Windows' Hardware Keys"
keywords: Silent Keyboard Windows,Mute Hardware Keys,Reduce Noise PC,Hush Sound Chimes,Quiet System Notifications,Dampen Key Clicks,Soft Alert Keys Tip
thumbnail: https://thmb.techidaily.com/9c499903b4fab811676ace6dccfa6523d6366f829a8f8e74e35020e8fb091823.jpg
---

## Tech Tip: Quiet Down Windows' Hardware Keys

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
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-youtubes-networking-finding-and-creating-video-co-ops/"><u>[New] Mastering YouTube's Networking  Finding and Creating Video Co-Ops</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-simplified-approaches-to-insta-photovideo-resharing-for-2024/"><u>[Updated] Simplified Approaches to Insta Photo/Video Resharing for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-full-screen-pro-excellence-4-precise-pc-and-mac-tools/"><u>2024 Approved  Full Screen Pro Excellence  4 Precise PC & Mac Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-go-beyond-screens-how-to-watch-360-videos-and-vr-via-android/"><u>2024 Approved  Go Beyond Screens  How to Watch 360 Videos & VR via Android</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unmissable-upgrades-top-8-tech-and-tools-reshaping-modern-enterprises/"><u>2024 Approved  Unmissable Upgrades  Top 8 Tech & Tools Reshaping Modern Enterprises</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/additional-tips-about-sinnoh-stone-for-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-itel-a05s-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Itel A05s Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-e84-in-steam-games/"><u>Eliminating Error Code E84 in Steam Games</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-no-device-drivers-detected-in-windows-setup/"><u>Eliminating Error: No Device Drivers Detected in Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-text-input-experience-integrating-wordpad-triggers-in-windows-11/"><u>Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-lowering-wlanext-cpu-usage/"><u>Essential Tips for Lowering WLANEXT CPU Usage</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-frequent-icloud-glitches-on-your-apple-devices-solutions-for-the-top-9-problems/"><u>Fixing Frequent iCloud Glitches on Your Apple Devices: Solutions for the Top 9 Problems</u></a></li>
<li><a href="https://win11.techidaily.com/from-apple-to-microsoft-transition-guide-for-windows-11-via-parallels/"><u>From Apple to Microsoft: Transition Guide for Windows 11 via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reducing-sound-boost-in-windows/"><u>Guide to Reducing Sound Boost in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-60-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Realme Narzo 60 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11.techidaily.com/how-windows-11-secures-your-files-understanding-the-backup-feature/"><u>How Windows 11 Secures Your Files: Understanding the Backup Feature</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-turning-fans-into-followers-friends-and-profits/"><u>In 2024, Turning Fans Into Followers, Friends, and Profits</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-locked-credential-management/"><u>Navigating Locked Credential Management</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-file-selection-activating-filters-with-box-on-win11/"><u>Optimal File Selection: Activating Filters with Box on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-screen-darkness-problem/"><u>Overcoming Chrome's Screen Darkness Problem</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-windows-11-manager-access-restoration-techniques/"><u>Overcoming Obstacles: Windows 11 Manager Access Restoration Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pinpointing-the-premier-top-10-pc-vr-headset-models-of-2-written-by-dr-jane-smith-on-january-15-2023/"><u>Pinpointing the Premier  Top 10 PC VR Headset Models of 2 Written by Dr. Jane Smith on January 15, 2023</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-recognize-absconded-drive-issues/"><u>Solutions to Recognize Absconded Drive Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-challenge-of-elevated-gpu-use-by-dwm-essential-fixes-for-windows-1011/"><u>Solving the Challenge of Elevated GPU Use by DWM - Essential Fixes for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-entry-tricks-beat-delayed-inputs-in-windows-11-environment/"><u>Speedy Entry Tricks: Beat Delayed Inputs in Windows 11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-turning-on-mouse-gestures-in-windows-11s-edge/"><u>Step-by-Step: Turning on Mouse Gestures in Windows 11'S Edge</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-sticking-notebooks-front-and-center/"><u>Tips for Sticking Notebooks Front and Center</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-over-obstacles-disable-windows-11-tpm-swiftly/"><u>Triumph Over Obstacles: Disable Windows 11 TPM Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-enterprise-controlled-chromeedge-browsers-on-pcs/"><u>Troubleshooting Enterprise-Controlled Chrome/Edge Browsers on PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-262-robloxs-solution-path/"><u>Unraveling Error 262: Roblox's Solution Path</u></a></li>
<li><a href="https://win11.techidaily.com/windows-reserve-a-detailed-look-at-memory-management/"><u>Windows Reserve: A Detailed Look at Memory Management</u></a></li>
<li><a href="https://win11.techidaily.com/winning-war-against-sse-windows-woes/"><u>Winning War Against SSE Windows Woes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/your-ultimate-path-to-google-podcast-submission/"><u>Your Ultimate Path to Google Podcast Submission</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
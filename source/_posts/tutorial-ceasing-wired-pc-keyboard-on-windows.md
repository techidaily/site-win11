---
title: "Tutorial: Ceasing Wired PC Keyboard on Windows"
date: 2024-08-15T23:56:11.510Z
updated: 2024-08-16T23:56:11.510Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Ceasing Wired PC Keyboard on Windows"
excerpt: "This Article Describes Tutorial: Ceasing Wired PC Keyboard on Windows"
keywords: Disconnecting Keyboards,PC Keyboard Removal Guide,Remove Wired Mouse From PC,Unplugging Keyboards on Windows,How to Dismount Wired Input Devices,Ceasing Wired Peripherals in WinOS,Disabling USB Keyboards Windows
thumbnail: https://thmb.techidaily.com/f567a9fec699d773d0b269b2abfaf091f129a875a6f111520a97150e50266041.jpg
---

## Tutorial: Ceasing Wired PC Keyboard on Windows

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select **Browse my computer for drivers**.  
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-essential-guide-to-the-top-10-video-calls-for-your-smartphone/"><u>[New] 2024 Approved  Essential Guide to the Top 10 Video Calls for Your Smartphone</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-snapchat-tricks-unleashing-yourself-with-a-cartoon-lens/"><u>[New] In 2024, Snapchat Tricks  Unleashing Yourself with a Cartoon Lens</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-master-the-momentum-sending-viral-videos-soaring/"><u>[New] Master the Momentum  Sending Viral Videos Soaring</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-heroic-journeys-unleashed-the-premier-game-collection/"><u>[Updated] 2024 Approved  Heroic Journeys Unleashed  The Premier Game Collection</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-methods-to-clear-up-obs-fullscreen-troubles/"><u>[Updated] 2024 Approved  Methods to Clear Up OBS Fullscreen Troubles</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-replay-redux-mastering-iphones-videography-backwards/"><u>[Updated] Replay Redux  Mastering iPhone's Videography Backwards</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/5-top-win-drawing-apps-that-challenge-procreates-edge/"><u>5 Top Win Drawing Apps That Challenge Procreate's Edge</u></a></li>
<li><a href="https://win11.techidaily.com/6-disappearing-windows-traits-explained/"><u>6 Disappearing Windows Traits Explained</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-reasons-users-prefer-older-windows-versions/"><u>7 Key Reasons Users Prefer Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-check-which-intel-processor-generation-you-have-on-windows/"><u>8 Ways to Check Which Intel Processor Generation You Have on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comparative-study-of-cloud-and-physical-methods-for-windows-setup/"><u>A Comparative Study of Cloud & Physical Methods for Windows Setup</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-comprerans-guide-to-capturing-spectacular-slow-motion-on-hero-10-for-2024/"><u>A Compreran's Guide to Capturing Spectacular Slow Motion on Hero 10 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-troubleshooting-windows-desktop-icons/"><u>A Guide to Troubleshooting Windows Desktop Icons</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-modifying-windows-system-booting-behavior/"><u>A Practical Guide to Modifying Windows System Booting Behavior</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-skills-using-windows-powertoys/"><u>Accelerate Keyboard Skills Using Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-winning-path-with-efficient-play/"><u>Accelerate Your Winning Path with Efficient Play</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-your-download-experience-with-epic-launcher/"><u>Accelerating Your Download Experience with Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/activate-dark-theme-for-windows-calc/"><u>Activate Dark Theme for Windows Calc</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-in-recent-windows-discord-upgrades/"><u>Addressing Failure in Recent Windows Discord Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/adopting-new-visual-elements-the-microsoft-store-experience/"><u>Adopting New Visual Elements: The Microsoft Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-windows-identifier-with-microsoft-entity/"><u>Aligning Windows Identifier with Microsoft Entity</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-11-crashes-interrupt-fixation/"><u>Avoiding Windows 11 Crashes: Interrupt Fixation</u></a></li>
<li><a href="https://win11.techidaily.com/beating-down-error-code-31-in-the-windows-landscape/"><u>Beating Down Error Code 31 in the Windows Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-of-windows-modern-standby-problems/"><u>Beneath the Surface of Windows Modern Standby Problems</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-tools-for-win-1011s-dropdowns/"><u>Beneath-the-Surface Tools for Win 10/11'S Dropdowns</u></a></li>
<li><a href="https://win11.techidaily.com/blending-elegance-with-utility-the-asus-vivobook-s-15-edition/"><u>Blending Elegance with Utility: The ASUS Vivobook S 15 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/boost-security-enable-or-disable-tpm-and-secure-boot-in-virtualbox/"><u>Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-gameplay-flush-and-optimize-steam-dns-cache/"><u>Boost Your Gameplay: Flush and Optimize Steam DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-productivity-enlarge-or-minify-software-via-keyboard-in-win11/"><u>Boost Your Productivity: Enlarge or Minify Software via Keyboard in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-taskbar-efficiency/"><u>Boosting Windows 11 Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/boot-overhaul-guide-windows-revival-in-eight-steps/"><u>Boot Overhaul Guide: Windows Revival in Eight Steps</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-swapping-old-to-new-window-drivers/"><u>Breaking Barriers: Swapping Old to New Window Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-code-breakdowns-quick-windows-fixes/"><u>Breaking Free From Code Breakdowns: Quick Windows Fixes</u></a></li>
<li><a href="https://driver-download.techidaily.com/effortless-installation-access-the-ultimate-downloaded-instructions-for-behringers-usb-sound-device/"><u>Effortless Installation: Access the Ultimate Downloaded Instructions for Behringer's USB Sound Device!</u></a></li>
<li><a href="https://win11.techidaily.com/1719327784213-fixing-the-common-wwinplusp-errors-on-windows-devices/"><u>Fixing the Common WWin+P Errors on Windows Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-excel-2003-run-time-error-1004-stellar-by-stellar-guide/"><u>How to Fix Excel 2003 Run Time Error 1004 | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-oppo-a78-by-fonelab-android-recover-photos/"><u>How to get back lost photos from Oppo A78.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-amazon-prime-hits-twitters-trendiest-watchers-and-lovers/"><u>In 2024, Amazon Prime Hits  Twitter's Trendiest Watchers & Lovers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-samsung-galaxy-xcover-6-pro-tactical-edition-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Samsung Galaxy XCover 6 Pro Tactical Edition Location by Number | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-vivo-y200e-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Vivo Y200e 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-techniques-to-smooth-out-lagging-sims-4-gameplay-on-windowsmac-2024-insights/"><u>Top Techniques to Smooth Out Lagging Sims 4 Gameplay on Windows/Mac - 2024 Insights</u></a></li>
<li><a href="https://win11.techidaily.com/1719239311887-unlock-the-future-at-an-irresistible-price-best-windows-11-deal-612lifetime-key-lovers-delight/"><u>Unlock the Future at an Irresistible Price – Best Windows 11 Deal, $6.12/Lifetime, Key Lovers' Delight</u></a></li>
</ul></div>

---
title: Technique to Turn Off Keyboard for Your Win-Run Devices
date: 2024-11-06T22:16:35.186Z
updated: 2024-11-07T22:36:47.717Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Technique to Turn Off Keyboard for Your Win-Run Devices
excerpt: This Article Describes Technique to Turn Off Keyboard for Your Win-Run Devices
keywords: Win Device Keyboard Toggle,Turnoff Win Keyboard,Win Run Keyboard OFF,Disable Win-Run Keyboards,Windows Input Shutdown,WinPC Keyboard Offline,Secure Win PC Keys
thumbnail: https://thmb.techidaily.com/cb70e57700d07e1f21d91f89b112cf1e7299f5606065c397aa28c9965f8c1a6d.jpg
---

## Technique to Turn Off Keyboard for Your Win-Run Devices

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
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

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

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
<li><a href="https://instagram-video-files.techidaily.com/updated-seamless-transfer-your-path-to-storing-instagram-videos-on-pc/"><u>[Updated] Seamless Transfer Your Path to Storing Instagram Videos on PC</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-which-is-better-for-vloggers-on-facebook-vertical-or-horizontal-for-2024/"><u>[Updated] Which Is Better for Vloggers on Facebook Vertical or Horizontal for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/boost-your-buzz-telegram-tactics-for-impactful-promotion/"><u>Boost Your Buzz Telegram Tactics for Impactful Promotion</u></a></li>
<li><a href="https://win11.techidaily.com/combating-valorant-communication-breakdowns-on-windows-78/"><u>Combating Valorant Communication Breakdowns on Windows 7/8</u></a></li>
<li><a href="https://extra-resources.techidaily.com/decoding-sound-sequence-confluence-crossfading-explained/"><u>Decoding Sound Sequence Confluence Crossfading Explained</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-obstacles-restoring-system-calls-on-win1111/"><u>Eliminating Obstacles: Restoring System Calls on Win11/11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-for-configuring-dns-in-windows-11/"><u>Expert Strategies for Configuring DNS in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-spontaneous-command-window-flashes/"><u>How to Stop Spontaneous Command Window Flashes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-vivo-y28-5g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Vivo Y28 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-unrealcefsubprocess-impact-on-system-resources/"><u>Lowering UnrealCEFSubprocess Impact on System Resources</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-windows-11-media-with-movie-maker-tools-for-2024/"><u>Mastering Windows 11 Media with Movie Maker Tools for 2024</u></a></li>
<li><a href="https://win-hacks.techidaily.com/preserve-your-data-while-refreshing-windows-11-a-step-by-step-guide/"><u>Preserve Your Data While Refreshing Windows 11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-top.techidaily.com/qnap-nas/"><u>QNAP NAS 迁移备份的无障碍指南：两种免费技巧</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/record-video-with-logitech-webcam-guide-for-2024/"><u>Record Video with Logitech Webcam [Guide] for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-absence-of-msvcr120dll-in-windows-environments/"><u>Resolving Absence of MSVCR120.DLL in Windows Environments</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210632727-9781959018025-runes/"><u>Runes | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-for-designing-custom-lock-patterns-in-windows-11/"><u>The Ultimate Technique for Designing Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-to-resolve-no-servers-found-navigating-apex-legends-windows-(156-chars/"><u>Top Tips to Resolve 'No Servers Found': Navigating Apex Legends Windows (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-microsoft-store-on-windows-10-and-11-with-x800704cf-error/"><u>Unblocking Microsoft Store on Windows 10 & 11 with X800704CF Error</u></a></li>
</ul></div>


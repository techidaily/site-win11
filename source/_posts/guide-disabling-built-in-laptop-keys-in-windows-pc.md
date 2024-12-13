---
title: "Guide: Disabling Built-In Laptop Keys in Windows PC"
date: 2024-12-12T02:07:43.063Z
updated: 2024-12-13T11:03:45.071Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Disabling Built-In Laptop Keys in Windows PC"
excerpt: "This Article Describes Guide: Disabling Built-In Laptop Keys in Windows PC"
keywords: Disable Laptop Keys Guide,Keyboard Shortcuts Removal,Windows Laptop Input Hacking,Built-In Laptop Control,Deactivate PC Keys,Windows Key Customization,Internal Laptop Button Management
thumbnail: https://thmb.techidaily.com/6b564cfcc68d7fa9fa2ebcc8ac34b00c6e2d610d2ee82b6185002beb469144e3.jpg
---

## Guide: Disabling Built-In Laptop Keys in Windows PC

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-effective-youtube-banners/"><u>[New] 2024 Approved The Ultimate Guide to Effective YouTube Banners</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-sound-capture-on-windows-10/"><u>[New] Unlocking Sound Capture on Windows 10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-cutting-edge-tech-mastering-dslr-macpc-for-social-media-broadcasts/"><u>[Updated] In 2024, Cutting Edge Tech Mastering DSLR, Mac/PC for Social Media Broadcasts</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-lgs-cinematic-revolution-the-31mu97-b-monitor-breakdown-review/"><u>2024 Approved LG’s Cinematic Revolution The 31MU97-B Monitor Breakdown Review</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/analyzing-both-contenders-a-detailed-look-at-apple-watch-s9-vs-fitbit-charge-6/"><u>Analyzing Both Contenders: A Detailed Look at Apple Watch S9 vs Fitbit Charge 6</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-realme-gt-neo-5-se-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Realme GT Neo 5 SE to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-update-dell-dell-d3100-printer-drivers-with-one-click/"><u>Download and Update DELL Dell D3100 Printer Drivers with One Click</u></a></li>
<li><a href="https://win11.techidaily.com/drive-into-the-future-audio-system-rejuvenation-for-windows-users/"><u>Drive Into the Future: Audio System Rejuvenation for Windows Users</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-essential-insights-for-crafting-youtube-intros-aplusb-methods/"><u>In 2024, Essential Insights for Crafting YouTube Intros A+B Methods</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-nubia-red-magic-9-proplus-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Nubia Red Magic 9 Pro+ Phones</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-exit-code-solutions-for-minecraft-players/"><u>Mastering Exit Code Solutions for Minecraft Players</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-made-simple-using-hotkeys-for-taskbar-efficiency/"><u>Minimizing Made Simple: Using Hotkeys for Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-of-affordable-windows-11-licenses/"><u>Secrets of Affordable Windows 11 Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-tasks-optimization-tips-for-winters/"><u>Streamline Windows Tasks: Optimization Tips for Winters</u></a></li>
<li><a href="https://win11.techidaily.com/tactical-steps-for-efficiently-converting-docx-files-to-pdfs-in-windows/"><u>Tactical Steps for Efficiently Converting DOCX Files to PDFs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-power-of-multitasking-understanding-the-need-for-16gb-windows-memory/"><u>The Power of Multitasking: Understanding the Need for 16GB Windows Memory</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-apps-to-transform-windows-clock-displays-into-interactive-screensavers/"><u>Top 5 Apps to Transform Windows Clock Displays Into Interactive Screensavers</u></a></li>
</ul></div>


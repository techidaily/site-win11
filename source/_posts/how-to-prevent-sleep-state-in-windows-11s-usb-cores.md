---
title: How to Prevent Sleep State in Windows 11'S USB Cores
date: 2024-06-25T11:28:26.040Z
updated: 2024-06-26T11:28:26.040Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Prevent Sleep State in Windows 11'S USB Cores
excerpt: This Article Describes How to Prevent Sleep State in Windows 11'S USB Cores
keywords: Preventing Sleep Mode WIN11,USB Cores Sleep Avoidance,Windows 11 USB Sleep Fix,Stop Windows Core Sleep,Win11 USB Power Saving Halt,Keep Win11 USB Awake,Disabling Core Sleep in Win11
thumbnail: https://thmb.techidaily.com/eae25c8cb1f012b237b4735a8d726d09f7b30b165b0175087b89427fe82c8e76.jpg
---

## How to Prevent Sleep State in Windows 11'S USB Cores

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/fixing-critical-winerror-upgrade-fault-0xc004f050/"><u>Fixing Critical WinError: Upgrade Fault #0XC004F050</u></a></li>
<li><a href="https://win11.techidaily.com/leading-painting-programs-beyond-the-procreate-window-experience/"><u>Leading Painting Programs Beyond the Procreate Window Experience</u></a></li>
<li><a href="https://win11.techidaily.com/decades-of-designs-the-windows-taskbars-journey/"><u>Decades of Designs: The Windows Taskbar's Journey</u></a></li>
<li><a href="https://win11.techidaily.com/the-financial-backbone-of-microsofts-windows-11/"><u>The Financial Backbone of Microsoft's Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-tablet-navigation-in-windows/"><u>Troubleshooting Non-Responsive Tablet Navigation in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-walkthrough-for-transferring-old-games-to-windows-gallery/"><u>A Walkthrough for Transferring Old Games to Windows Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-hurdles-for-epic-games/"><u>Overcoming Windows Login Hurdles for Epic Games</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-14-proipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock on Apple iPhone 14 Pro/iPad/iPod</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-handheld-gyro-stabilization-upgrade/"><u>[New] Handheld Gyro Stabilization Upgrade</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enriching-youtube-channels-amp-up-with-songs-for-2024/"><u>Enriching Youtube Channels  Amp up with Songs for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-best-10-animoji-apps-you-can-use-to-edit-animoji/"><u>2024 Approved Best 10 Animoji Apps You Can Use to Edit Animoji</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-infinix-hot-30i-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Infinix Hot 30i</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-how-to-screen-record-netflix-on-mac/"><u>[Updated] In 2024, How to Screen Record Netflix on Mac</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/affordable-pc-screen-recorder-comparisons/"><u>Affordable PC Screen Recorder Comparisons</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-infinix-hot-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-professional-video-editing-implementing-the-ken-burns-effect-in-camtasa/"><u>[New] In 2024, Professional Video Editing  Implementing the Ken Burns Effect in Camtasa</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
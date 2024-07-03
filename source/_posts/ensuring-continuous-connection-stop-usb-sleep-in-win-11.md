---
title: "Ensuring Continuous Connection: Stop USB Sleep in Win 11"
date: 2024-06-25T11:44:37.455Z
updated: 2024-06-26T11:44:37.455Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Ensuring Continuous Connection: Stop USB Sleep in Win 11"
excerpt: "This Article Describes Ensuring Continuous Connection: Stop USB Sleep in Win 11"
keywords: Win 11 NoSleep USB,USB Connection,Windows 11 Persist USB,Uninterrupted USB Use,Preventing USB Sleep,Win 11 USB Management,Stop USB Hibernate Mode
thumbnail: https://thmb.techidaily.com/4a4e8f7773cbb7ba2441b2203815dab13dab20d5c0f40b64cdaf24434f35396e.jpg
---

## Ensuring Continuous Connection: Stop USB Sleep in Win 11

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
<li><a href="https://win11.techidaily.com/tethering-tech-microsofts-vision-in-windows-11-phones/"><u>Tethering Tech: Microsoft's Vision in Windows 11 Phones</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-transformation-through-38-years/"><u>Taskbar Transformation Through 38 Years</u></a></li>
<li><a href="https://win11.techidaily.com/facilitating-regular-updates-toolbar-integration-in-the-windows-ui/"><u>Facilitating Regular Updates: Toolbar Integration in the Windows UI</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-cannot-determine-error-on-windows-computers/"><u>Overcoming Cannot Determine Error on Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-systemsettingsexe-failure-on-windows-11/"><u>Preventing SystemSettings.exe Failure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-ultimate-guide-fbx-free-gametime-tracking-for-2024/"><u>[New] The Ultimate Guide  FBX-Free Gametime Tracking for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-motorola-moto-g84-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Motorola Moto G84 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-find-your-perfect-vlog-title-best-free-name-generators/"><u>[New] 2024 Approved  Find Your Perfect Vlog Title - Best Free Name Generators</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-how-to-promote-your-youtube-channel-with-high-impact-showcase-techniques/"><u>In 2024, How to Promote Your YouTube Channel with High-Impact Showcase Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-make-a-cool-youtube-video-intro-in-imovie/"><u>[Updated] How to Make a Cool YouTube Video Intro in iMovie?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/addicted-to-boomerangs-mastering-ig-loop-artistry-for-2024/"><u>Addicted to Boomerangs  Mastering IG Loop Artistry for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-peek-at-all-shared-images-and-videos-in-chats/"><u>[Updated] In 2024, Peek at All Shared Images & Videos in Chats</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-masterful-descriptions-for-youtube-success-for-2024/"><u>[Updated] Masterful Descriptions for YouTube Success for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-tecno-spark-20-proplus-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Tecno Spark 20 Pro+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-your-youtube-presence-banners-for-gamers-for-2024/"><u>Elevate Your YouTube Presence  Banners for Gamers for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
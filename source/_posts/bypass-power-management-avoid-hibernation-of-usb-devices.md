---
title: "Bypass Power Management: Avoid Hibernation of USB Devices"
date: 2025-02-08T17:00:29.839Z
updated: 2025-02-16T00:48:23.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bypass Power Management: Avoid Hibernation of USB Devices"
excerpt: "This Article Describes Bypass Power Management: Avoid Hibernation of USB Devices"
keywords: USB Device Sleep Prevention,Bypass USB Hibernate,Manage Power for USB,USB Avoiding Sleep,Circuit Hibernation Evasion,USB Power Management Skip,USB Sleep Bypass Methods
thumbnail: https://thmb.techidaily.com/5ccaaabe736ffa61c5b51b0c29ef16cab934fcf393b5c97e5b701ae15078e141.jpg
---

## Bypass Power Management: Avoid Hibernation of USB Devices

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-escape-from-ennui-with-humor-top-20-funny-faces-in-social-media-jail/"><u>[Updated] In 2024, Escape From Ennui with Humor Top 20 Funny Faces in Social Media Jail</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-nocturnal-notions-for-iphone-photographers/"><u>[Updated] Nocturnal Notions for iPhone Photographers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-quickedit-videotool-for-2024/"><u>[Updated] QuickEdit VideoTool for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-3dr-solo-unveiling-the-single-user-experience/"><u>2024 Approved '3DR Solo' Unveiling the Single User Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/control-at-a-click-manage-windows-tray-using-keyboard-commands/"><u>Control at a Click: Manage Windows Tray Using Keyboard Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-persistent-0x800f0831-error-in-windows-10-and-11/"><u>How to Fix a Persistent 0X800f0831 Error in Windows 10 and 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-watch-hulu-outside-us-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/improve-system-visibility-add-file-space-explorer-to-windows-menu/"><u>Improve System Visibility: Add File Space Explorer to Window's Menu</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-7-leading-mac-video-player-options/"><u>In 2024, 7 Leading Mac Video Player Options</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-task-management-on-windows-os/"><u>Mastering Task Management on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/opening-act-emailcalendar-troubles-in-w11-os/"><u>Opening Act: Email/Calendar Troubles in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-sleep-settings-for-windows-pcs/"><u>Optimal Sleep Settings for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/proven-techniques-for-stylishly-inserting-app-icons-in-desktop/"><u>Proven Techniques for Stylishly Inserting App Icons in Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-stopping-exception-breakpoint-failure-in-windows/"><u>Solutions for Stopping Exception Breakpoint Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-10-safe-download-zones-for-windows-users/"><u>Top 10 Safe Download Zones for Windows Users</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ultimate-tutorial-capturing-screen-activity-on-iphone-11-using-the-best-techniques-by-movavi/"><u>Ultimate Tutorial: Capturing Screen Activity on iPhone 11 Using the Best Techniques by Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-user-management-for-windows-home-editions/"><u>Unlock Full User Management for Windows Home Editions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unpacking-the-features-of-fujitsu-scansnap-ix1600-the-desktop-scanner-that-elevates-productivity/"><u>Unpacking the Features of Fujitsu ScanSnap iX1600: The Desktop Scanner That Elevates Productivity</u></a></li>
</ul></div>


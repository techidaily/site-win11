---
title: Quick Fixes for USB Hibernate Prevention in Win 11
date: 2024-12-05T11:27:33.384Z
updated: 2024-12-07T09:08:09.729Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fixes for USB Hibernate Prevention in Win 11
excerpt: This Article Describes Quick Fixes for USB Hibernate Prevention in Win 11
keywords: Win 11 Hibernate,USB Freeze Prevent,Quick Fix Win PC,Hibernate Stop Guide,USB Safety Windows,Hibernation Control,Fast Win 11 Tips
thumbnail: https://thmb.techidaily.com/66474ad3ea796bd372c3cdc425ee2c1b3cee0dd881c03ccdd13266e6df3b21d0.jpg
---

## Quick Fixes for USB Hibernate Prevention in Win 11

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-videography-size-guide-ready/"><u>[Updated] Instagram Videography Size Guide - Ready</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-integrating-cg-centrals-luts-into-vfx-production-flows/"><u>2024 Approved Integrating CG Central's Luts Into VFX Production Flows</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-infinix-note-30-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-the-unexplainable-pink-screen-phenomenon/"><u>Conquering The Unexplainable Pink Screen Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-explorer-with-extra-paths/"><u>Enhancing File Explorer with Extra Paths</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-full-functionality-in-windows-audio-controls-missing/"><u>Ensuring Full Functionality in Windows: Audio Controls Missing</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-do-these-7-innovative-applications-utilize-gpt-4s-power/"><u>How Do These 7 Innovative Applications Utilize GPT- 4'S Power?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-display-sizing-in-win11-environment/"><u>Mastering the Art of Display Sizing in Win11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-desktop-with-a-three-column-widget-board-setup-in-win11/"><u>Maximize Your Desktop with a Three-Column Widget Board Setup in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-in-use-alerts-for-files-in-windows-11/"><u>Navigating 'In Use' Alerts for Files in Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-tech-gadgets-expert-reviews-from-toms-hardware/"><u>Navigating the World of Tech Gadgets: Expert Reviews From Tom's Hardware</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-best-free-video-hosting-platforms-for-monetizing-your-content/"><u>New 2024 Approved The Best Free Video Hosting Platforms for Monetizing Your Content</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-uninstalled-windows-utilities-and-extras/"><u>Recovering Uninstalled Windows Utilities and Extras</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-your-silent-tab-key-in-modern-windows/"><u>Resurrecting Your Silent Tab Key in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solving-steam-permission-faults-on-win11-system/"><u>Solving Steam Permission Faults on Win11 System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-into-tomorrow-revel-in-the-unveiling-of-apples-latest-handheld-masterpiece/"><u>Step Into Tomorrow: Revel in the Unveiling of Apple's Latest Handheld Masterpiece</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-10-recommended-screen-recording-software-for-enhanced-security/"><u>Top 10 Recommended Screen Recording Software for Enhanced Security</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/unlocking-the-power-of-titles-in-final-cut-pro-x-2023-update-for-2024/"><u>Unlocking the Power of Titles in Final Cut Pro X 2023 Update for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
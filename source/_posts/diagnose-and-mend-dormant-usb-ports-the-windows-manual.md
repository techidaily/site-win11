---
title: Diagnose & Mend Dormant USB Ports - The Windows Manual
date: 2024-06-25T10:27:07.513Z
updated: 2024-06-26T10:27:07.513Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diagnose & Mend Dormant USB Ports - The Windows Manual
excerpt: This Article Describes Diagnose & Mend Dormant USB Ports - The Windows Manual
keywords: USB Port Repair,Fixing Windows USB,Diagnosing USB Issues,USB Troubleshooting Guide,Mending USB Docks,Windows USB Port Fix,Revive Dormant USB
thumbnail: https://thmb.techidaily.com/5f19d12263b1224bd46b49560f2a184a0c0f8c0d56bb43f9e5c26e9a6768a6cd.jpg
---

## Diagnose & Mend Dormant USB Ports - The Windows Manual

 Have your PC or laptop USB ports stopped working? To fix this, you need to diagnose the root of the problem. Here's everything you need to know to quickly get your USB ports working again on any PC or laptop.

## Think Your USB Port Is Not Working? Test It

 Before proceeding, be sure that it is the port that is faulty, rather than the device you're connecting.

 To establish which is the problem, you'll need to know how to troubleshoot the USB port. This means knowing how to test the USB port.

 Start by connecting the device to another USB port. If it works, then the problem is the first port; if the device remains undetected, you have a faulty device. (Note that if you can't [reformat the USB drive](https://www.makeuseof.com/tag/format-usb-drive/), it will need replacing.)

![Have your USB ports stopped working?](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports.jpg)

 If there's a problem with your USB port, you'll notice it thanks to either of these things:

* The connected device fails to be detected
* Your operating system displays an error message relating to the device (removing and replacing the device might solve this)

 Either way, you should investigate the state of the USB port. Has it been damaged in any way? The safest way to find out is to shut down your PC or laptop.

 Next, look at the USB port. Is it clean and dust free? There's a chance that dirt, dust, and general detritus might have become embedded in the port. This can happen with laptop and desktop computers alike.

 Dust will reduce airflow, causing your system to overheat. It is particularly damaging to laptops, where [overheating can reduce performance in seconds](https://www.makeuseof.com/tag/fix-overheating-laptop/). To fix this, clean out the USB port with a can of compressed air. A vacuum cleaner might also prove handy here.

 Finally, grab a USB cable (or flash drive) and gently wiggle it around. If the drive is moving and feels loose---typically this will be up and down---then you have a problem.

## How to Fix a Broken USB Port on PC and Laptop

 We'll look at some software fixes in a moment, but first, what if the USB port is loose?

 USB ports are soldered to a board within your computer. This may be the motherboard but is typically a secondary printed circuit board (PCB). With regular use, ports can become movable, at times completely unattached.

 Often, this is down to the shape of the connected USB devices. While small Wi-Fi, Bluetooth, and even new USB flash memory are unlikely to put any significant strain on the port's physical connection, older "stick" memory drives are a different story. So are USB cables; their size and associated weight act as a sort of lever, contributing to USB ports working loose.

 If you suspect that your motherboard USB ports are not working, replacing them isn't easy. On a desktop computer, you may be able to find a replacement board that can be slotted in without too much effort. Want to know how to fix a USB port on a laptop? It's going to take a soldering iron.

 Of course, you could take this to an expert for repair, but there will be associated costs with this. If you want to do it yourself, make sure you [learn how to solder](http://www.makeuseof.com/tag/learn-solder-simple-tips-projects/). If you're not sure, check out the software fixes first.

## Can Restarting a Computer Fix Broken USB Ports?

 "Have you tried turning it off and back on again?"

 This old tech support standby is well-known for a reason: it works!

 With your unrecognized USB device correctly inserted into the suspect USB port, restart your computer. Once the operating system has rebooted, it should detect the USB device. If not, it's worth looking at the device in the Windows device manager.

## How to Check USB Ports on Windows 10 With Device Manager

 Device Manager is a system tool in Windows that lists devices attached to your computer. They’re grouped into categories, listed alphabetically, which enables you to quickly find the device you’re looking for.

 To check the status of your USB ports in Windows 10 and 11:

1. Right-click **Start** and select **Device Manager**  
![Open Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr.png)
2. **Browse the list for** **Universal Serial Bus controllers**
3. Expand this and look for the **USB Host Controller**(your device may have a longer title, but it will feature those three words)  
![Find the USB Host Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr-host-controller.png)
4. Right-click USB Host Controller (and any duplicates) and select **Uninstall**  
![Uninstall USB Host Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr-host-controller-uninstall.png)
5. Restart your computer
6. If no USB Host Controller is listed, click **Scan for hardware changes** on the toolbar

 If you're using a USB mouse and keyboard, it will be disabled while the USB Host Controllers are uninstalled.

## Have Power Settings Stopped Your USB Ports Working?

 If power management settings are overriding your USB controller, this will impact the detection of USB devices. It will appear that USB is not working, but in fact the operating system has put the device to sleep.

 This is particularly relevant if you think your laptop USB port is not working. However, if you're keen to reduce power usage, you might have set your Windows 10 desktop to low power.

**USB Selective Suspend** is a power saving setting that cuts power to the USB device, thereby reducing battery use.

 The feature usually works well, but at times makes it look as if there is a problem with your USB ports.

 Fix this by opening the Windows Control Panel and adjusting the settings.

1. Click **Start** and enter **control panel**
2. Select the corresponding result
3. Go to **Hardware and Sound > Power Options**
4. Here, find the selected plan and click **Change plan settings > Change advanced power settings**
5. Find **USB Settings** and expand to find **USB selecting suspend setting**
6. Change the drop-down menu to **Disabled**  
![Alter USB power settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/muo-windows-dead-usb-suspend-bg-2022.jpg)
7. Click **Apply** and **OK** to confirm
8. Finally, reboot your PC to ensure this change is applied

 You should find that any USB ports that were not working have now been fixed.

## USB Port Still Not Working? Reset the BIOS/UEFI Settings

 Your BIOS/UEFI exists to help provide a low-level interface between the hardware, software, and firmware on your computer. In other words, it helps all the major components of your PC combine and work together. In terms of specific functions, it helps you carry out the boot-up process, hardware initialization, system configuration, firmware updates, and so on.

 It's no wonder, then, that any tampered settings in your BIOS or UEFI will leave a variety of problems in its wake, including a malfunctioning USB port. So if you've reason to believe something has gone wrong with the BIOS/UEFI settings, we suggest resetting its settings.

 Check out [how to enter the BIOS settings on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) for instructions. If it was indeed a faulty BIOS/ UEFI stopping your USB port from working properly, then everything will be back to normal after a reset.

## You've Fixed Your Broken USB Port

 As you can see, you have several options for repairing an unresponsive USB port. In most cases, it won't be dead, and you'll be able to fix it.

 USB ports aren't the only potential weak spots on your computer. Looking after your hardware will reduce potential failures, and you can save a lot of money if you know how to test your PC for failing hardware.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-the-switch-for-regedit-on-win11/"><u>Mastering the Switch for RegEdit on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-faulty-windows-update-error/"><u>Correcting Faulty Windows Update Error</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computing-enable-hyper-v-in-windows-11-homes/"><u>Boost Your Computing: Enable Hyper-V in Windows 11 Homes</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-beginnings-executing-a-clean-windows-11-reinstall/"><u>Fresh Beginnings: Executing a Clean Windows 11 Reinstall</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-troubleshooting-winerror-0x80071a90/"><u>Understanding & Troubleshooting WinError 0X80071A90</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-the-not-responsive-window-software-problem/"><u>Mastery over the Not Responsive Window Software Problem</u></a></li>
<li><a href="https://extra-information.techidaily.com/capturing-the-best-on-iphone-8-techniques-for-pro-video-shoots-for-2024/"><u>Capturing the Best on iPhone  8 Techniques for Pro Video Shoots for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-peeling-back-layers-what-hides-beneath-each-snapchat-emoji/"><u>[Updated] 2024 Approved  Peeling Back Layers  What Hides Beneath Each Snapchat Emoji?</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-edit-your-way-to-success-iosandroid-apps-for-youtube-shorts/"><u>In 2024, Edit Your Way to Success  IOS/Android Apps for YouTube Shorts</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-effortless-ads-free-desktop-video-recorder/"><u>[New] In 2024, Effortless, Ads-Free Desktop Video Recorder</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713965430781-new-using-adobe-after-effects-as-a-pro-level-editing-platforms-demands-you-to-add-expressions-in-after-effects-if-youre-looking-for-the-solutions-on-after-e/"><u>New Using Adobe After Effects as a Pro-Level Editing Platforms Demands You to Add Expressions in After Effects. If Youre Looking for the Solutions on After Effects How to Add Expressions Then Weve Got You Covered. Learn More Here for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-essential-blueprint-for-monetary-success-on-tiktok-for-2024/"><u>[New] The Essential Blueprint for Monetary Success on TikTok for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/pro-video-practice-screen-record-on-various-devices/"><u>Pro Video Practice  Screen Record on Various Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/boosting-engagement-the-key-to-successful-youtuber-interactions/"><u>Boosting Engagement  The Key to Successful YouTuber Interactions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
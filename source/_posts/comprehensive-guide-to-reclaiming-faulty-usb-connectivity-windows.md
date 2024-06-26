---
title: Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows
date: 2024-06-25T10:04:36.920Z
updated: 2024-06-26T10:04:36.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows
excerpt: This Article Describes Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows
keywords: Fix USB on Windows,USB Error Solutions,Reconnect USB WINDOWS,USB Troubleshooting Guide,Restore Faulty USB,Win USB Connectivity Reclaim,Regain USB Functionality WIN
thumbnail: https://thmb.techidaily.com/b40abdafc85906cdf8c505af7da6e2b6de5b2e3882be4cc44ae2eb5b5e3f9c4a.jpg
---

## Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows

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
<li><a href="https://win11.techidaily.com/essential-tips-for-using-windows-11-snap-features/"><u>Essential Tips for Using Windows 11 Snap Features</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-copy-and-paste-on-chrome-edge-and-firefox-windows/"><u>Restoring Copy & Paste on Chrome, Edge, and Firefox (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-win-os-files-editable-again/"><u>How to Make Win OS Files Editable Again</u></a></li>
<li><a href="https://win11.techidaily.com/4-key-approaches-to-activate-a-dormant-windows-guard/"><u>4 Key Approaches to Activate a Dormant Windows Guard</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-windows-pricing-acquiring-top-product-keys/"><u>Triumph in Windows Pricing: Acquiring Top Product Keys</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-excessive-use-of-windows-module-installer/"><u>Overcoming Excessive Use of Windows Module Installer</u></a></li>
<li><a href="https://win11.techidaily.com/sound-superchargers-4-applications-boosting-windows-audio-capacity/"><u>Sound Superchargers: 4 Applications Boosting Windows' Audio Capacity</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-collective-windows-11-folder-making/"><u>Revolutionize File Management with Collective Windows 11 Folder Making</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mov-files-on-xiaomi-redmi-note-12-pro-4g-by-aiseesoft-video-converter-play-mov-on-android/"><u>How do you play .mov files on Xiaomi Redmi Note 12 Pro 4G ?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-convenient-methods-for-video-recording-on-youtube-for-2024/"><u>[New] Convenient Methods for Video Recording on YouTube for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-masterful-discord-ux-with-these-top-10-essentials/"><u>In 2024, Masterful Discord UX with These Top 10 Essentials</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-explore-top-rated-windows-10-video-capture-software-for-2024/"><u>[New] Explore Top-Rated Windows 10 Video Capture Software for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-premiere-experts-exceptional-instagram-highlight-craftsmen/"><u>[New] In 2024, Premiere Experts  Exceptional Instagram Highlight Craftsmen</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-comprehensive-guide-to-youtube-video-editing-tools/"><u>[New] In 2024, Comprehensive Guide to YouTube Video Editing Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-auditory-interface-excellence-for-podcasters/"><u>[Updated] Auditory Interface Excellence  For Podcasters</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/tech-savvy-tips-for-capturing-and-saving-mobile-snapshots-for-2024/"><u>Tech-Savvy Tips for Capturing and Saving Mobile Snapshots for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-edge-2023-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Edge 2023?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-vivo-y78-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Vivo Y78 5G FRP Locks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
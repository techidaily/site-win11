---
title: "Resurrecting Your PC's Dead Hub: A Windows Fix Guide"
date: 2024-07-13T10:55:33.614Z
updated: 2024-07-14T10:55:33.614Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resurrecting Your PC's Dead Hub: A Windows Fix Guide"
excerpt: "This Article Describes Resurrecting Your PC's Dead Hub: A Windows Fix Guide"
keywords: PC Revival Tips,Fix Hub Woes Win,ReBoot PC Cores,Resurrect Hub Errors,Hub Restoration Steps,Windows Hub Repair Guide,Hub Recovery Windows
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## Resurrecting Your PC's Dead Hub: A Windows Fix Guide

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/social-media-food-frenzy-10-hits/"><u>Social Media Food Frenzy  10 Hits</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-dns-flushing-in-modern-windows-os/"><u>Efficient Techniques for DNS Flushing in Modern Windows OS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-ensuring-privacy-when-documenting-whatsapp-voice-calls/"><u>[Updated] Ensuring Privacy When Documenting WhatsApp Voice Calls</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-updated-method-to-bypass-realme-11-pro-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Realme 11 Pro FRP</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-entry-points-to-troubled-boots-in-win-writable-steps/"><u>Eliminate Entry Points to Troubled Boots in Win' Writable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-sleep-state-in-windows-11s-usb-cores/"><u>How to Prevent Sleep State in Windows 11'S USB Cores</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-folder-context-menus-on-windows-11/"><u>Enhancing Folder Context Menus on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/echoes-of-the-past-amplifying-vintage-games-with-shaders/"><u>Echoes of the Past: Amplifying Vintage Games with Shaders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-monochrome-to-multicolor-grading-journey/"><u>[Updated] From Monochrome to Multicolor  Grading Journey</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-cannot-locate-gpeditmsc-windows-problems/"><u>Essential Fixes for Cannot Locate Gpedit.msc Windows Problems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-immediate-assist-feature-windows-11/"><u>How to Engage Immediate Assist Feature: Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/curated-list-of-top-10-song-tracks-for-enhancing-visual-narratives-for-2024/"><u>Curated List of Top 10 Song Tracks for Enhancing Visual Narratives for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-youtube-video-edits-with-adobe-premiere/"><u>[New] Mastering YouTube Video Edits with Adobe Premiere</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-oppo-find-x7-ultra-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Oppo Find X7 Ultra? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-essential-screen-recording-software-a-comprehensive-analysis/"><u>2024 Approved  Essential Screen Recording Software  A Comprehensive Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/launching-quake-mode-using-windows-terminal/"><u>Launching Quake Mode: Using Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/fix-steams-inaccessible-game-content-on-latest-windows-11/"><u>Fix Steam's Inaccessible Game Content on Latest Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-clickers-the-best-auto-click-cars-and-keys/"><u>Masterful Clickers: The Best Auto Click Cars & Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ditch-installation-struggles-preparations-before-vbox-on-pc/"><u>Ditch Installation Struggles: Preparations Before VBox on PC</u></a></li>
<li><a href="https://win11.techidaily.com/fix-inflexible-scrollbar-issue-in-microsoft-excel-2016/"><u>Fix Inflexible Scrollbar Issue in Microsoft Excel 2016</u></a></li>
<li><a href="https://some-guidance.techidaily.com/uncovering-key-differences-in-panoramic-and-vr-filmmaking-for-2024/"><u>Uncovering Key Differences in Panoramic & VR Filmmaking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-a-non-functional-printer-in-the-os-environment/"><u>Fixing a Non-Functional Printer in the OS Environment</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-colour-mismanagement-issues/"><u>Eliminate Windows Colour Mismanagement Issues</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-harvesting-happiness-the-ultimate-list-of-7-14-mods/"><u>[Updated] Harvesting Happiness  The Ultimate List of #7-14 Mods</u></a></li>
<li><a href="https://win11.techidaily.com/entrusting-administration-to-command-line/"><u>Entrusting Administration to Command Line</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-the-framework-for-high-quality-streaming-archiving/"><u>[Updated] 2024 Approved  The Framework for High-Quality Streaming Archiving</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-schedule-with-winning-windows-to-dos/"><u>Mastering Your Schedule with Winning Windows To-Dos</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-into-windows-booting-system-customization/"><u>Expert Insights Into Windows Booting System Customization</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ing-engaging-youtube-beginnings-two-methods/"><u>Crafting Engaging YouTube Beginnings  Two Methods</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overscan-in-windows-enhance-screen-fit/"><u>Fixing Overscan in Windows - Enhance Screen Fit</u></a></li>
<li><a href="https://win11.techidaily.com/file-sharing-mastery-constructing-python-servers-in-windows/"><u>File Sharing Mastery: Constructing Python Servers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-your-pcs-core-generating-and-reviewing-data/"><u>Deciphering Your PC’s Core: Generating & Reviewing Data</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-get-animated-28-video-to-gif-conversion-tools/"><u>New In 2024, Get Animated 28 Video to GIF Conversion Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-distinguished-makers-elite-instagram-highlight-constructors/"><u>[New] Distinguished Makers  Elite Instagram Highlight Constructors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-steps-to-efficient-zoom-meetings/"><u>Quick Steps to Efficient Zoom Meetings</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tune-sharing-compliance-instagram-ip-codex/"><u>[Updated] Tune-Sharing Compliance  Instagram IP Codex</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>Which Pokémon can Evolve with a Moon Stone For Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-steam-sync-problems/"><u>Deciphering and Fixing Steam Sync Problems</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-how-to-download-and-save-tiktok-videos-without-apple-writes/"><u>[New] How to Download and Save TikTok Videos without Apple' Writes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-has-been-blocked-by-your-system-administrator-error-in-windows/"><u>How to Fix This App Has Been Blocked by Your System Administrator Error in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/efficient-live-gaming-broadcasting-on-xbox/"><u>Efficient Live Gaming Broadcasting on Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-windows-files-writable-stop-read-only/"><u>How to Make Windows Files Writable: Stop Read-Only</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-top-tier-windows-10-screen-capture-programs-unveiled/"><u>2024 Approved  Top-Tier Windows 10 Screen Capture Programs Unveiled</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-oppo-find-x7-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Oppo Find X7</u></a></li>
</ul></div>

---
title: Enabling Functional State in Dead USB Ports, Win Edition
date: 2024-07-13T10:14:05.906Z
updated: 2024-07-14T10:14:05.906Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling Functional State in Dead USB Ports, Win Edition
excerpt: This Article Describes Enabling Functional State in Dead USB Ports, Win Edition
keywords: Dead USB Revival Windows,USB Resurrection Tech,Reactive USB Solutions,USB Recovery Protocol,Functional USB Restoration,Enabling Deactivated USBs,Reactivate USB in Win OS
thumbnail: https://thmb.techidaily.com/d8f58ce885808b79b129b3a2207409d6b0df7e72b7b5c93436a642cc91c8c39d.jpg
---

## Enabling Functional State in Dead USB Ports, Win Edition

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
<li><a href="https://win11.techidaily.com/does-the-geforce-experience-scan-fail-on-windows-heres-how-to-fix-it/"><u>Does the GeForce Experience Scan Fail on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-team-chats-on-windows-1110/"><u>Ensuring Smooth Team Chats on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/discover-why-your-windows-11-icons-are-diminishing/"><u>Discover Why Your Windows 11 Icons Are Diminishing</u></a></li>
<li><a href="https://win11.techidaily.com/outsmart-windows-delete-temp-files-without-fuss/"><u>Outsmart Windows: Delete Temp Files Without Fuss</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-blank-display-of-startup-items/"><u>Eradicating Blank Display of Startup Items</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unlocking-12-steps-fixing-hidden-fb-video-issues/"><u>In 2024, Unlocking 12 Steps  Fixing Hidden FB Video Issues</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-non-loading-drivers-functional-on-windows-11/"><u>How to Make Non-Loading Drivers Functional on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-insta-vid-techniques-scaling-videos-to-perfect-size-in-fcpx/"><u>[Updated] Insta-Vid Techniques  Scaling Videos to Perfect Size in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/hosting-multiple-oses-linux-vm-inside-hyper-v-on-a-windows-machine/"><u>Hosting Multiple OSes: Linux VM Inside Hyper-V on a Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-image-navigation-using-file-explorer-windows/"><u>Effortless Image Navigation Using File Explorer Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-update-schedules-setting-active-periods-windows-11/"><u>Mastering Update Schedules: Setting Active Periods Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launch-failures-fixing-windows-speech-recognition/"><u>Overcoming Launch Failures: Fixing Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/opera-stuck-swift-solutions-for-a-smooth-windows-patch/"><u>Opera Stuck? Swift Solutions for a Smooth Windows Patch</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-techniques-for-reality-warp-imagery/"><u>In 2024, Techniques for Reality Warp Imagery</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-teachers-choice-top-recording-applications/"><u>[Updated] 2024 Approved  Teachers' Choice  Top Recording Applications</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unveiling-irecorders-top-screen-capabilities/"><u>Unveiling iRecorder's Top Screen Capabilities</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-vivo-y78-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Vivo Y78 5G Lock Screen Password?</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsoft-family-safetys-core-functions/"><u>Decoding Microsoft Family Safety's Core Functions</u></a></li>
<li><a href="https://win11.techidaily.com/make-ms-word-defaultly-use-reading-pane-for-email-attachments-no-editing/"><u>Make MS Word Defaultly Use Reading Pane for Email Attachments, No Editing</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-alternatives-how-to-access-imessage-on-windows/"><u>Exploring Alternatives: How to Access iMessage on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/christmas-edition-enhance-windows-11/"><u>Christmas Edition: Enhance Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-vivo-s17-pro-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/foster-fluidity-in-your-playtime-by-addressing-launcher-issues/"><u>Foster Fluidity in Your Playtime by Addressing Launcher Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-app-hiccup-geforce-x0001/"><u>Overcoming Windows 11 App Hiccup: GeForce X0001</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-disappearances-in-system-navigator/"><u>Eradicating Disappearances in System Navigator</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-how-to-execute-system-file-checker-sfc/"><u>Command Line: How to Execute System File Checker (SFC)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-discovering-if-muted-on-snapstreak/"><u>In 2024, Discovering If Muted on Snapstreak</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-fixes-for-stuck-game-resolutions-in-windows/"><u>Insightful Fixes for Stuck Game Resolutions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-voice-typing-failure-in-windows-11-error-code-0x80049dd3/"><u>Fixing Voice Typing Failure in Windows 11 (Error Code: 0X80049DD3)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-windows-11-logins-restoration/"><u>Mastering Quick Windows 11 Logins Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-monitor-settings-in-latest-os-version/"><u>Fine-Tune Monitor Settings in Latest OS Version</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-windows-11-efficiency-with-these-5-reliability-checks/"><u>Maximize Your Windows 11 Efficiency with These 5 Reliability Checks</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mac-users-mastering-mp3-conversion-from-youtube/"><u>2024 Approved  Mac Users  Mastering MP3 Conversion From YouTube</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/craft-stellar-channels-best-10-apps-for-artistic-banner-design-for-2024/"><u>Craft Stellar Channels  Best 10 Apps for Artistic Banner Design for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-melody-match-masters-unveiling-the-hottest-tunes-on-web-platforms/"><u>New In 2024, Melody Match Masters Unveiling the Hottest Tunes on Web Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-onedrive-error-def5-woes/"><u>Navigating Through Windows 11'S Onedrive Error DEF5 Woes</u></a></li>
<li><a href="https://win11.techidaily.com/non-light-no-problem-master-five-cures-for-backlit-keyboard-failure/"><u>Non-Light, No Problem: Master Five Cures for Backlit Keyboard Failure</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-overcome-common-flaws-in-windows-applications/"><u>Essential Tips to Overcome Common Flaws in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-unlock-the-power-of-slow-mo-a-kapwing-video-editing-tutorial/"><u>Updated 2024 Approved Unlock the Power of Slow Mo A Kapwing Video Editing Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/nine-keys-to-release-verification-holds-during-windows-update/"><u>Nine Keys to Release Verification Holds During Windows Update</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-watch-without-limits-15plus-free-apps-to-save-your-favorite-content/"><u>[Updated] In 2024, Watch Without Limits  15+ Free Apps to Save Your Favorite Content</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win-rpc-failures-five-must-try-fixes/"><u>Navigating Win RPC Failures: Five Must-Try Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-rescue-deskanywhere-on-win11/"><u>Essential Tips to Rescue DeskAnywhere on Win11</u></a></li>
</ul></div>

---
title: "Fixes for Crashing Virtual Machines: BSOD Remedy Win11"
date: 2024-12-16T17:10:36.398Z
updated: 2024-12-22T16:09:08.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixes for Crashing Virtual Machines: BSOD Remedy Win11"
excerpt: "This Article Describes Fixes for Crashing Virtual Machines: BSOD Remedy Win11"
keywords: Win11 VM Fix,VM Boot Repair,BSOD Win11 Solution,Stable VM Windows,Win11 Crash Remedy,Virtual Machine Recovery,Stop WM Errors
thumbnail: https://thmb.techidaily.com/3d0b2d16ee1d6e6a1474c3b5739a00253bf279f4294e6c37548bb9b82e10821e.jpg
---

## Fixes for Crashing Virtual Machines: BSOD Remedy Win11

 VMware Workstation Player is among the best virtualization software available today. You can create virtual machines and install operating systems on them. Virtual machines save you the trouble of wiping your hard disk to try out an operating system. However, it is not the only use case of third-party hypervisors like VMware.

 And although virtual machines typically run smoothly, you might occasionally experience a BSOD error while launching or using a virtual machine in a VMware workstation player. So, we'll list the potential reasons for BSODs in VMware along with multiple methods to resolve the issue.

## Reasons for VMware BSOD Error on Windows 11

Here are a few possible reasons for the VMware BSOD error on Windows:

1. Native virtualization services like WHP are running alongside VMware.
2. You are using an outdated version of Windows.
3. VMware is conflicting with another application or background service.
4. The virtual machine is eating up more resources than the system can spare.

## How to Fix VMware BSOD Error on Windows 11

 Now, you know the possible reasons for the BSOD error while using VMware. Try out the following methods to fix the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Restart VMware

 Before moving on to more complex fixes, restart the VMware program on your Windows 11 computer. Close the program and terminate all its processes from the Task Manager. Now, relaunch VMware and power on a virtual machine. Keep the machine running for some time, and keep an eye out for BSOD errors.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Update VMware

 An outdated version of VMware can act finicky with the new system updates. So, you must update it to apply fixes released by developers for newfound bugs. Here's how to do it:

1. Launch VMware on your system.
2. Navigate to the top left section and click on the Player button.
3. Then, go to**Help > Software Updates** .
4. Click on the**Check for Updates** button. Wait for the utility to search for the latest available update, if any.
5. If an update is available, click on the**Download and install** button. Wait for the update to install.  
![Update VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-vmware.jpg)
6. [UAC](https://www.makeuseof.com/tag/user-account-control-windows-10/) will pop up. Click on the**Yes** button to begin the update installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Close the VMware program. Follow the on-screen prompts to install the update on your system.
8. Click on the**Finish** button after the installation completes successfully.
9. Restart your system. Launch VMware and start a virtual machine. Check if the program produces a BSOD error.

### 3\. Disable Hyper-V and Other Windows Features

 Third-party hypervisors fail to launch or work properly when Hyper-V or other virtualization features such as Windows Hypervisor Platform, Virtual Machine Platform, and more. You must turn off all these features before using VMware on your Windows 11 system.

Repeat the following steps to disable Windows features:

1. Press**Win + R** to launch the Run command box. Type**appwiz.cpl** and press the enter key.
2. Programs and Features utility will launch. Click on the**Turn Windows features on or off** option.
3. Scroll down and uncheck the**Hyper-V** feature in the list. Similarly, uncheck the**Windows Hypervisor Platform** ,**Virtual Machine Platform** , and**Windows Subsystem for Linux** .  
![Disable Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-windows-features.jpg)
4. Windows will uninstall all these features from your system and auto-restart it to apply changes. It will take a while to remove all these features.
5. Sign in and launch VMware again. Now, power on a virtual machine and check if a BSOD error pops up.

### 4\. Reconfigure Virtual Machine Resources

 If your virtual machine crashes and throws a BSOD error, it is likely consuming more resources than your system can spare. Ideally, you should not devote more than 50 percent of any hardware (CPU, RAM, or disk space) to a virtual machine. Always leave enough for the host system to run smoothly and then devote the rest to the virtual machine.

Here's how to reconfigure virtual machine resources in VMware.

1. Launch VMware on your system. Click on any virtual machine in the list and select the**edit virtual machine settings** option.
2. Under the hardware tab, click on the**Memory** option. Adjust the slider to the recommended memory size.
3. Move to the Processors option and expand the**number of processor cores** dropdown list. Select**four** and click on the**OK** button.  
![Reconfigure virtual machine resources](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reconfigure-virtual-machine-resources.jpg)
4. These hardware settings are different for every operating system. Make sure to allocate only the bare minimum resources specified by the operating system developers.
5. Now, power on the virtual machine and use it for some time. If you still encounter a BSOD error, move to the next method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 5\. Update Windows

 An outdated version of Windows can contain bugs and may not sit well with new apps and software. So, update your Windows system using the settings app. Repeat the following steps to update Windows:

1. Press**Win + I** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to the top right section and click on the Windows Update icon.
3. Click on the**Check for updates** button. Wait for the utility to search for new updates for your device.  
![Update Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-windows.jpg)
4. Download and install the update.**Restart** your system to apply the update.
5. Launch VMware on your system and start a virtual machine.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 6\. Perform a Clean Boot

 A background program could be interfering with the nominal working of VMware. You must perform and clean boot to isolate and identify the root cause of trouble. Clean boot will start Windows with basic drivers and programs.

To clean boot your Windows PC, repeat the following steps:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**msconfig** and press the enter key. The system configuration utility will launch.
3. Switch to the**Services** tab and click on the**Hide all Microsoft services** option.
4. Click on the**Disable all** button and then switch to the startup tab. Click on the Open Task Manager option.
5. Task Manager will launch. Right-click on a startup program and select the**Disable** option. Repeat this action for all programs.  
![Perform a Clean Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/perform-a-clean-boot-1.jpg)
6. Close Task Manager and click on the**OK** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Restart your system and launch VMware. If it runs fine, open System Configuration, enable some services, and try again.
8. Identify and uninstall the troublemaker program or keep its services disabled on startup.

### 7\. Use a Different ISO File

 A corrupt ISO file can also cause a BSOD error while installing the operating system on a virtual machine. If you are using an old ISO file that is possibly corrupt, download its most recent version and add it to the virtual machine.

 Start the virtual machine and boot from that ISO file using the boot menu options. Begin the installation process and check if the process completes without an issue.

### 8\. Use a Different Hypervisor

 The last resort is to use a different hypervisor program for the time being. Try a level-1 hypervisor like Hyper-V or use level-2 hypervisors like VirtualBox or QEMU. Report the issue to the VMware developers and wait for them to release a bug fix for the BSOD issue.

 VirtualBox had a similar issue when it wasn't compatible with Windows 11\. It took Oracle some time to release a compatible version, forcing users to find a temporary alternative while waiting for the fix.

## VMware BSOD Error Won't Bother You Anymore

 VMware can easily run all the popular operating systems inside a virtual machine. But the BSOD error renders the program unusable. Try out the basic troubleshooting methods and update VMware and Windows. After that, disable Windows Hyper-V and other virtualization features and reconfigure the virtual machine resources.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-a-filmmakers-essentials-the-quintessential-5-camera-strategies/"><u>[New] A Filmmaker's Essentials The Quintessential 5 Camera Strategies</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-how-to-record-lectures-on-mac/"><u>[Updated] 2024 Approved How to Record Lectures on Mac</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/flavorful-journeys-on-tiktoks-culinary-map/"><u>Flavorful Journeys on TikTok's Culinary Map</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-past-not-valid-updates-in-winos/"><u>How to Get Past Not Valid Updates in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-lengthen-the-wait-before-closing-managing-running-tasks-on-windows-10/"><u>How to Lengthen the Wait Before Closing: Managing Running Tasks on Windows 10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-the-activation-lock-on-your-ipad-and-iphone-14-plus-without-apple-account-by-drfone-ios/"><u>How to Remove the Activation Lock On your iPad and iPhone 14 Plus without Apple Account</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-journeying-through-yesteryears-facebook-posts-on-mobilelaptop/"><u>In 2024, Journeying Through Yesteryear's Facebook Posts on Mobile/Laptop</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-infinix-note-30-pro-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Infinix Note 30 Pro</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-startup-success-on-youtubing-free-beginner-courses/"><u>In 2024, Startup Success on YouTubing Free Beginner Courses</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-snipping-tool-not-working-here-are-9-ways-to-fix-it/"><u>Is Your Snipping Tool Not Working? Here Are 9 Ways to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-settings-in-windows-11/"><u>Mastering the Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-fix-windows-rdp-black-screens/"><u>Methods to Fix Windows RDP Black Screens</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/next-level-gaming-with-dell-alienware-aurora-r9-the-cutting-edge-pc-review/"><u>Next-Level Gaming with Dell Alienware Aurora R9 - The Cutting Edge PC Review</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-keeping-the-taskbar-ready-while-maximized/"><u>Strategies for Keeping the Taskbar Ready While Maximized</u></a></li>
<li><a href="https://win11.techidaily.com/taming-windows-irq-issues-for-audio-devices/"><u>Taming Windows' IRQ Issues for Audio Devices</u></a></li>
<li><a href="https://win11.techidaily.com/time-tested-techniques-bringing-back-lost-windows-time-services/"><u>Time-Tested Techniques: Bringing Back Lost Windows Time Services</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-asus-rog-phone-8-pro-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Asus ROG Phone 8 Pro FRP Bypass</u></a></li>
</ul></div>


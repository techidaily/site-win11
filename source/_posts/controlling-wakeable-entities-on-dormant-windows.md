---
title: Controlling Wakeable Entities on Dormant Windows
date: 2024-06-25T10:07:56.249Z
updated: 2024-06-26T10:07:56.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Wakeable Entities on Dormant Windows
excerpt: This Article Describes Controlling Wakeable Entities on Dormant Windows
keywords: Wake Entity Control,Window Wake Prevention,Dormant Windows Management,Entities in Sleep Mode,Secure Windows Operations,Preventing Active Windows,Managing Wakeable Systems
thumbnail: https://thmb.techidaily.com/c88c76635d5e0629581e4fd4108916cee892ed1d438b3013953d19ca906db797.jpg
---

## Controlling Wakeable Entities on Dormant Windows

 When not in use, putting your Windows PC to sleep is an excellent way to preserve its battery life. You can wake your computer at any time by simply wiggling the mouse, pressing the power button, or pressing a key on your keyboard.

 Windows gives you complete control over devices that can wake your computer from a sleep state. In this guide, we will discuss how you can manage those devices.

## How to Check Which Devices Are Capable of Waking Your Windows PC From Sleep Mode

 Not every device connected to your system can wake Windows from sleep mode. You can use Command Prompt or Windows PowerShell to determine which of your devices supports waking the computer.

1. Press**Win + S** to open the search menu.
2. Type in**Windows PowerShell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to view a list of devices on your system that can wake Windows from any sleep state.  
`powercfg -devicequery wake_from_any`  
![Devices That Can Wake Windows From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-That-Can-Wake-Windows-From-Sleep-Mode.jpg)

 On this list, you'll see devices like your keyboard, mouse, network adapter, and more.

## How to Check Which Devices Are Allowed to Wake Your Windows PC From Sleep Mode

 Command Prompt or PowerShell can also tell you which devices are permitted to wake your Windows PC from sleep mode. Here's how to find out.

1. [Open Command Prompt or Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command and press**Enter** to view a list of devices that are allowed to wake your computer from sleep mode.  
`powercfg -devicequery wake_armed`  
![Devices Are Allowed to Wake Your Windows PC From Sleep Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Devices-Are-Allowed-to-Wake-Your-Windows-PC-From-Sleep-Mode.jpg)

## How to Find Out What Woke Your Windows PC From Sleep Mode

 Many times, you may find that your Windows computer wakes from sleep mode on its own. Often, it's one of the connected devices or processes that causes your computer to wake up. Windows can tell you exactly what woke your computer from sleep mode.

1. Press**Win + R** to open the Run dialog.
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to[launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
3. Input the following command and press**Enter** .  
`powercfg -lastwake`  
![Check What Woke Windows From Sleep](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-What-Woke-Windows-From-Sleep.jpg)

 Once you run the above command, Windows will tell you which device or process woke your computer from sleep mode.

 If you see something like**Wake History Count - 0** , it means that Windows doesn't have a record of wake history. This can happen if you've recently rebooted your computer.

## How to Allow or Deny a Device Permission to Wake Your Windows PC From Sleep Mode

 Once you know which devices are waking up your computer without your consent, you can take the necessary steps to prevent them from doing so.

To allow or deny a device permission to wake your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Device Manager** from the list.
3. Locate the device you want to configure. Right-click on it and select**Properties** .
4. In the Properties window, switch to the**Power Management** tab.
5. Check or uncheck the**Allow this device to wake the computer** checkbox to allow or disallow the permission.
6. Click**OK** to save the changes.  
![Allow or Disallow Device to Wake Computer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Allow-or-Disallow-Device-to-Wake-Computer-on-Windows.jpg)

 You can repeat the above steps to configure power management settings for more devices if you want.

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on[how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

## Manage Your Computer’s Sleep

 Now you know what devices can wake your computer from a sleep state and how to prevent them from doing so. That said, putting your computer in sleep mode may not always be the best option for your laptop. Sometimes, it’s better to shut it down completely.


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
<li><a href="https://win11.techidaily.com/fixing-power-spike-issues-during-multiplayer-adventures/"><u>Fixing Power Spike Issues During Multiplayer Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/max-out-your-games-on-windows-the-amd-optimization-guide/"><u>Max Out Your Games on Windows: The AMD Optimization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-absence-of-printmanagement-on-your-system/"><u>Remedying the Absence of 'Printmanagement' On Your System</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-aural-outputs-with-win-compatible-audacity/"><u>Overhauling Windows' Aural Outputs with Win-Compatible Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-secondary-antivirus-without-defenders-hindrance/"><u>Tips for Integrating Secondary Antivirus Without Defender’s Hindrance</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-classics-windows-11s-pathway-to-photos-folder/"><u>Connecting Classics: Windows 11'S Pathway to Photos Folder</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-pc-data-access-everythingapp-utilization/"><u>Rapid PC Data Access: EverythingApp Utilization</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-poco-f5-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-screensavvy-comprehensive-free-recording-software-for-everyone-for-2024/"><u>[New] ScreenSavvy  Comprehensive, Free Recording Software for Everyone for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/perfecting-your-facebook-video-cover-tips-and-tricks/"><u>Perfecting Your Facebook Video Cover Tips and Tricks</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/1713954143701-new-in-2024-how-to-livestream-zoom-on-facebook/"><u>New In 2024, | How to Livestream Zoom on Facebook?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-dos-and-donts-of-recording-in-zoom-work-environments/"><u>[New] In 2024, The Do's and Don’ts of Recording in Zoom Work Environments</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-best-selling-ubuno-video-recorders-for-linux-users/"><u>In 2024, Best-Selling UbuNo Video Recorders for Linux Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unraveling-periscopes-mystique-is-it-free-and-how-to-signup/"><u>[Updated] Unraveling Periscope's Mystique  Is It Free and How to Signup?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-asus-rog-phone-8-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Asus ROG Phone 8 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-livescreen-capture-halt-guidebook/"><u>[New] In 2024, LiveScreen Capture Halt Guidebook</u></a></li>
</ul></div>

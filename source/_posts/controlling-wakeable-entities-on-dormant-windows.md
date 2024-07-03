---
title: Controlling Wakeable Entities on Dormant Windows
date: 2024-06-25T11:30:37.423Z
updated: 2024-06-26T11:30:37.423Z
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
<li><a href="https://win11.techidaily.com/is-the-outlook-app-not-syncing-on-windows-heres-how-to-fix-it/"><u>Is the Outlook App Not Syncing on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-cannot-open-file-problems-in-win1110/"><u>Mastering the Art of Fixing 'Cannot Open File' Problems in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-error-code-0x0000011b/"><u>Resolving Windows 11 Error Code: 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cleanup-close-multiple-windows-with-one-click/"><u>Quick Cleanup: Close Multiple Windows with One Click</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-your-windows-pcs-character-map-functionality-succeeds/"><u>Ensuring Your Windows PC's Character Map Functionality Succeeds</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-with-ms-store-a-stepwise-approach-to-windows-pcs/"><u>Re-Engaging with MS Store: A Stepwise Approach to Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-winerror-with-code-0x8019/"><u>Resolving WinError with Code 0X8019</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://win11.techidaily.com/windows-blue-screen-analysis-key-to-troubleshooting/"><u>Windows Blue Screen Analysis: Key to Troubleshooting</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-streaming-titans-clash-streamlabs-versus-obs-in-the-arena-for-2024/"><u>[Updated] Streaming Titans Clash  Streamlabs versus OBS in the Arena for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-art-of-synchronizing-video-to-music-techniques-for-2024/"><u>New The Art of Synchronizing Video to Music Techniques for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-can-creators-earn-from-product-video-reviews/"><u>In 2024, Can Creators Earn From Product Video Reviews?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-how-to-counter-facebooks-instantaneous-deletion-of-videos/"><u>[Updated] In 2024, How to Counter Facebook's Instantaneous Deletion of Videos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-compile-of-top-15-gopro-stabilizers-and-mounts/"><u>[New] Compile of Top 15 GoPro Stabilizers & Mounts</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-introduction-to-av1-encoding-techniques/"><u>[Updated] Introduction to AV1 Encoding Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-effortless-live-chat-setup-via-whatsapp-browser-on-your-laptop/"><u>2024 Approved  Effortless Live Chat Setup via WhatsApp Browser on Your Laptop</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-tricks-for-smooth-animation-with-movie-maker/"><u>[Updated] In 2024, Tricks for Smooth Animation with Movie Maker</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-mastering-tiktok-installation-on-your-macbook-for-2024/"><u>[New] Mastering TikTok Installation on Your MacBook for 2024</u></a></li>
</ul></div>

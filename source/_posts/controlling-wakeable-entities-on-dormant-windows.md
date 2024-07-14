---
title: Controlling Wakeable Entities on Dormant Windows
date: 2024-07-13T10:13:58.325Z
updated: 2024-07-14T10:13:58.325Z
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
2. Type**cmd** in the box and press**Ctrl + Shift + Enter** to [launch Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
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

 Aside from your devices, your network connections, scheduled tasks, and background wake timers can also wake Windows from sleep mode. If you want to stop that from happening, check our guide on [how to prevent your Windows computer from waking up randomly](https://www.makeuseof.com/tag/stop-windows-computer-randomly-waking/) .

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
<li><a href="https://win11.techidaily.com/why-gamers-should-trust-windows-vision-and-performance/"><u>Why Gamers Should Trust Windows' Vision and Performance</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oneplus-ace-3-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your OnePlus Ace 3 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/debugging-made-easy-essential-windows-fixers-guide/"><u>Debugging Made Easy: Essential Windows Fixers Guide</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-rectify-hiberflattening-windows/"><u>Easy Steps to Rectify HiberFlattening Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-discover-the-hottest-tiktok-goodies-top-30-from-amazon/"><u>[New] 2024 Approved  Discover the Hottest TikTok Goodies – Top 30 From Amazon</u></a></li>
<li><a href="https://win11.techidaily.com/exemplary-protection-in-a-new-era-selecting-four-for-windows-11/"><u>Exemplary Protection in a New Era: Selecting Four for Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-complete-protocol-never-revisit-your-tiktok-account/"><u>2024 Approved  Complete Protocol  Never Revisit Your TikTok Account</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-e8024002e-for-updates/"><u>Bypassing Windows Error E:8024002E for Updates</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pcs-safety-with-these-7-password-generators/"><u>Boost Your PC's Safety with These 7 Password Generators</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-extract-subtitles-for-free-top-10-tools-reviewed/"><u>[New] 2024 Approved  Extract Subtitles for Free  Top 10 Tools Reviewed</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-asus-rog-phone-8-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-webp-saving-chrome-image-format-change-guide/"><u>Win Over WebP Saving: Chrome Image Format Change Guide</u></a></li>
<li><a href="https://win11.techidaily.com/batch-terminate-programs-in-windows-effortlessly/"><u>Batch Terminate Programs in Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/1719222893625-eradicate-failed-capture-on-windows-devices-today/"><u>Eradicate Failed Capture on Windows Devices Today!</u></a></li>
<li><a href="https://win11.techidaily.com/determining-optimal-nvidia-driver-gamingstudio-edition/"><u>Determining Optimal Nvidia Driver: Gaming/Studio Edition</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-0x8004def5-onedrive-hurdle-on-win11/"><u>Eradicating 0X8004DEF5 Onedrive Hurdle on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-optimize-cpu-load-from-tiworkerexe/"><u>Approaches to Optimize CPU Load From TiWorker.exe</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-windows-11s-misaligned-html-emails/"><u>Deciphering and Dismantling Windows 11'S Misaligned HTML Emails</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-edge-and-keep-your-system-clean-w11/"><u>Eliminate Edge and Keep Your System Clean (W11)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-vivo-v30-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Vivo V30 FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-choices-activating-filters-on-windows-11-files/"><u>Streamline Choices: Activating Filters on Windows 11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-write-unavailable-issue-in-windows/"><u>Eradicating 'Write Unavailable' Issue in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-spectrum-screens-a-new-film-language/"><u>In 2024, Spectrum Screens  A New Film Language</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-exception-breaking-point-achieved-in-windows/"><u>Troubleshooting Error: Exception Breaking Point Achieved in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-seamlessly-posting-online-content-to-ig-storypost/"><u>[Updated] 2024 Approved  Seamlessly Posting Online Content to IG Story/Post</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-directx-protocols-for-your-gaming-system/"><u>Effortless DirectX Protocols for Your Gaming System</u></a></li>
<li><a href="https://win11.techidaily.com/to-keep-or-not-to-delete-the-case-of-pagefilesys/"><u>To Keep or Not to Delete: The Case of Pagefile.sys</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-leading-animals-in-play-androids-favorites-list-for-2024/"><u>[Updated] Leading Animals in Play  Android's Favorites List for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-exploring-the-limits-full-potential-of-screenflow-v4-on-macos/"><u>[Updated] In 2024, Exploring the Limits  Full Potential of ScreenFlow v4 on macOS</u></a></li>
<li><a href="https://win11.techidaily.com/auto-shutdown-hacks-for-idle-pcs-running-w10w11/"><u>Auto Shutdown Hacks for Idle PCs Running W10/W11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-download-facebook-audio-as-mp3-top-online-converters/"><u>2024 Approved Download Facebook Audio as MP3 Top Online Converters</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-learn-to-keep-unwanted-suggestions-away-from-ig/"><u>[Updated] In 2024, Learn to Keep Unwanted Suggestions Away From IG</u></a></li>
<li><a href="https://win11.techidaily.com/determine-your-pcs-wattage-usage-on-windows-system/"><u>Determine Your PC's Wattage Usage on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-obstacles-when-installing-java/"><u>Addressing Common Obstacles When Installing Java</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-guide-reactivate-disabled-slack-notifications/"><u>Win 11 Guide: Reactivate Disabled Slack Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-mail-issues-with-html-enhanced-emails/"><u>Troubleshooting Windows 11 Mail Issues with HTML-Enhanced Emails</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-game-bar-errors-due-to-weak-hardware/"><u>Fixing Game Bar Errors Due to Weak Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-use-estimating-windows-app-size/"><u>Efficient Use: Estimating Windows App Size</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
</ul></div>

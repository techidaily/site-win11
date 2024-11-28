---
title: Masking Wi-Fi Presence on Windows Systems
date: 2024-11-25T16:01:57.610Z
updated: 2024-11-27T18:58:12.893Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Masking Wi-Fi Presence on Windows Systems
excerpt: This Article Describes Masking Wi-Fi Presence on Windows Systems
keywords: Hide Wifi Signal,Stealthy Wifi,Invisible Wifi,Wifi Camouflage,Concealed Wi-Fi,Obfuscate Wi-Fi,Masked Network
thumbnail: https://thmb.techidaily.com/4c2f1c5599abfece009f925c2828de86667e5982a128d746578608e8851ede9e.jpg
---

## Masking Wi-Fi Presence on Windows Systems

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/updated-high-definition-streaming-app-your-ultimate-video-choice-12-channels-for-2024/"><u>[Updated] High Definition Streaming App - Your Ultimate Video Choice (12 Channels) for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/cut-to-the-chase-download-fb-videos-as-mp4/"><u>Cut to the Chase - Download FB Videos as MP4</u></a></li>
<li><a href="https://win11.techidaily.com/empower-your-win11-mastering-powertoys-setup/"><u>Empower Your Win11: Mastering PowerToys Setup</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-new-policy-remove-overtly-politicalreligious-info/"><u>Facebook's New Policy: Remove Overtly Political/Religious Info</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-transformative-zooms-for-snapchat-photos-and-videos/"><u>In 2024, Transformative Zooms for Snapchat Photos & Videos</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcome-startup-issues-effective-strategies-to-repair-ntldr-is-absent-and-related-mistakes/"><u>Overcome Startup Issues: Effective Strategies to Repair 'NTLDR Is Absent' & Related Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-windows-team-video-sharing/"><u>Reclaiming Windows Team Video Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-nonworking-tools-for-windows-maintenenasive-troubleshooters/"><u>Repairing Nonworking Tools for Windows Maintenenasive Troubleshooters</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-copy-and-paste-on-common-browsers-for-pcs/"><u>Resetting Copy & Paste on Common Browsers for PCs</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/singing-machine-sml385btbk-karaoke-review-the-easiest-and-most-colorful-karaoke-machine-to-plug-and-play/"><u>Singing Machine SML385BTBK Karaoke Review: The Easiest and Most Colorful Karaoke Machine to Plug and Play</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-users-how-will-losing-taskbar-chat-shape-your-user-experience/"><u>Windows 11 Users: How Will Losing Taskbar Chat Shape Your User Experience?</u></a></li>
</ul></div>


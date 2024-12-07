---
title: Guidance to Fix Erratic Time Estimate Indicator on Win 11 OS
date: 2024-12-01T06:48:26.333Z
updated: 2024-12-06T16:42:03.794Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidance to Fix Erratic Time Estimate Indicator on Win 11 OS
excerpt: This Article Describes Guidance to Fix Erratic Time Estimate Indicator on Win 11 OS
keywords: Win 11 Time Estimate Issue,Fixing Win 11 Estimator,Win 11 Estimate Glitch,Correct Windows 11 Timer Error,Win 11 Estimation Correction,Troubleshoot Win 11 Time Delay,Resolve Erratic W11 Estimator
thumbnail: https://thmb.techidaily.com/2c97ca9c03a4b90ac808b47e7a1e56e2bf5202bf8ec2d002abc5e5f18888aaa6.jpg
---

## Guidance to Fix Erratic Time Estimate Indicator on Win 11 OS

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.

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
<li><a href="https://fox-access.techidaily.com/new-in-2024-revolutionize-your-online-presence-with-these-eight-strategies/"><u>[New] In 2024, Revolutionize Your Online Presence with These Eight Strategies</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-vivo-x100-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-maximizing-android-video-brilliance-simple-steps/"><u>2024 Approved Maximizing Android Video Brilliance Simple Steps</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-quintessential-queries-a-highlight-of-reddits-best-threads/"><u>2024 Approved The Quintessential Queries A Highlight of Reddit's Best Threads</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722077254658-chat-with-powerful-ai-like-never-before-chatgpt-on-android-now/"><u>Chat With Powerful AI Like Never Before – ChatGPT on Android Now!</u></a></li>
<li><a href="https://win11.techidaily.com/effective-ways-to-eliminate-apple-device-images-not-uploading-in-windows/"><u>Effective Ways to Eliminate Apple Device Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-msresourceappnametext-error-in-windows-11/"><u>Eliminating 'MsResource:AppName/Text Error' In Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-xbox-audio-with-windows-support/"><u>Enhancing Xbox Audio with Windows' Support</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-new-pc-up-and-running-free-usb-c-windows-11-drivers/"><u>Get Your New PC Up and Running: Free USB-C Windows 11 Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/inserting-windows-1011-menu-feature-for-software-alerts/"><u>Inserting Windows 10/11 Menu Feature for Software Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/learn-and-master-window-11s-taskbar-search-box-quickly/"><u>Learn and Master Window 11’S Taskbar Search Box Quickly</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-mobile-conversations-with-voicegpt-your-ultimate-guide-for-android-users/"><u>Mastering Mobile Conversations with VoiceGPT – Your Ultimate Guide for Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resolve-secure-boot-non-activation-on-windows-systems/"><u>Methods to Resolve Secure Boot Non-Activation on Windows Systems</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-your-way-to-a-new-place-the-ultimate-list-of-apartment-search-tools-online/"><u>Navigate Your Way to a New Place: The Ultimate List of Apartment Search Tools Online</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-restricted-windows-security-rules/"><u>Rectifying Restricted Windows Security Rules</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/seamless-sharing-with-windows-11-display-phone-pictures-on-your-desktop/"><u>Seamless Sharing with Windows 11 - Display Phone Pictures on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-streams-on-pc/"><u>Troubleshooting Steam Streams on PC</u></a></li>
</ul></div>


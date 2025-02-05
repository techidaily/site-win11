---
title: How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
date: 2025-01-29T20:36:09.902Z
updated: 2025-02-04T05:48:07.507Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
excerpt: This Article Describes How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
keywords: Metro Connection Settings Windows 11,Wi-Fi Metering Control Windows,Enable/Disable Wi-Fi Metering Windows,Windows 11 Metered Mode Adjustment,Manage Metered Wi-Fi in Windows 11,Windows 11 Set Metered Connection,Wi-Fi Data Usage Management Win11
thumbnail: https://thmb.techidaily.com/e68430bcb106e10e6ed671e16682f01d022f0799c626556c343ddc595fa9cde5.jpg
---

## How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagrams-power-in-motion-crafting-a-comprehensive-video-plan/"><u>[New] In 2024, Instagram's Power in Motion Crafting a Comprehensive Video Plan</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-safe-purchase-high-quality-tiktok-followers/"><u>[New] In 2024, Safe Purchase High-Quality TikTok Followers</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723013291963-bypassing-the-stubborn-loading-screen-in-far-cry-5-solutions-inside/"><u>Bypassing the Stubborn Loading Screen in Far Cry 5 – Solutions Inside!</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-msvcr110dll-deficit-in-windows/"><u>Eliminating the msvcr110.dll Deficit in Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ensuring-continuous-gameplay-with-quality-ups-units-an-in-depth-look-at-apcs-gaming-models/"><u>Ensuring Continuous Gameplay with Quality UPS Units: An In-Depth Look at APC's Gaming Models</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-fixing-bluetooth-connection-problems-in-win-11/"><u>Essential Guide: Fixing Bluetooth Connection Problems in Win 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-skincare-revolution-the-best-apps-for-your-phone/"><u>In 2024, Skincare Revolution The Best Apps for Your Phone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Vivo Y36i? | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/mastering-close-up-techniques-with-videoleap/"><u>Mastering Close-Up Techniques with Videoleap</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pixel-perfect-video-modifier/"><u>Pixel-Perfect Video Modifier</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-lost-data-curing-transfer-failures-on-windows-usbs/"><u>Preventing Lost Data: Curing Transfer Failures on Windows USBs</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-workspace-individual-monitors-in-windows-11/"><u>Tailoring Your Workspace: Individual Monitors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-oculus-quest-to-windows-pc-vr-setup/"><u>Transitioning Oculus Quest to Windows PC VR Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-potential-of-your-pc-learning-system-restore-in-windows/"><u>Unlock the Potential of Your PC: Learning System Restore in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-windows-rediscovered-secrets-to-restoring-hidden-panes-6-ways/"><u>Unseen Windows Rediscovered: Secrets to Restoring Hidden Panes (6 Ways)</u></a></li>
</ul></div>


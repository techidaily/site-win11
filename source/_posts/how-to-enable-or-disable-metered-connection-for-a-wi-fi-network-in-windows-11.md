---
title: How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
date: 2024-12-08T20:06:57.177Z
updated: 2024-12-12T16:25:38.980Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-keep-your-snaps-alive-strategies-for-longevity/"><u>[New] Keep Your Snaps Alive – Strategies for Longevity</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-visual-storytelling-crafting-impressive-imovie-video-intros/"><u>[New] Visual Storytelling Crafting Impressive iMovie Video Intros</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-smiling-screens-top-15-funny-mobile-photography-tools/"><u>[Updated] 2024 Approved Smiling Screens Top 15 Funny Mobile Photography Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-audio-enabled-mac-video-recorder/"><u>[Updated] In 2024, Audio-Enabled Mac Video Recorder</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-pixelated-prowess-celebrating-the-best-shooter-classics/"><u>[Updated] Pixelated Prowess Celebrating the Best Shooter Classics</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-from-finish-to-start-the-art-of-negative-playback-on-instagram/"><u>2024 Approved From Finish to Start The Art of Negative-Playback on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/a-novices-guide-to-windows-11-sound-capture/"><u>A Novice's Guide to Windows 11 Sound Capture</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discovering-greatness-a-complete-analysis-of-the-2019-tcl-50s425-the-ultimate-blend-of-quality-and-affordability-in-a-50-4k-roku-setup/"><u>Discovering Greatness: A Complete Analysis of the 2019 TCL 50S425 - The Ultimate Blend of Quality and Affordability in a 50 4K Roku Setup</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-windows-hard-drive-sustainably/"><u>Expanding Windows Hard Drive Sustainably</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ideal-websites-for-extracting-text-visual-upgrades-for-2024/"><u>Ideal Websites for Extracting Text Visual Upgrades for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-lustrous-frameworks-structuring-illumination-in-film/"><u>In 2024, Lustrous Frameworks Structuring Illumination in Film</u></a></li>
<li><a href="https://win11.techidaily.com/lightening-windows-11-startup-latency-tips-for-a-speedy-launch/"><u>Lightening Windows 11 Startup Latency – Tips for a Speedy Launch</u></a></li>
<li><a href="https://win11.techidaily.com/secure-edge-with-microsofts-advanced-protection-technology-aguard-on-windows-11/"><u>Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win-error-no-access-to-network-paths/"><u>Solving WIN Error: No Access to Network Paths</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-tutorial-getting-fortnite-up-and-running-on-android-phones/"><u>Step-by-Step Tutorial: Getting Fortnite Up and Running on Android Phones</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-file-explorer-on-win11-effective-repair-methods/"><u>Trouble with File Explorer on Win11? Effective Repair Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-interruptexception-solution-for-win11/"><u>Unveiling INTERRUPT_EXCEPTION Solution for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-excel-is-running-slow-on-windows/"><u>What to Do if Excel Is Running Slow on Windows</u></a></li>
</ul></div>


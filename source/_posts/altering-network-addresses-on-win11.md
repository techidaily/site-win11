---
title: Altering Network Addresses on Win11
date: 2024-07-13T09:45:53.130Z
updated: 2024-07-14T09:45:53.130Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Network Addresses on Win11
excerpt: This Article Describes Altering Network Addresses on Win11
keywords: Win11 IP Change,Win11 Router Update,Network Adjustment Win11,Win11 MAC Alteration,Windows IP Address Editing,Win11 Gateway Reconfiguration,Win11 DHCP Modification
thumbnail: https://thmb.techidaily.com/cd939fa7a6d55f7872fb793de3dd6a0a1cf42f10f319881184a8db53e138fd0a.jpg
---

## Altering Network Addresses on Win11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the [Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.


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
<li><a href="https://win11.techidaily.com/navigating-past-fatal-js-error-in-discord-on-modern-windows-11/"><u>Navigating Past Fatal JS Error in Discord on Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-losses-commit-to-daily-windows-data-archiving/"><u>Avoid Losses: Commit to Daily Windows Data Archiving</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/hot-off-the-tiktok-menu-top-dishes-and-challenges-for-2024/"><u>Hot Off the TikTok Menu  Top Dishes & Challenges for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-multi-selection-activating-windows-11s-checkboxes/"><u>Efficient Multi-Selection: Activating Windows 11'S Checkboxes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-address-dying-function-keys-adjusting-screen-brightness/"><u>Solutions to Address Dying Function Keys Adjusting Screen Brightness</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-dead-iphone-15-pro-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover data from dead iPhone 15 Pro Max | Stellar</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/experts-choice-the-best-windows-pc-screen-recorders-for-2024/"><u>Expert's Choice  The Best Windows PC Screen Recorders for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-microsoft-store-crash-0x80073d26/"><u>Strategies to Overcome Microsoft Store Crash: 0X80073D26</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pajama-plots-performed-a-critical-study-of-bedtime-storytelling-vids/"><u>2024 Approved  Pajama Plots Performed  A Critical Study of Bedtime Storytelling Vids</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-instructions-for-setting-up-dolby-atmos-in-windows-1111/"><u>In-Depth Instructions for Setting Up Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-file-transfer-integrating-zip-into-image-files-win/"><u>The Unseen File Transfer: Integrating ZIP Into Image Files (WIN)</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-and-thrive-harnessing-the-power-of-wintoys/"><u>Optimize and Thrive: Harnessing the Power of Wintoys</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-7-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 7 Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-store-error-0x800704cf-in-win11/"><u>Troubleshooting Store Error 0X800704CF in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-shadows-tackling-wacatacbml-on-microsoft-windows/"><u>Unveiling the Shadows: Tackling Wacatac.B!ml on Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-deleted-characters-a-guide-for-windows-users/"><u>Restoring Deleted Characters: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/averting-steam-library-write-errors-on-modern-windows-pcs/"><u>Averting Steam Library Write Errors on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-page-denial-challenges/"><u>Overcoming Windows Page Denial Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-drive-detect-and-delete-null-space-in-windows/"><u>Streamline Your Drive: Detect and Delete Null Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-frequent-rainmeter-setbacks-an-easy-guide/"><u>Decoding and Fixing Frequent Rainmeter Setbacks: An Easy Guide</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-screen-display-defeating-windows-overscan/"><u>Optimize Full-Screen Display: Defeating Windows Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-dynamic-walls-in-windows-11-for-enhanced-aesthetics/"><u>The Art of Dynamic Walls in Windows 11 for Enhanced Aesthetics</u></a></li>
<li><a href="https://extra-skills.techidaily.com/maximizing-podcast-discoverability-through-effective-seo-for-2024/"><u>Maximizing Podcast Discoverability Through Effective SEO for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-here-is-a-review-of-the-best-security-camera-software-and-every-single-one-has-a-free-option-technique-questions-are-answered-as-well/"><u>New Here Is a Review of the Best Security Camera Software, and Every Single One Has a Free Option. Technique Questions Are Answered as Well</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-stream-and-share-successfully-with-fb-integration/"><u>[Updated] In 2024, Stream & Share Successfully with FB Integration</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-easy-way-to-modify-iphone-photo-dimensions-for-2024/"><u>The Easy Way to Modify iPhone Photo Dimensions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/master-window-11s-icon-arrangement/"><u>Master Window 11'S Icon Arrangement</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-efficiently-start-and-schedule-a-zoom-call-on-any-android-device/"><u>[New] 2024 Approved  Efficiently Start & Schedule a Zoom Call on Any Android Device</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-bring-your-favorite-tunes-to-the-social-network-iphoneandroid/"><u>In 2024, Bring Your Favorite Tunes to the Social Network (iPhone/Android)</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-14-plus-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 14 Plus Data From iTunes | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-cutting-edge-tools-for-youtube-content-capture/"><u>[New] Cutting-Edge Tools for YouTube Content Capture</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-mastering-music-creation-the-6-best-free-daw-choices-for-newcomers-for-2024/"><u>Updated Mastering Music Creation The 6 Best Free DAW Choices for Newcomers for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-no-budget-no-problem-the-finest-free-voice-alterer-for-valorant-players/"><u>In 2024, No Budget? No Problem! The Finest Free Voice Alterer for Valorant Players</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oneplus-ace-2-pro-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to OnePlus Ace 2 Pro FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-dormant-slack-alerts-on-modern-windows-pcs/"><u>Reinstating Dormant Slack Alerts on Modern Windows PCs</u></a></li>
</ul></div>

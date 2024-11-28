---
title: Control Data Cost Monitoring on Your Wi-Fi Network with Win11
date: 2024-11-20T17:30:56.913Z
updated: 2024-11-27T17:06:03.470Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Control Data Cost Monitoring on Your Wi-Fi Network with Win11
excerpt: This Article Describes Control Data Cost Monitoring on Your Wi-Fi Network with Win11
keywords: Wi-Fi Cost Tracking,Wi-Fi Expense Control,Win11 Wi-Fi Monitoring,Wi-Fi Data Analysis,Wi-Fi Network Savings,Win11 Security Audit,Wi-Fi Management Tools
thumbnail: https://thmb.techidaily.com/359889cca1fac1d0cab50a3e170aa122469e4b901fffff3859c0a0ef7a4f048d.jpg
---

## Control Data Cost Monitoring on Your Wi-Fi Network with Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-blog.techidaily.com/n-2024-strategies-for-soaring-up-the-youtube-ranks-list/"><u>[New] In 2024, Strategies for Soaring Up the YouTube Ranks List</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-exclusive-hub-free-images-galore-across-the-web/"><u>[Updated] 2024 Approved Exclusive Hub Free Images Galore Across the Web</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-pioneering-avengers-the-marvellous-world-builders/"><u>2024 Approved Pioneering Avengers The Marvellous World-Builders</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/a-visual-treat-discover-these-14-text-animation-delights/"><u>A Visual Treat Discover These 14 Text Animation Delights</u></a></li>
<li><a href="https://facebook.techidaily.com/breaking-down-the-fbctas-effect-on-consumers/"><u>Breaking Down the FBCTA's Effect on Consumers</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-cannot-create-window-errors-on-windows/"><u>Decoding the 'Cannot Create' Window Errors on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-the-silent-microphone-problem-in-your-corsair-hs50-setup/"><u>Diagnosing and Fixing the Silent Microphone Problem in Your Corsair HS50 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/isolating-and-remedying-solo-sideheadphone-glitches-in-win/"><u>Isolating and Remedying Solo Sideheadphone Glitches in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-search-configurations-reset/"><u>Mastering Windows 11 Search Configurations Reset</u></a></li>
<li><a href="https://tech-revival.techidaily.com/paving-pathways-for-the-future-top-5-advances-in-ai-tech-landscape/"><u>Paving Pathways for the Future: Top 5 Advances in AI Tech Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsoft-store-errors-the-quick-fix-for-0x80072efd/"><u>Tackling Microsoft Store Errors: The Quick Fix for 0X80072EFD</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-complete-handbook-of-gopro-time-lapse-photography-excellence/"><u>The Complete Handbook of GoPro Time-Lapse Photography Excellence</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/twitters-viral-victory-hot-talk-highlights/"><u>Twitter's Viral Victory Hot Talk Highlights</u></a></li>
</ul></div>


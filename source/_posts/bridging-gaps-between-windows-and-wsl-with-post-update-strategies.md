---
title: Bridging Gaps Between Windows & WSL With Post-Update Strategies
date: 2025-01-28T08:43:46.669Z
updated: 2025-02-03T23:48:43.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bridging Gaps Between Windows & WSL With Post-Update Strategies
excerpt: This Article Describes Bridging Gaps Between Windows & WSL With Post-Update Strategies
keywords: Windows WSL Update,WSL Compatibility,WSL Bridge Tech,Windows Linux Integration,System Post-Updates,OS WSL Sync,Strategy for Updates
thumbnail: https://thmb.techidaily.com/3e134df3d1e30ff21305cf90a72d9a508b70a320e15fdc18733cb673b02e8a47.jpg
---

## Bridging Gaps Between Windows & WSL With Post-Update Strategies

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://extra-lessons.techidaily.com/new-color-depth-explored-windows-hdri-for-editors/"><u>[New] Color Depth Explored Windows HDRI for Editors</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/lv-file-symphony-creating-a-single-youtube-playlist-for-2024/"><u>[New] FLV File Symphony Creating a Single YouTube Playlist for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-maximizing-subscribers-youtubes-expansion-blueprint/"><u>[New] In 2024, Maximizing Subscribers YouTube's Expansion Blueprint</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-techniques-in-producing-accelerated-video-narratives/"><u>[Updated] In 2024, Techniques in Producing Accelerated Video Narratives</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-youtube-copyrights-demystified-understanding-and-managing-strikes/"><u>[Updated] In 2024, YouTube Copyrights Demystified Understanding and Managing Strikes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-videotwit2mp4-simple-conversion-for-2024/"><u>[Updated] VideoTwit2MP4 Simple Conversion for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/become-an-audio-trailblazer-exclusive-vocal-change-techniques-in-free-fire-free-for-2024/"><u>Become an Audio Trailblazer – Exclusive Vocal Change Techniques in Free Fire (Free) for 2024</u></a></li>
<li><a href="https://win-bits.techidaily.com/enabling-windows-defender-a-step-by-step-guide-by-yl-computing/"><u>Enabling Windows Defender: A Step-by-Step Guide by YL Computing</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-integrating-audio-tracks-with-avi-files-seamlessly/"><u>Quick Guide: Integrating Audio Tracks with AVI Files Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-transforming-avi-videos-into-gifs-with-speed/"><u>Quick Guide: Transforming AVI Videos Into GIFs with Speed</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-on-effortlessly-transforming-snd-tracks-into-mp3-files/"><u>Quick Tips on Effortlessly Transforming SND Tracks Into MP3 Files</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-conversion-a-step-by-step-guide-to-transferring-dvds-onto-your-iphone-7-or-7-plus/"><u>Seamless Conversion: A Step-by-Step Guide to Transferring DVDs Onto Your iPhone 7 or 7 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-adding-the-ghost-add-on-to-your-kodi-version-20-and-19-setup/"><u>Step-by-Step Guide: Adding the Ghost Add-On to Your Kodi (Version 20 & 19) Setup</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-videos-into-mov-format/"><u>Step-by-Step Guide: Converting Videos Into MOV Format</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-downloading-karaoke-tracks-from-youtube-without-restrictions/"><u>Step-by-Step Guide: Downloading Karaoke Tracks From YouTube Without Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-process-for-clipping-movies-at-15-second-markers-the-ultimate-tutorial/"><u>Step-by-Step Process for Clipping Movies at 15-Second Markers: The Ultimate Tutorial</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-rated-zmi-powerpack-20000-examined-the-perfect-compact-power-device-reviewed/"><u>Top-Rated ZMI PowerPack 20000 Examined: The Perfect Compact Power Device Reviewed</u></a></li>
</ul></div>


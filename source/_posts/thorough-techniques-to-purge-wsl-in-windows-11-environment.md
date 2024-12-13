---
title: Thorough Techniques to Purge WSL in Windows 11 Environment
date: 2024-12-07T18:59:11.528Z
updated: 2024-12-12T16:47:11.679Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Thorough Techniques to Purge WSL in Windows 11 Environment
excerpt: This Article Describes Thorough Techniques to Purge WSL in Windows 11 Environment
keywords: WSL Cleanup Guide,Windows 11 WSL Purging,WSL Reset Tips,Disable WSL (Windows),Remove WSL Windows 11,Optimize WSL Performance,Efficient WSL Clearance
thumbnail: https://thmb.techidaily.com/dbece127b3474bfee03fecc83648c4194241691bdbde80d7fc24eae5256f2a38.jpg
---

## Thorough Techniques to Purge WSL in Windows 11 Environment

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-harvesting-stills-from-moving-images-on-windows/"><u>[New] 2024 Approved Harvesting Stills From Moving Images on Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-transform-your-snaps-with-cutting-edge-filter-techniques/"><u>[New] 2024 Approved Transform Your Snaps with Cutting-Edge Filter Techniques</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-to-use-your-recordings-for-a-seamless-live-experience-on-fb-for-2024/"><u>[Updated] How to Use Your Recordings for a Seamless Live Experience on FB for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-elevate-your-meetings-with-zooms-filter-capabilities/"><u>[Updated] In 2024, Elevate Your Meetings with Zoom's Filter Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-seamless-experience-with-enhanced-window-11-menus/"><u>Crafting a Seamless Experience with Enhanced Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-11s-secrets-to-mac-retrieval/"><u>Decoding Windows 11'S Secrets to MAC Retrieval</u></a></li>
<li><a href="https://win-amazing.techidaily.com/direct-download-for-updated-nvidia-rtx-2080-graphics-card-software-supported-by-windows-1078/"><u>Direct Download for Updated NVIDIA RTX 2080 Graphics Card Software – Supported by Windows 10/7/8</u></a></li>
<li><a href="https://win11.techidaily.com/getting-out-the-windows-store-in-win11/"><u>Getting Out the Windows Store in Win11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-vivo-y200e-5g-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Vivo Y200e 5G FRP In 3 Different Ways</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harnessing-the-power-of-zooms-video-features-on-youtube-platform/"><u>In 2024, Harnessing the Power of Zoom's Video Features on YouTube Platform</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/no-internet-full-fun-best-offline-gaming-on-mobile-devices-for-2024/"><u>No Internet, Full Fun Best Offline Gaming on Mobile Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-snipkey-shortcut-woes/"><u>Restoring Functionality: SnipKey Shortcut Woes</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-upgrade-for-your-computers-double-click-rate/"><u>Speedy Upgrade for Your Computer's Double Click Rate</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/steps-to-clear-out-your-youtube-watch-later-collection/"><u>Steps to Clear Out Your YouTube Watch Later Collection</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-turn-off-microsofts-assistant/"><u>Strategies to Turn Off Microsoft's Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-excel-freeze-up-during-slide-viewing/"><u>Tackle Windows Excel Freeze-Up During Slide Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-secrets-of-windows-camera-a-fixers-manual/"><u>Unlock the Secrets of Windows Camera: A Fixer’s Manual</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
---
title: Effective Techniques for Disabling WSL
date: 2024-12-07T05:44:10.549Z
updated: 2024-12-13T08:13:19.107Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Techniques for Disabling WSL
excerpt: This Article Describes Effective Techniques for Disabling WSL
keywords: Windows Subsystem Limit,Control WSL Accessibility,Configure WSL Settings,Turn Off WSL Feature,Disable WSL Command,Restrict WSL Functionality,Opt-Out of WSL Service
thumbnail: https://thmb.techidaily.com/c572e526911ff13873cfea2690ee252e9ff11a89ced90101624b46320eed1514.jpg
---

## Effective Techniques for Disabling WSL

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-get-more-from-tiny-screens-top-6-youtube-shorts-downloader-apps-for-2024/"><u>[New] Get More From Tiny Screens Top 6 YouTube Shorts Downloader Apps for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-mastering-hd-video-the-best-android-players-for-2024/"><u>[Updated] Mastering HD Video The Best Android Players for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-motorola-moto-g84-5g-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola Moto G84 5G Unlock Without Password</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-frozen-epic-launcher-on-your-windows-11-machine/"><u>Eliminate Frozen Epic Launcher on Your Windows 11 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-disk-needs-format-message-in-windows/"><u>How to Clear Disk Needs Format Message in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-error-0x80073d26-from-your-microsoft-store/"><u>How to Eliminate Error 0X80073D26 From Your Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-strategies-solve-clipchamp-issues-on-win11-platforms/"><u>Masterful Strategies: Solve ClipChamp Issues on Win11 Platforms</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-ultimate-backward-beat-playlist/"><u>New 2024 Approved The Ultimate Backward Beat Playlist</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-the-401-unauthorized-access-issue-a-step-by-step-guide/"><u>Resolving the 401 Unauthorized Access Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-your-windows-1011-apps-with-restart-techniques/"><u>Revamping Your Windows 10/11 Apps with Restart Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-alternatives-to-the-windows-snipping-tool/"><u>The 5 Best Alternatives to the Windows Snipping Tool</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/the-art-of-saving-and-enjoying-animated-gifs-on-your-iphone-for-2024/"><u>The Art of Saving and Enjoying Animated GIFs on Your iPhone for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-ultimate-issues-essential-fixes-for-dev-errors-in-call-of-duty-modern-warfare-and-warzone-titles/"><u>Troubleshooting Ultimate Issues: Essential Fixes for Dev Errors in Call of Duty Modern Warfare & Warzone Titles</u></a></li>
</ul></div>


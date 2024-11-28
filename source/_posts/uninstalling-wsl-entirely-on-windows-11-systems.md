---
title: Uninstalling WSL Entirely on Windows 11 Systems
date: 2024-11-22T18:59:18.913Z
updated: 2024-11-28T02:36:39.996Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling WSL Entirely on Windows 11 Systems
excerpt: This Article Describes Uninstalling WSL Entirely on Windows 11 Systems
keywords: Uninstall WSL,Windows 11 Removal,Remove Linux Subsystem,WSL Delete Process,Disable WSL Feature,WSL Offsetting Windows,WSL Uninstall Guide
thumbnail: https://thmb.techidaily.com/8823459ab6574b19c976d6905c67df41ee5da35193b7ba8be663bba21950e5e8.jpg
---

## Uninstalling WSL Entirely on Windows 11 Systems

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-facebook-film-download-highlights-no-8/"><u>[New] 2024 Approved Facebook Film Download Highlights - No. 8</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-complete-review-for-dji-inspire-1-for-2024/"><u>[New] Complete Review for DJI Inspire 1 for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-behind-the-scenes-of-youtube-income-generation/"><u>[Updated] 2024 Approved Behind the Scenes of YouTube Income Generation</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-elevating-storytelling-merging-narration-into-videos/"><u>[Updated] 2024 Approved Elevating Storytelling Merging Narration Into Videos</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-unlock-content-potential-with-the-right-vimeo-membership-choice/"><u>[Updated] In 2024, Unlock Content Potential with the Right Vimeo Membership Choice</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-navigating-the-maze-of-tiktoks-bulk-video-transfer/"><u>2024 Approved Navigating the Maze of TikTok's Bulk Video Transfer</u></a></li>
<li><a href="https://win11.techidaily.com/compact-connoisseurs-panasonic-choice/"><u>Compact Connoisseur's Panasonic Choice</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-tackling-cc-issues-with-ease-in-window-10/"><u>Guide to Tackling CC Issues with Ease in Window 10</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-from-ideation-to-implementation-a-comprehensive-approach-for-quality-edu-videos/"><u>In 2024, From Ideation to Implementation A Comprehensive Approach for Quality Edu-Videos</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-taskbar-organization-in-win-11/"><u>Mastering Taskbar Organization in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-network-key-inconsistencies-5-steps-for-windows-users/"><u>Navigating Through Network Key Inconsistencies: 5 Steps for Windows Users</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-ultimate-guide-to-mp4-to-mp3-apps-for-ios-and-android/"><u>New 2024 Approved The Ultimate Guide to MP4 to MP3 Apps for iOS and Android</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-limitations-without-moving-to-newest-os/"><u>Overcoming Limitations without Moving to Newest OS</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-files-adopt-the-minimalist-way-with-windows-explorer/"><u>Tidy Up Files: Adopt the Minimalist Way with Windows Explorer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/tricks-for-recording-online-discussions-easily-for-2024/"><u>Tricks for Recording Online Discussions Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-up-surplus-graphics-from-windows-search/"><u>Trimming Up Surplus Graphics From Windows Search</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-guide-solving-your-iphones-silent-alarm-issue/"><u>Ultimate Guide: Solving Your iPhone's Silent Alarm Issue</u></a></li>
<li><a href="https://win11.techidaily.com/uncommon-processes-a-task-manager-tale/"><u>Uncommon Processes: A Task Manager Tale</u></a></li>
<li><a href="https://win11.techidaily.com/unveil-top-6-trackers-to-master-your-computerinas-windows-domain/"><u>Unveil Top 6 Trackers to Master Your Computer'inas Windows Domain</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
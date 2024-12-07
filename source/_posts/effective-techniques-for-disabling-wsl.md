---
title: Effective Techniques for Disabling WSL
date: 2024-12-02T02:37:15.945Z
updated: 2024-12-07T04:00:02.474Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-tidied-missing-miniature-videos-on-youtube/"><u>[New] 2024 Approved Tidied Missing Miniature Videos on YouTube</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-content-creation-conundrum-where-to-go/"><u>[New] In 2024, Content Creation Conundrum Where to Go?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-top-10-free-templates-for-engaging-presentations-and-slideshows/"><u>[New] In 2024, Top 10 Free Templates for Engaging Presentations and Slideshows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevating-creative-content-vimeo-vs-youtubes-approach-for-2024/"><u>[Updated] Elevating Creative Content Vimeo vs YouTube's Approach for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-best-drawing-apps-for-iphones/"><u>[Updated] In 2024, Best Drawing Apps for iPhones</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-superb-phone-video-and-photo-capturing-with-best-apps-list/"><u>2024 Approved Superb Phone Video & Photo Capturing with Best Apps List</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-comprehensible-breakdown-for-youtube-annotation-and-card-implementation/"><u>A Comprehensible Breakdown for YouTube Annotation and Card Implementation</u></a></li>
<li><a href="https://buynow-info.techidaily.com/decoding-value-an-in-depth-look-at-the-costly-microsoft-surface-studio-2/"><u>Decoding Value: An In-Depth Look at the Costly Microsoft Surface Studio 2</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-excessive-memory-consumption-in-edges-view2/"><u>Eliminating Excessive Memory Consumption in Edge's View2</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-windows-desktop-visual-aesthetics/"><u>Fine-Tuning Windows Desktop Visual Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-synapses-device-ignorance-on-latest-windows-os/"><u>Fixing Synapse's Device Ignorance on Latest Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-problem-fixes-for-windows-11-and-11-enterprise/"><u>Mastering Printer Problem Fixes for Windows 11 & 11 Enterprise</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-sharing-in-action-top-5-fileshare-software-for-pcs/"><u>Seamless Sharing in Action: Top 5 Fileshare Software for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/why-disable-yourphoneexe-insights-for-windows-xp-lovers/"><u>Why Disable YourPhoneExe? Insights for Windows XP Lovers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    
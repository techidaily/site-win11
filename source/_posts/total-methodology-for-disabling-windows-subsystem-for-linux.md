---
title: Total Methodology for Disabling Windows Subsystem for Linux
date: 2024-12-16T16:30:01.204Z
updated: 2024-12-22T17:13:06.212Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Total Methodology for Disabling Windows Subsystem for Linux
excerpt: This Article Describes Total Methodology for Disabling Windows Subsystem for Linux
keywords: Disable WSL (Windows Subsystem),Turn Off Windows Subsystem for Linux,Stop Windows Subsystem Functionality,Cease WSL Operations in Windows,Inhibit Linux Subsystem on Windows OS,End Windows Subsystem Service,Terminate WSL Activation Windows-Wise
thumbnail: https://thmb.techidaily.com/ea90287aad1128dcf73001caefa47ec3f1c16bb10f0ed6607a3b7c4f98575dff.jpg
---

## Total Methodology for Disabling Windows Subsystem for Linux

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/new-djis-quadcopters-variants-basic-model-advanced-series-uhd-edition/"><u>[New] DJI's Quadcopters Variants Basic Model, Advanced Series, UHD Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-enhancing-your-iphone-experience-voice-memo-techniques/"><u>[New] In 2024, Enhancing Your iPhone Experience Voice Memo Techniques</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-making-a-channels-story-visible-in-snippets/"><u>[New] In 2024, Making a Channel's Story Visible in Snippets</u></a></li>
<li><a href="https://win-superb.techidaily.com/6-to-server-2019-a-comprehensive-guide/"><u>6 to Server 2019 - A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/halt-spontaneous-terminal-flashes-in-windows/"><u>Halt Spontaneous Terminal Flashes in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mkv-m4v-online-video-converter-movavi/"><u>MKV, M4V를 비용 부과 없이 효율적으로 Online Video Converter - Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-your-digital-landscape-with-regular-windows-backups/"><u>Protecting Your Digital Landscape with Regular Windows Backups</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unavailable-value-error-in-windows-operations/"><u>Resolving Unavailable Value Error in Windows Operations</u></a></li>
<li><a href="https://discord-videos.techidaily.com/sever-ties-with-discord-network/"><u>Sever Ties With Discord Network</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/step-by-step-guide-to-elevating-your-channel-brand-growth-in-viewers-for-2024/"><u>Step-by-Step Guide to Elevating Your Channel Brand, Growth in Viewers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-eliminating-windows-generic-sound-problem/"><u>Steps for Eliminating Windows Generic Sound Problem</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/visual-tweets-the-panorama-of-threaded-video-for-2024/"><u>Visual Tweets The Panorama of Threaded Video for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/why-does-my-new-world-game-keep-freezing-solve-the-mystery/"><u>Why Does My 'New World' Game Keep Freezing? Solve the Mystery</u></a></li>
</ul></div>


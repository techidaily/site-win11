---
title: "Step-by-Step Approach: Augmenting Virtual Memory on Windows 11"
date: 2024-12-08T20:28:23.259Z
updated: 2024-12-13T00:36:16.153Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Approach: Augmenting Virtual Memory on Windows 11"
excerpt: "This Article Describes Step-by-Step Approach: Augmenting Virtual Memory on Windows 11"
keywords: Virtual Memory Enhancement Windows,Windows VM Optimization Guide,Boost WM Performance Increase,Improving RAM in Win11,Virtual Space Expansion Windows,W11 RAM Utilization Tips,Enhancing Memory Efficiency Win11
thumbnail: https://thmb.techidaily.com/be34f09b3263dabe58e7e8e9b611840eed5d78451bd041646a395d4031103684.jpg
---

## Step-by-Step Approach: Augmenting Virtual Memory on Windows 11

 Your computer slowing down isn't a great feeling. Is it overheating? Is the CPU old? Or is it that you've run out of memory?

 Running out of memory affects your system from top to bottom, making regular tasks suddenly feel like walking through treacle.

 If that sounds like your Windows 11 installation, it's time to check out your virtual memory settings to make sure your system can cope with demand. So, here's how you change the virtual memory size on Windows 11, along with a few tips on boosting your system performance.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Virtual Memory?

 We've[previously explained virtual memory](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) in more detail, but here is an outline to bring you up to speed.

> Your hard drive is where your operating system lives, as well as your photos, music, games, documents, and otherwise. Your RAM stores program-specific data. It is much faster but also more volatile, acting as a working storage area for the programs and files you have open.

> So, what is virtual memory?

> Well, if you use all the RAM available to your system, it will utilize virtual memory—also known as a swap or paging file—to provide a temporary expansion. Your system's virtual memory does this using part of your hard-drive memory to expand your RAM effectively. So, this virtual memory is extremely useful. It allows your system to handle more data for more programs than previously available.

[When your RAM runs low](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , your system will call upon the paging file to handle some of the extra data. However, as your hard drive or even solid-state drive is much slower than your RAM, system performance will take a hit.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Windows 11 Is Running Low on Virtual Memory

 Now, the thing is, virtual memory has its own limits. It isn't an infinite well of additional yet slower memory you can call upon. If you begin to run out of virtual memory, Windows 11 will display the following error message:

> Your system is low on virtual memory. Windows is increasing the size of your virtual memory paging file. During this process, memory requests for some applications may be denied. For more information, see help.

 Windows 11 will automatically manage your virtual memory, ensuring that the paging file has enough capacity to handle your system demands. However, you can also manually increase the size of your paging file on Windows 11 if you're comfortable making decisions regarding how much RAM you have installed.

 Windows sets the initial virtual memory paging file equal to the amount of installed RAM. The paging file is a minimum of 1.5 times and a maximum of three times your physical RAM. You can use the following system to calculate your Windows 11 paging file (using a system with 8GB installed as the example), providing you know[how much RAM you have installed](https://www.makeuseof.com/windows-check-installed-ram-available-ram-slots/) .

* **Minimum** : 1024_8_ 1.5=12288 \[1GB RAM x Installed RAM x Minimum\]
* **Maximum** : 1024_8_ 3=24576 \[1GB RAM x Installed RAM x Maximum\]

 Still, both of these values are high.[Microsoft recommends](http://docs.microsoft.com/en-us/windows/client-management/determine-appropriate-page-file-size) "3 × RAM or 4 GB, whichever is larger," which will protect your system from instability when you do use your paging file. However, Windows' automatic paging file management might decide otherwise, so it's typically best to let the operating system figure things out for itself. For example, in the image below, you can see that on my Windows 10 machine with 32GB RAM installed, the paging file is automatically set at just under 7GB.

 Furthermore, remember that these values take up space on your hard drive, as Windows allocates the overall paging file space in case it needs it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Increase Virtual Memory Size on Windows 11

 If you want to go ahead and manually alter the paging file size on Windows 11 to remove the virtual memory low message, here's how you go about it.

![windows 11 advanced system settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/windows-11-advanced-system-settings-option.jpg)

1. Press**Windows key + I** to open the**Settings** app.
2. Head to**System > About** .
3. Select**Advanced system settings** .
4. Under**Performance** , select**Settings** .
5. Open the**Advanced** tab. Under**Virtual memory** , select**Change** . Here are your Virtual Memory options.
6. If you want to set custom virtual memory settings, you'll have to uncheck the box to**Automatically manage paging file size for all drives** . Once you clear the check box, the Virtual Memory options below will become accessible. Select**Custom Size,** then input your desired virtual memory size and select**OK** .

![windows 11 system properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-system-properties.png)

![windows 11 performance options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-performance-options.png)

![windows 11 virtual memory options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-virtual-memory-options.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Close

 Keep in mind the virtual memory management tips in the previous section. It might seem like drastically increasing your paging file is a great idea, but it's almost guaranteed to cause system instability when you least expect it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Install More RAM to Boost Your System Performance

 Increasing your virtual memory size is a temporary fix and isn't one you should rely on long-term. The only way to truly fix your low virtual memory issue[is to install more RAM](https://www.makeuseof.com/how-to-install-ram/) . The reason your system is turning to the paging file to begin with is that additional data is being palmed off.

 The answer is to install more RAM, which in turn will give your whole system a boost as you'll no longer run out of memory and have to use the slower paging file instead. It's easier to install more RAM on a desktop computer than on a laptop, but[upgrading the RAM on a laptop is possible](https://www.makeuseof.com/tag/upgrading-a-laptops-ram-step-by-step-si-x2/) . Unfortunately, if you don't have any more RAM slots, have reached the maximum RAM capacity, or find that your laptop has soldered RAM, you're flat out of luck.

 You can[attempt to free up more RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) , but ultimately, you're probably going to need a new laptop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Increasing the Windows 11 Paging File Size Is a Temporary Fix

 Boosting the paging file size on Windows 11 or any operating system is a temporary fix. If you're butting up against your memory limit frequently and your computer begins to slow to a crawl, there is only one true fix.

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
<li><a href="https://youtube-docs.techidaily.com/oost-engagement-discover-the-top-5-youtube-promotion-tactics-for-2024/"><u>[New] Boost Engagement Discover the Top 5 YouTube Promotion Tactics for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-immediate-mp3-download-from-facebook-media-posts-for-2024/"><u>[New] Immediate MP3 Download From Facebook Media Posts for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-beat-bringers-sourcing-premium-dj-visuals/"><u>[New] In 2024, Beat Bringers Sourcing Premium DJ Visuals</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-insta-stories-enhancing-background-blur-technique/"><u>[New] Insta Stories Enhancing Background Blur Technique</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-comprehensive-approach-to-integrating-whiteboards-in-zoom-sessions-for-2024/"><u>[Updated] Comprehensive Approach to Integrating Whiteboards in Zoom Sessions for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-evaluating-active-8-does-it-match-best-recording-standards/"><u>[Updated] In 2024, Evaluating Active 8 - Does It Match Best Recording Standards?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-latest-hp-deskjet-2600-printer-drivers-for-windows-operating-systems-7810/"><u>Download the Latest HP Deskjet 2600 Printer Drivers for Windows Operating Systems - 7/8/10</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-technology-for-enhanced-macos/"><u>Exploiting Windows Technology for Enhanced macOS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-ft232r-usbuart-driver-free-fast-and-reliable-download/"><u>Get the Latest FT232R USB/UART Driver - Free, Fast, and Reliable Download</u></a></li>
<li><a href="https://win11.techidaily.com/go-green-with-pc-updates-ditch-windows/"><u>Go Green with PC Updates: Ditch Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagrams-updated-strategy-and-its-effects-for-2024/"><u>Instagram’s Updated Strategy and Its Effects for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-w11s-screensaver-and-crash-dilemmas/"><u>Overcoming W11's Screensaver and Crash Dilemmas</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-up-game-resolving-steam-write-problems/"><u>Stepping Up Game: Resolving Steam Write Problems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-respond-and-recover-windows-download-issues/"><u>Strategies to Respond and Recover Windows Download Issues</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-grayed-recycle-icon-issue-in-win11/"><u>Tackling Grayed Recycle Icon Issue in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-peak-potential-7-efficient-practices-for-windows-11-users-42/"><u>Unleash Peak Potential: 7 Efficient Practices for Windows 11 Users (42)</u></a></li>
</ul></div>


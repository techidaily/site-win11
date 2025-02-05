---
title: "Reviving Windows: Upgrading Obsolete System Drivers"
date: 2025-02-02T02:36:31.435Z
updated: 2025-02-03T19:47:37.639Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Windows: Upgrading Obsolete System Drivers"
excerpt: "This Article Describes Reviving Windows: Upgrading Obsolete System Drivers"
keywords: Driver Upgrade Tips,Update Old Windows,Revive Outdated OS,Fix Windows Issue,System Driver Renewal,Windows Performance Boost,Drivers For Elders OS
thumbnail: https://thmb.techidaily.com/e66e28dff9a78d29ac6c41d0e2dd487a7c339d734ca57b3143f21e9c629c5f8e.jpg
---

## Reviving Windows: Upgrading Obsolete System Drivers

 Do you know what drivers are installed on your Windows 10/11 computer? Do those drivers need updating? And if so, how do you even update them?

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Check Your Installed Drivers

 You will have drivers on your system, even if you didn't manually install them, but you may not know what they are or what version you have. There are various ways to check this.

 When you come across a date associated with a driver, this usually refers to when the driver was published, not necessarily when you installed it.

### 1\. Use Device Manager

 A user-friendly way to check drivers is through Device Manager. There are plenty of [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/); a simple method is to press **Windows key + X** and select **Device Manager**.

 This shows all your devices split by category (like **Disk drives**, **Monitors**, and **Printers**). To see a device's driver details:

1. **Double-click** a category to expand it and see the devices within.
2. **Right-click** a device and click **Properties**.
3. Click the **Driver** tab.
4. If you need more information and want to view the installed driver files, click **Driver Details**.

![device manager driver details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/device-manager-driver-details.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use DriverView

[DriverView](https://www.nirsoft.net/utils/driverview.html) is a free utility that lists all your drivers in a single table. It provides lots of information about those drivers, like the version number, manufacturer, and file path. To use DriverView, download the ZIP, extract it, and open the EXE.

![DriverView](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/driverview.jpg)

 DriverView is a simple program, but it has some handy features, such as:

* To adjust the table, select **View** from the toolbar and use options like **Mark Non-Microsoft Drivers** and **Choose Columns** as needed.
* Export the data via **File > Save Selected Items** or **View > HTML Report** (then save the page).
* If you require additional information about a driver, select the row and go to **File > Google Search**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Use Command Prompt

 Windows' Command Prompt can generate a report of all your drivers. Historically, this worked well, but the information is often unreliable on Windows 10 and Windows 11\.

 As such, when you need a list of all drivers, the best solution is to use third-party software, as explained above. However, if you're using an older version of Windows, or don't want to install additional software, you can use the Command Prompt method explained here.

 To begin, open Command Prompt: press **Windows key + R** to open Run, input **cmd**, and click **OK**. Then, to run the report, type **driverquery** and press **Enter**.

 To get the information in a handy text file that you can refer to later, type **driverquery > driver.txt**. The file saves wherever your Command Prompt path is set. See [Microsoft's driverquery page](https://learn.microsoft.com/windows-server/administration/windows-commands/driverquery) for more advanced parameters.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

### 1\. Use Windows Update

 In most cases, Windows automatically keeps your drivers updated through Windows Update. This is safe because the drivers are verified and should only be delivered to your system if they're necessary and compatible.

 To manually perform a Windows Update, press **Windows key + I** to open Settings and go to **Update & Security > Windows Update > Check for updates** (Windows 10) or **Windows Update > Check for updates** (Windows 11).

![windows 11 windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-windows-update.jpg)

 You can [disable automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) if you want, perhaps if the latest version is causing trouble, but generally you should let Windows Update do its thing.

 Windows Update also provides some drivers as optional downloads—in other words, the drivers aren't automatically updated. Generally, you should only install optional driver updates if you have a specific problem. To do that, from the Windows Update page:

1. Click **View optional updates** (Windows 10) or **Advanced options > Optional updates** (Windows 11).
2. Click **Driver updates** to expand the category. You won't see this if there aren't any updates.
3. Check the driver(s) you wish to install.
4. Click **Download and install**.

![windows 11 view optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-view-optional-updates.jpg)

### 2\. Use the Manufacturer's Website

 You can also download drivers yourself through the hardware manufacturer's website. To ensure the driver is safe and the latest version, don't use any unofficial websites.

 Use one of the methods provided earlier to find out what drivers you have and which company produces them. Head to the manufacturer's website and look for the driver section (perhaps under "Downloads" or "Support"). Some providers, like AMD and NVIDIA, have tools that scan your system and detect what driver you need if you're unsure. Some also have proprietary software that keeps the driver updated and provides other functionality.

 Most drivers come as executables that update what's necessary when run. If not, use Device Manager to install them:

1. Press **Windows key + X** and select **Device Manager**.
2. **Double-click** a category to expand it and see the devices within.
3. **Right-click** a device and click **Update driver**.
4. Click **Browse my computer for drivers**.
5. Click **Browse** and navigate to the folder where you downloaded the driver.
6. Click **OK**.
7. Click **Next** and follow the wizard to completion.

![windows 10 browse for drivers on your computer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-10-browse-for-drivers-on-your-computer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Drivers Keep Your Computer Running Smoothly

 You may find that all your drivers are already up-to-date, thanks to Windows Update. If everything is working well, you might be better off not updating them at all. It's usually things like graphics cards, which receive constant patches to support recent games, that need updating the most.

 Remember, if not through Windows Update, always download your drivers directly from the device manufacturer. Also, don't install any which weren't made specifically for your devices.

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-science-behind-engaging-video-content-on-fb/"><u>[New] In 2024, The Science Behind Engaging Video Content on FB</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-rhythm-rulebook-seamlessly-mixing-music-into-instagram-posts-for-2024/"><u>[New] The Rhythm Rulebook Seamlessly Mixing Music Into Instagram Posts for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-busting-myths-essential-facts-on-instagrams-reels-for-2024/"><u>[Updated] Busting Myths Essential Facts on Instagram's Reels for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/easy-methods-how-to-transfer-pictures-from-apple-iphone-13-pro-max-to-pc-drfone-by-drfone-transfer-from-ios/"><u>Easy Methods How To Transfer Pictures From Apple iPhone 13 Pro Max to PC | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-nubia-red-magic-9-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-exact-video-editing-a-step-by-step-guide/"><u>Mastering the Art of Exact Video Editing: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mp4pcgif5/"><u>MP4ビデオをPC上でGIFへの変換方法:5選ベストガイド</u></a></li>
<li><a href="https://win11.techidaily.com/offline-entertainment-unlimited-quick-download-movies-shows-songs-and-special-features-for-on-the-go-viewing/"><u>Offline Entertainment Unlimited: Quick-Download Movies, Shows, Songs, and Special Features for On-The-Go Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/playing-japanese-region-bddvd-on-american-systems-without-a-specialized-disc-player/"><u>Playing Japanese Region BD/DVD on American Systems Without a Specialized Disc Player</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-conversion-top-3-techniques-for-turning-your-google-slides-into-videos/"><u>Seamless Conversion: Top 3 Techniques for Turning Your Google Slides Into Videos</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-audio-conversion-discover-the-three-best-avi-to-mp3-transformation-techniques/"><u>Simplify Audio Conversion: Discover the Three Best AVI to MP3 Transformation Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-ac3-audio-format-conversion-the-ultimate-tool-for-fast-and-effortless-mp3-creation/"><u>Speedy AC3 Audio Format Conversion: The Ultimate Tool for Fast and Effortless MP3 Creation</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-on-downloading-snappea-software-for-your-windows-computer/"><u>Step-by-Step Guide on Downloading Snappea Software for Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-dvd-collection-into-common-video-formats-like-mp4-mkv-and-more/"><u>Step-by-Step Guide: Converting Your DVD Collection Into Common Video Formats Like MP4, MKV & More</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-entire-itunes-library-into-high-quality-mp3-format/"><u>Step-by-Step Guide: Converting Your Entire iTunes Library Into High-Quality MP3 Format</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unraveling-the-art-of-screencasts-a-step-by-step-approach/"><u>Unraveling the Art of Screencasts A Step-by-Step Approach</u></a></li>
<li><a href="https://facebook.techidaily.com/whatsapp-pauses-policy-change-rollout-beyond-may-15/"><u>WhatsApp Pauses Policy Change Rollout Beyond May 15</u></a></li>
</ul></div>


---
title: "Overhauling Windows Drivers: A Step-by-Step Guide"
date: 2025-01-01T21:09:05.703Z
updated: 2025-01-06T18:24:07.324Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overhauling Windows Drivers: A Step-by-Step Guide"
excerpt: "This Article Describes Overhauling Windows Drivers: A Step-by-Step Guide"
keywords: Driver Update Guide,Windows Driver Fixing,PC Driver Repair,System Driver Overhaul,Windows Upgrade,Drivers Troubleshooting,Optimize Windows Drivers
thumbnail: https://thmb.techidaily.com/6e2f3010b64553c858c441b2aa0463f3e8a124b61c9d02d5a4f78ba177103c47.png
---

## Overhauling Windows Drivers: A Step-by-Step Guide

 Do you know what drivers are installed on your Windows 10/11 computer? Do those drivers need updating? And if so, how do you even update them?

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

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

 This method is great if you only need to check a handful of drivers, but it's a bit tedious if you want to see all your drivers. In that case, use an alternative method detailed below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use DriverView

[DriverView](https://www.nirsoft.net/utils/driverview.html) is a free utility that lists all your drivers in a single table. It provides lots of information about those drivers, like the version number, manufacturer, and file path. To use DriverView, download the ZIP, extract it, and open the EXE.

![DriverView](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/driverview.jpg)

 DriverView is a simple program, but it has some handy features, such as:

* To adjust the table, select **View** from the toolbar and use options like **Mark Non-Microsoft Drivers** and **Choose Columns** as needed.
* Export the data via **File > Save Selected Items** or **View > HTML Report** (then save the page).
* If you require additional information about a driver, select the row and go to **File > Google Search**.

### 3\. Use Command Prompt

 Windows' Command Prompt can generate a report of all your drivers. Historically, this worked well, but the information is often unreliable on Windows 10 and Windows 11\.

 As such, when you need a list of all drivers, the best solution is to use third-party software, as explained above. However, if you're using an older version of Windows, or don't want to install additional software, you can use the Command Prompt method explained here.

 To begin, open Command Prompt: press **Windows key + R** to open Run, input **cmd**, and click **OK**. Then, to run the report, type **driverquery** and press **Enter**.

 To get the information in a handy text file that you can refer to later, type **driverquery > driver.txt**. The file saves wherever your Command Prompt path is set. See [Microsoft's driverquery page](https://learn.microsoft.com/windows-server/administration/windows-commands/driverquery) for more advanced parameters.

## How to Update Outdated Windows Drivers

 There are plenty of [reasons to keep drivers updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/). By doing so, you'll ensure software compatibility, and benefit from bug fixes and security patches.

 However, updating your drivers is not always necessary. Importantly, if Windows Update isn't recommending a driver update (which we'll get into shortly), it might mean the driver isn't compatible with your hardware configuration. If everything is working well on your system, you may be better off leaving your drivers alone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Use Windows Update

 In most cases, Windows automatically keeps your drivers updated through Windows Update. This is safe because the drivers are verified and should only be delivered to your system if they're necessary and compatible.

 To manually perform a Windows Update, press **Windows key + I** to open Settings and go to **Update & Security > Windows Update > Check for updates** (Windows 10) or **Windows Update > Check for updates** (Windows 11).

![windows 11 windows update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-windows-update.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can [disable automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) if you want, perhaps if the latest version is causing trouble, but generally you should let Windows Update do its thing.

 Windows Update also provides some drivers as optional downloads—in other words, the drivers aren't automatically updated. Generally, you should only install optional driver updates if you have a specific problem. To do that, from the Windows Update page:

1. Click **View optional updates** (Windows 10) or **Advanced options > Optional updates** (Windows 11).
2. Click **Driver updates** to expand the category. You won't see this if there aren't any updates.
3. Check the driver(s) you wish to install.
4. Click **Download and install**.

![windows 11 view optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-11-view-optional-updates.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-elevate-your-gopro-experience-with-top-rated-sd-card-picks/"><u>[New] In 2024, Elevate Your GoPro Experience with Top-Rated SD Card Picks</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-honor-magic-v2-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Honor Magic V2 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/five-exceptional-sierra-dvd-editors-unveiled-for-2024/"><u>Five Exceptional Sierra DVD Editors Unveiled for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/journey-through-podcast-land-iphoneipad-edition-for-2024/"><u>Journey Through Podcast Land IPhone/iPad Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/liberate-your-computing-experience-freedomgpt/"><u>Liberate Your Computing Experience: FreedomGPT</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-linux-setup-drop-wsl/"><u>Optimal Linux Setup - Drop WSL</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-startup-routine-placing-shortcuts-by-power-icon-in-win11/"><u>Optimizing Startup Routine: Placing Shortcuts by Power Icon in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/outdated-os-new-dawn-atlasos-reboot/"><u>Outdated OS, New Dawn: AtlasOS Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-of-technology-laptops-at-ifa-2023/"><u>Pinnacle of Technology: Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/prove-your-productivity-the-best-6-computer-usage-tracker-tools/"><u>Prove Your Productivity: The Best 6 Computer Usage Tracker Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/replace-vanished-facebook-watch-icon/"><u>Replace Vanished Facebook Watch Icon</u></a></li>
<li><a href="https://win11.techidaily.com/safeguarding-success-essential-fixes-for-windows-security/"><u>Safeguarding Success: Essential Fixes for Windows Security</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-updating-and-downloading-canons-mg3email-protected22-printer-drivers/"><u>Step-by-Step: Updating & Downloading Canon's MG3([email Protected])22 Printer Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-11-pin-setbacks/"><u>Swiftly Solve Your Windows 11 PIN Setbacks</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-compatibility-playbook/"><u>The Ultimate Win Compatibility Playbook</u></a></li>
<li><a href="https://blog-min.techidaily.com/ultimate-guide-top-5-secrets-for-stunning-4k-virtual-reality-videos-and-downloads/"><u>Ultimate Guide: Top 5 Secrets for Stunning 4K Virtual Reality Videos and Downloads</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-elite-17-inch-laptop-picks-for-the-year-2024/"><u>Unveiling the Elite 17-Inch Laptop Picks for the Year 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/why-the-tp-link-archer-c9-is-a-top-choice-for-budget-friendly-routers-reviewed/"><u>Why the TP-LInk Archer C9 Is a Top Choice for Budget-Friendly Routers – Reviewed!</u></a></li>
</ul></div>


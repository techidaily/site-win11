---
title: "Paving the Way for Progress: Updating Windows Drivers"
date: 2024-06-25T09:45:48.855Z
updated: 2024-06-26T09:45:48.855Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Paving the Way for Progress: Updating Windows Drivers"
excerpt: "This Article Describes Paving the Way for Progress: Updating Windows Drivers"
keywords: Driver Update Guide,Windows Driver Support,Upgrade Windows Drivers,New Windows Driver Release,Enhance System Performance,Optimize PC Operating,Streamline Driver Management
thumbnail: https://thmb.techidaily.com/4bdb303f42b83bdabbc89bbaed552a530d980933768bd910a7c15106cfbf73fe.png
---

## Paving the Way for Progress: Updating Windows Drivers

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

## Drivers Keep Your Computer Running Smoothly

 You may find that all your drivers are already up-to-date, thanks to Windows Update. If everything is working well, you might be better off not updating them at all. It's usually things like graphics cards, which receive constant patches to support recent games, that need updating the most.

 Remember, if not through Windows Update, always download your drivers directly from the device manufacturer. Also, don't install any which weren't made specifically for your devices.

 In the simplest terms, a driver is software that enables communication between Windows and your hardware. All sorts of components use drivers: graphics cards, webcams, motherboards, and much more. If you're having system trouble, like a printer not working or games crashing, then it might be indicative that your drivers require updating.

 Let's explore how to find and replace outdated Windows drivers on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-of-windows-11-is-ai-whether-you-like-it-or-not/"><u>The Future of Windows 11 Is AI, Whether You Like It or Not</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-installs-time-mastering-grouped-deployments-with-winstall-on-windows-11/"><u>Cutting Down Installs Time: Mastering Grouped Deployments with Winstall on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-revenue-strategies-for-microsofts-profits/"><u>Windows Revenue Strategies for Microsoft's Profits</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-package-unopenable-error-on-win11-10-oses/"><u>Eliminating the 'Package Unopenable' Error on Win11, 10 OSes</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-solutions-to-spy-on-apple-iphone-xs-max-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>In 2024, Solutions to Spy on Apple iPhone XS Max with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-top-15-non-copyrighted-music-for-montages/"><u>In 2024, Top 15 Non Copyrighted Music for Montages</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-realme-c51-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Realme C51</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-infinix-hot-40-pro-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Infinix Hot 40 Pro via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-journey-to-crafting-wow-worthy-collage-art/"><u>[Updated] The Journey to Crafting Wow-Worthy Collage Art</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-comprehensive-strategies-for-swiftly-clearing-feedback/"><u>[Updated] 2024 Approved  Comprehensive Strategies for Swiftly Clearing Feedback</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-threefold-mastery-in-copy-for-social-media-campaigns-increasing-impact-with-every-word/"><u>[Updated] 2024 Approved  Threefold Mastery in Copy for Social Media Campaigns – Increasing Impact with Every Word</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-incorporating-leadership-in-your-discord-network/"><u>[Updated] 2024 Approved  Incorporating Leadership in Your Discord Network</u></a></li>
<li><a href="https://animation-videos.techidaily.com/is-blender-2d-animation-as-awesome-as-3d/"><u>Is Blender 2D Animation As Awesome As 3D?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>